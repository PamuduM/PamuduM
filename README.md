<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=35&center=true&vCenter=true&width=500&height=70&duration=4000&lines=Hello+There...👋;I'm+Pamudu+Mihranga;Full+Stack+Developer💻;&color=FFFFFF&background=FFFFFF00&pause=1000" alt="Typing Animation" /><br>
</h1>

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
        String name = "Pamudu Mihiranga";
        String role = "Software Engineer";

        Map<String, List<String>> techStack = Map.of(
            "IDE", List.of("IntelliJ IDEA", "VS Code", "WebStorm", "Rider"),
            "App Development", List.of("Java", "Python", "C#"),
            "Frontend", List.of("HTML", "CSS", "JavaScript", "React", "Bootstrap", "Tailwind", "jQuery", "Axios"),
            "Backend", List.of("Hibernate", "MySQL", "Spring", ".NET"),
            "Tools", List.of("GitHub", "Git", "Firebase", "AWS", "Postman", "Stack Overflow")
        );

        System.out.println(" Hello, I'm " + name + " - " + role + "!");
        System.out.println("\n Tech Stack:");

        techStack.forEach((category, tools) -> {
            String toolsList = tools.stream().collect(Collectors.joining(", "));
            System.out.println("- " + category + ": " + toolsList);
        });

        System.out.println("\n Always learning, exploring, and building cool stuff!");
    }
}
```
<div align="center">
    <p>
  <img src="https://skillicons.dev/icons?i=java,py,cpp,cs,spring,net,nodejs,nestjs,expressjs,html,css,js,ts,react,bootstrap,tailwindcss,figma,jquery,hibernate,regex,mysql,mongodb,postman,flask,prisma,idea,webstorm,rider,vscode,github,git,maven,npm,yarn,vite,gradle,discord,stackoverflow,firebase,notion" alt="Tech Stack" />
</p>
</div>


## <img src="https://github.com/SP-XD/SP-XD/blob/main/images/message.gif" width="50"/> Let's Connect
<div align="center">
    <p> Open to working on challenging projects, sharing ideas, and contributing to the latest advancements in software development. Let’s connect and create impactful solutions together!<br><br>
</div>
