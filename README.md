![](https://komarev.com/ghpvc/?seclist&color=green)


```csharp
using System;

class Info
{
    public string Name { get; set; }
    public string Role { get; set; }
    public string[] LanguagesSpoken { get; set; }

    public Info()
    {
        Name = "seclist";
        Role = "student";
        LanguagesSpoken = new string[] { "en_UK" };
    }

    public void SayFact()
    {
        Console.WriteLine("survived another meeting...that couldve been an email");
    }
}

class Program
{
    static void Main()
    {
        Info me = new Info();
        me.SayFact();
    }
}
