# <center><span style="color:yellow">HACKSPLAIN ASSIGNMENT 2</span></center>
## <span style="color:orange">C++ Variant</span>
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

## <span style="color:violet">Python Variant</span>
This one is pretty simple. It follows the same logic in the C++ code. Ask the user for input. Store it
in a variable called text.
```python
text = input("Enter a string: ")
```

We then use the ord() function to print out the ASCII values. Feel free to compare the results in both versions. 

```python 
print("The ASCII representation of", text[i], "is", ord(text[i]))
```