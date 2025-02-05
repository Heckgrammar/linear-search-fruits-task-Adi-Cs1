          string[] fruits = { "banana", "apple", "orange", "pear", "grape", "pineapple" };
          Console.WriteLine("What fruit would you like to find");
          string fruit = Console.ReadLine();
          for (int i = 0; i <fruits.Length-1 ; i++)
          {
              if (fruits[i] == fruit)
              {
                  Console.WriteLine("True");
                 
              }
             if (i == fruits.Length && fruits[i] != fruit)
             {
            Console.WriteLine("False");
            }
