<p align="left"> <img src="https://komarev.com/ghpvc/?username=seclist&label=Profile%20views&color=f5c2ec&style=flat" alt="seclist" /> </p>


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
