# user.java
class User {
    private String name;
    private int age;
    private int screenTime; // in minutes
    private int stressLevel; // Scale: 1-10

    public User(String name, int age, int screenTime, int stressLevel) {
        this.name = name;
        this.age = age;
        this.screenTime = screenTime;
        this.stressLevel = stressLevel;
    }

    public int getScreenTime() {
        return screenTime;
    }

    public int getStressLevel() {
        return stressLevel;
    }
}
