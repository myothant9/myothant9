<!-- Header -->
<p align="center">
  <img src="./header.svg" width="100%" alt="Myo Thant Naing" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=22&duration=3000&pause=1000&color=2C5364&center=true&vCenter=true&width=600&lines=Welcome+to+my+GitHub!;Thanks+for+stopping+by;Have+a+wonderful+day!" alt="Typing SVG" />
</p>

<p align="center">
  <img src="./divider.svg" width="100%" alt="divider" />
</p>

<!-- AI robot petting an orange cat -->
<p align="center">
  <img src="./robot.svg" width="100%" alt="AI robot petting a cat" />
</p>

<p align="center">
  <img src="./divider.svg" width="100%" alt="divider" />
</p>

<!-- Night sky with orbiting planets -->
<p align="center">
  <img src="./orbit.svg" width="100%" alt="Orbiting planets" />
</p>

<p align="center">
  <img src="./divider.svg" width="100%" alt="divider" />
</p>

<!-- C# demo -->
<h3 align="center">💻 A little C# about me</h3>

```csharp
using System;
using System.Collections.Generic;
using System.Linq;

public record Skill(string Name, int Level);   // Level: 1–5

public class Developer
{
    public string Name { get; } = "Myo Thant Naing";
    public string Role { get; } = "Developer & automation enthusiast";

    public List<Skill> Skills { get; } = new()
    {
        new("C#", 4),
        new("JavaScript / Node.js", 4),
        new("Git & GitHub Actions", 4),
        new("SQL", 3),
        new("AI-assisted workflows", 5),
    };

    public IEnumerable<string> Strongest(int min = 4) =>
        Skills.Where(s => s.Level >= min)
              .OrderByDescending(s => s.Level)
              .Select(s => $"{s.Name} {new string('★', s.Level)}");

    public string Greet() => $"Hi, I'm {Name} – thanks for visiting! 👋";
}

public static class Program
{
    public static void Main()
    {
        var me = new Developer();
        Console.WriteLine(me.Greet());
        Console.WriteLine($"Role: {me.Role}");
        foreach (var skill in me.Strongest())
            Console.WriteLine($"  • {skill}");
    }
}
```

<details>
<summary>▶ Output</summary>

```text
Hi, I'm Myo Thant Naing – thanks for visiting! 👋
Role: Developer & automation enthusiast
  • AI-assisted workflows ★★★★★
  • C# ★★★★
  • JavaScript / Node.js ★★★★
  • Git & GitHub Actions ★★★★
```

</details>

<p align="center">
  <img src="./divider.svg" width="100%" alt="divider" />
</p>

<!-- GitHub activity -->
<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=myothant9&show_icons=true&hide_border=true&bg_color=0F2027&title_color=91EAE4&icon_color=86A8E7&text_color=ffffff" alt="GitHub stats" />
  <img height="165" src="https://streak-stats.demolab.com?user=myothant9&hide_border=true&background=0F2027&ring=91EAE4&fire=86A8E7&currStreakLabel=91EAE4&sideLabels=ffffff&currStreakNum=ffffff&sideNums=ffffff&dates=cccccc" alt="GitHub streak" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=myothant9&bg_color=0F2027&color=91EAE4&line=86A8E7&point=ffffff&area=true&hide_border=true" alt="Contribution graph" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=myothant9&style=flat-square&color=0F2027&label=Profile%20views" alt="Profile views" />
</p>

<!-- Footer -->
<p align="center">
  <img src="./footer.svg" width="100%" alt="footer" />
</p>
