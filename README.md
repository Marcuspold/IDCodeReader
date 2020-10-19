# IDCodeReader

## Substring

```
 class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Good Morning!");
            string somestring = "interpolation";
            Console.WriteLine($"{somestring.Length}");
            string newstring = somestring.Substring(0, 5);
            Console.WriteLine(newstring);
            string polationstring = somestring.Substring(5, 8);
            Console.WriteLine(polationstring);
        }
    }
    
```
    
    ## LOGITpe20
    
```
     static void Main(string[] args)
        {
            Console.WriteLine("Good Morning!");
            DisplayLOGIT();
            Displaype();
            Display20();
        }
        public static void DisplayLOGIT()
        {
            string Word = "LOGITpe20";
            string LOGIT = Word.Substring(0, 5);
            Console.WriteLine(LOGIT);
        }
        public static void Displaype()
        {
            string Word = "LOGITpe20";
            string pe = Word.Substring(5, 2);
            Console.WriteLine(pe);
        }
        public static void Display20()
        {
            string Word = "LOGITpe20";
            string Twenty = Word.Substring(7, 2);
            Console.WriteLine(Twenty);
        }
        
```
        
        
        ## YearValidator
       
```
       class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Good Morning!");
            Console.WriteLine("Enter Your Year Of Birth: ");
            string Birth = Console.ReadLine();

            if(Validate(Birth))
            {
                Userage(Birth);
            }
        }
        public static bool Validate(string Input)
        {
            if (Input.Length == 4) 
            {
                try
                {
                    long.Parse(Input);
                    Console.WriteLine("All Good.");
                    return true;
                }
                catch(Exception error)
                {
                    Console.WriteLine(error);
                    return false;
                } 
                
                
                    
                
            }
            else
            {
                Console.WriteLine("Wrong Format.");
                return false;
            }

        }
        public static void Userage(string YearOfBirth)
        {
            int year = Int32.Parse(YearOfBirth);

            DateTime now = DateTime.Now;
            string currentYear = now.Year.ToString();
            int yearNow = Int32.Parse(currentYear);
            int age = yearNow - year;
            Console.WriteLine($"You are now {age} years old.");
        }


    }
    ```   
    
       
       
        
        
 

    
