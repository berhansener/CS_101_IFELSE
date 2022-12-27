# CS_101_IFELSE
```cs
using System;

    namespace if_else_if
    {
        class Program
        {
            static void Main(string[] args)

            {
                int time = DateTime.Now.Hour;

                if(time>6 && time <11)

                    Console.WriteLine("Günaydın");
                else if(time <=18)
                    Console.WriteLine("iyi Günler");
                else
                    Console.WriteLine("iyi akşamlar");

                string sonuc =  time <= 18 ? "iyi Günler": "İyi geceler";

                sonuc = time >= 6 && time < 11 ? "Günaydın" : time<=18 ? "İyi Günler" : "İyi geceler";
                Console.WriteLine(sonuc);

            }
            

        }
    }
    ```
