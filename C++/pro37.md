# Explain string operations and functions in C++. 

A string is referred to as an array of characters. In C++, a stream/sequence of characters is stored in a char array. C++ includes the std::string class that is used to represent strings. It is one of the most fundamental datatypes in C++ and it comes with a huge set of inbuilt functions. 

|Category|Functions and Operators|Functionality|
|---|---|---|
|String Length	|length() or size()|It will return the length of the string.|
|Accessing Characters	|Indexing (using array[index])|To access individual characters using array indexing.|
|Concatenating Strings	|+ Operator|+ operator is used to concatenate two strings.|
|Appending |append()|The append() function adds one string to the end of another.|
|String Comparison	|== Operator|You can compare strings using the == operator.|
^|compare()|The compare() function returns an integer value indicating the comparison result.|
|Substrings	|substr()|Use the substr() function to extract a substring from a string.|
|Searching	|find()|The find() function returns the position of the first occurrence of a substring.|
|Modifying Strings	|replace()|Use the replace() function to modify a part of the string.
|^|insert()|The insert() function adds a substring at a specified position.
|^|erase()|Use the erase() function to remove a part of the string.
|Conversion	|c_str()|To obtain a C-style string from a std::string, you can use the c_str() function.

#### `Example`
```cpp
// this is concatinate using  + Operator
std::string firstName = "Geeks";
std::string lastName = "forGeeks";
std::string fullName = firstName + " " + lastName; 

//this is append()
std::string base = "Hey! Geeks";
base.append(" Welcome to GeeksforGeeks!"); // Append a string

// this is compare using == operator
std::string str1 = "apple";
std::string str2 = "banana";
if (str1 == str2) {
    std::cout << "Strings are equal";
}
else {
    std::cout << "Strings are not equal";
}

//this is compare()
string str1 = "Geeks";
string str2: = "Geeksfor";
int result = str1.compare(str2);

//this is insert()
std::string text = "I have a cat.";
text.insert(9, " black"); // Insert " black" at position 9

```