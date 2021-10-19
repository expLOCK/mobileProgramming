using System;

class Employee {
  public string name;
  public int age;
  public int salary;

  public Employee(string name, int age, int salary) {
    this.name = name;
    this.age = age;
    this.salary = salary;
  }

  public virtual void Info() {
    Console.WriteLine($"Name: {name}\n" + 
                      $"Age: {age}\n" + 
                      $"Salary: ${salary}\n");
  }
}

class Zavodchanin : Employee {
  public string zavod;

  public Zavodchanin(string name, int age, int salary, string zavod) : base(name, age, salary) {
    this.zavod = zavod;
  }

  public override void Info() {
    Console.WriteLine("Zavod workers:");
    Console.WriteLine($"Name: {name}\n" + 
                      $"Age: {age}\n" + 
                      $"Salary: ${salary}");
    Console.WriteLine($"Zavod: {zavod}\n");
  }
}

class Kassir : Employee {
  public string magazin;

  public Kassir(string name, int age, int salary, string magazin) : base(name, age, salary) {
    this.magazin = magazin;
  }

  public override void Info() {
    Console.WriteLine("Kassirs:");
    Console.WriteLine($"Name: {name}\n" + 
                      $"Age: {age}\n" + 
                      $"Salary: ${salary}");
    Console.WriteLine($"Magazin: {magazin}\n");
  }
}

class Blogger : Employee {
  public string platform;

  public Blogger(string name, int age, int salary, string platform) : base(name, age, salary) {
    this.platform = platform;
  }

  public override void Info() {
    Console.WriteLine("Bloggers:");
    Console.WriteLine($"Name: {name}\n" + 
                      $"Age: {age}\n" + 
                      $"Salary: ${salary}");
    Console.WriteLine($"Platform: {platform}\n");
  }
}

class Program {
  public static void Main (string[] args) {
    Zavodchanin rabotnik1 = new Zavodchanin("amogus", 21, 1500, "Kirpichnyi");
    rabotnik1.Info();
    Kassir rabotnik2 = new Kassir("Joe Biden", 54, 400, "Pyaterochka");
    rabotnik2.Info();
    Blogger rabotnik3 = new Blogger("Danya Milokhin", 19, 9999999, "TikTok");
    rabotnik3.Info();
  }
}
