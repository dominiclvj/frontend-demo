<style>
code, pre {
  font-size: 0.9rem;
}
</style>

# Data Types

## Learning
In JavaScript, every value belongs to a data type, which defines what kind of information it represents and how the language can work with it. Understanding data types is one of the most important foundations for learning to program, because it affects how you store, manipulate, and compare values in your code.

The most common types are fairly intuitive. A string is text wrapped in quotation marks, such as "Hello" or "Jamila". A number represents both whole numbers (21) and decimals (100.32). A boolean is a simple true/false value that often underpins logic in your programs.

Beyond these basics, JavaScript also has more complex types. An object groups together related data and behaviour in key–value pairs. For example, ```{name: "Jamila", age: 21}``` is an object. Dates ```(new Date())``` are actually specialised objects too. You’ll also encounter arrays, which are ordered lists of values, though technically arrays are a type of object rather than a standalone category.

Two special values are worth noting. Undefined means a variable has been declared but not given a value. Null represents an intentional absence of any object or value. Interestingly, running typeof null returns "object", a quirk that has existed since the earliest versions of JavaScript.

To check the type of any variable, JavaScript provides the typeof operator, which returns a string describing the value’s type. For example, typeof "Hello" is "string", and typeof 42 is "number". This is an essential tool when debugging or teaching yourself how JavaScript interprets different values.