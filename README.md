# <center><span style="color:yellow">HACKSPLAIN WORKS</span></center>
## <span style="color:blue">C++ Code</span>
This C++ program converts a user-provided string into its corresponding ASCII values.

**Compiling and Running:**

1. Save the code as '(with your preffered name.cpp)'.
2. The C++ version works by creating a string variable called inputaString and asking for user input
```cpp

  cout << "Enter a string: " ;
  cin >> inputaString  ;
  cout << "ASCII values for the characters in the string are: \n" ;
```
Next, a for loop is run 
```cpp
 for (char s: inputaString ){
      int asciiValue = static_cast<int>(s);
cout << s << "(character)" << asciiValue <<"\n " ;



