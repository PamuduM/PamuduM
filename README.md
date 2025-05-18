```
/**
 * AboutMe.java
 * A glimpse into my tech journey and passion.
 */

import java.util.List;
import java.util.Map;
import java.util.stream.Collectors;

public class AboutMe {
    public static void main(String[] args) {
        String name = "Kusal Gunasekara";
        String role = "Software Engineer";

        Map<String, List<String>> techStack = Map.of(
            "IDE", List.of("IntelliJ IDEA", "VS Code", "WebStorm", "Rider"),
            "App Development", List.of("Java", "Python", "C#"),
            "Frontend", List.of("HTML", "CSS", "JavaScript", "React", "Bootstrap", "Tailwind", "jQuery", "Axios"),
            "Backend", List.of("Hibernate", "MySQL", "Spring", ".NET"),
            "Tools", List.of("GitHub", "Git", "Firebase", "AWS", "Postman", "Stack Overflow")
        );

        System.out.println("👋 Hello, I'm " + name + " - " + role + "!");
        System.out.println("\n🛠️ Tech Stack:");

        techStack.forEach((category, tools) -> {
            String toolsList = tools.stream().collect(Collectors.joining(", "));
            System.out.println("- " + category + ": " + toolsList);
        });

        System.out.println("\n🌟 Always learning, exploring, and building cool stuff!");
    }
}

/**
 * 📌 Find me here:
 * - GitHub: github.com/KusalDemo
 * - LinkedIn: http://www.linkedin.com/in/kusal-gunasekara-337507234
 */

```
<div align="center">
    <p>
  <img src="https://skillicons.dev/icons?i=java,py,cpp,cs,spring,net,nodejs,nestjs,expressjs,html,css,js,ts,react,bootstrap,tailwindcss,figma,jquery,hibernate,regex,mysql,mongodb,postman,flask,prisma,idea,webstorm,rider,vscode,github,git,maven,npm,yarn,vite,gradle,discord,stackoverflow,firebase,notion" alt="Tech Stack" />
</p>
</div>
</div>


