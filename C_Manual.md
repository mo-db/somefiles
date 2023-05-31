### Hello World
  - int main() `so main gives back integer with return`

### Vars and Types
  - int: char, int, short, long or long long
  - unsigned ints: unsigned ", ...
  - floats: float, double
  - **no boolean type in c** but can be defined by doing:
    - #define BOOL char
    - #define FALSE 0
    - #define TRUE 1

### Arrays
  - int numbers[10]; `array with size 10`
  - Multidimensional:
    ```c
    char vowels[2][5] = {
      {'A', 'E', 'I', 'O', 'U'},
      {'a', 'e', 'i', 'o', 'u'}
    };
    int val vowels[2][3]; // would be o
    ```
### if statement
  - if(a == / < / > b) {};
  - if(a < b && / || / != b > c) {};`&& AND, || OR, != NOT`