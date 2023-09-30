This first example goes against good practice as there is a total lack of indentation.
```
using System; 

namespace HelloWorld 
{ 
class Program   { 
static void Main(string[] args) 
{ 
Console.WriteLine("Hello World!");
}
}
}
```

This can easily be fixed by adding the proper indentation as shown below. This is a good solution as it doesn't add any complexity, and makes the code easier to read.
```
using System; 
namespace HelloWorld
{
    class Program {         
        static void Main(string[] args)
        {
            Console.WriteLine("Hello World!");
        }
    }
}
```
