## Réponses TP 01

```
using System;

class Program {
  public static void Main (string[] args) {
    var agePere = 40;
    var ageMere = 40; // Même age

    if (agePere > ageMere)
    {
      Console.WriteLine("Mon père est plus vieux que ma mère.");
    }
    if (ageMere > agePere)
    {
      Console.WriteLine("Ma mère est plus vieille que mon père.");
    }
    if (ageMere == agePere)
    {
      Console.WriteLine("Mes parents ont le même âge.");
    }
    Console.WriteLine("Ce programme est terminé.");
  }
}
```
```
Mes parents ont le même âge.
Ce programme est terminé.
```
