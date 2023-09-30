This first example violates C# convention as brackets are not matched with indentation, as there's a total lack of it, also indentation should always be present as it makes code easier to read.
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

This can easily be fixed by adding the proper indentation as shown below. This is a good solution as it makes the code comply with the C# standard and doesn't add any complexity.
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
