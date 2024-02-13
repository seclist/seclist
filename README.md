https://camo.githubusercontent.com/9b4817897b616b2a4b03d55d27b41b307884fffd163dd622e72c7e2a95d104bf/68747470733a2f2f6b6f6d617265762e636f6d2f67687076632f3f757365726e616d653d746572726f72697374266c6162656c3d50726f66696c65253230766965777326636f6c6f723d663563326563267374796c653d666c6174

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
