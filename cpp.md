# [C++](https://www.tutorialspoint.com/cplusplus/)
[cheatsheet](https://github.com/AnthonyCalandra/modern-cpp-features)

## main
```cpp
#include "iostream"
using namespace std;

int main(int argc, char** argv)
{
    for(int i=0;i<argc;++i)
      cout << argv[i];
    
    return 0;
}
```

## [Declarations](https://www.codeproject.com/Articles/7042/How-to-interpret-complex-C-C-declarations)
[Data Types](https://www.tutorialspoint.com/cplusplus/cpp_data_types.htm)

bool, char, int, float, double, void, wchar_t

```cpp
sizeof(char)
```

[null](http://www.cplusplus.com/forum/beginner/7947/)
```cpp
int  *ptr = NULL;
char hello[6] = "Hello";                              // Both of these
char hello[6] = { 'H', 'e', 'l', 'l', 'o', '\0' };    // are null terminated
cout << "hello\0world";                               // Prints only 'hello'
```

[typedef](https://www.codeproject.com/Articles/7042/How-to-interpret-complex-C-C-declarations#typedef)
```cpp
typedef int * feet;
```

[enum](http://www.drdobbs.com/when-enum-just-isnt-enough-enumeration-c/184403955)
```cpp
enum color { red, green = 5, blue };
```


## [IO](https://www.tutorialspoint.com/cplusplus/cpp_basic_input_output.htm)
```cpp
#include <iostream>
using namespace std;
cout << "Size of char : " << sizeof(char) << endl;
float f = 70.0/3.0;
cout << f << endl ;
```

[std::string](https://embeddedartistry.com/blog/2017/7/24/stdstring-vs-c-strings)
```cpp
const char * str = "This is a dumb string literal."
std::string name("Phillip");                         // This one is smart
```
