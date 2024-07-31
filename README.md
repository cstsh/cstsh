<p align="left"> <img src="https://komarev.com/ghpvc/?username=cstsh&label=Profile%20views&color=lightgrey&style=flat" alt="cstsh" /> </p>


```csharp
using System;

class Info
{
    public string Name { get; set; }
    public string Role { get; set; }
    public string[] LanguagesSpoken { get; set; }

    public Info()
    {
        Name = "cure";
        Role = "student";
        LanguagesSpoken = new string[] { "en_US" };
    }

    public void SayFact()
    {
        Console.WriteLine("just one more drop of blood");
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
