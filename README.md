# <center><span style="color:yellow">HACKSPLAIN ASSIGNMENT 2</span></center>
## <span style="color:blue">C++ Variant</span>
The C++ version works by creating a string variable called text and asking for user input
```cpp
cout << "Enter a text string: ";
    string text;
    cin >> text;
```
Next, a for loop is run and since a string is basically an array of individual characters,
we are able to select each character and use  static cast to show the ASCII values of that character.
```cpp
for (int i = 0; i < text.length(); i++) {
        cout << "The ASCII representation of " << text[i] << " is " << static_cast<int>(text[i]) << endl;
}
```


```