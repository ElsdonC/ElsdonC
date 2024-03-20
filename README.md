```java
import java.util.List
public class Profile {
    private String name;
    private String school;
    private List<String> interests;
    private List<String> skills;

    public Profile(String name, String school, List<String> interests, List<String> skills) {
        this.name = name;
        this.school = school;
        this.interests = interests;
        this.skills = skills;
    }

    public static void main(String[] args) 
        List<String> interests = List.of("Backend", "AI/ML");
        List<String> skills = List.of("Java", "Python", "C", "JavaScript", "React", "Node", "MongoDB", "SQL", "Git");

        Profile myProfile = new Profile("Elsdon Chang", "University of Minnesota", interests, skills);
    }
}
```
