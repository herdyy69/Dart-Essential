# Dart Basic - Essential Dart Learning Project

A comprehensive collection of Dart language examples covering fundamental concepts, control structures, functions, variables, and more. This project is designed to help you learn Dart programming through practical examples.

## 📋 Prerequisites

- **Dart SDK**: Version 3.9.2 or higher
- **Dart CLI**: For running examples and tests

## 🚀 Getting Started

### 1. Install Dependencies

```bash
dart pub get
```

### 2. Run Examples

#### Run the Main Application

```bash
dart run bin/dart_101.dart
```

#### Run Individual Examples

Each example can be run independently:

```bash
# Comments examples
dart run lib/comments/single_line_comment.dart
dart run lib/comments/multi_line_comment.dart
dart run lib/comments/documentation_comment.dart

# Control flow examples
dart run lib/control_flows/if.dart
dart run lib/control_flows/for.dart
dart run lib/control_flows/while.dart
dart run lib/control_flows/do_while.dart
dart run lib/control_flows/switch.dart

# Function examples
dart run lib/functions/main_function.dart
dart run lib/functions/function.dart
dart run lib/functions/anonymous_function.dart

# Variable examples
dart run lib/variables/string.dart
dart run lib/variables/number.dart
dart run lib/variables/boolean.dart
dart run lib/variables/enum.dart
dart run lib/variables/records.dart

# Import examples
dart run lib/imports/import.dart
```

## 📁 Project Structure

```
dart_essential/
├── bin/                    # Main application entry point
│   └── dart_101.dart      # Main application
├── lib/                    # Library code and examples
│   ├── comments/          # Comment examples
│   ├── control_flows/     # Control structure examples
│   ├── functions/         # Function examples
│   ├── imports/           # Import and module examples
│   └── variables/         # Variable type examples
├── test/                  # Unit tests
├── pubspec.yaml          # Project configuration
└── README.md             # This file
```

## 📚 Learning Path

### 1. **Comments** (`lib/comments/`)

- **Single Line Comments**: Basic commenting with `//`
- **Multi-line Comments**: Block comments with `/* */`
- **Documentation Comments**: API documentation with `///`

### 2. **Variables** (`lib/variables/`)

- **Basic Types**: `String`, `int`, `double`, `bool`
- **Advanced Types**: `dynamic`, `late`, `const`
- **Collections**: `List`, `Set`, `Iterable`
- **Special Types**: `void`, `never`, `enum`, `records`, `runes`
- **Generics**: Type parameters with `<T>`

### 3. **Control Flows** (`lib/control_flows/`)

- **Conditional**: `if`, `else if`, `else`
- **Loops**: `for`, `while`, `do-while`
- **Switch**: Pattern matching with `switch`
- **Control**: `break` and `continue` statements

### 4. **Functions** (`lib/functions/`)

- **Main Function**: Entry point of Dart applications
- **Regular Functions**: Parameters, return values, scope
- **Anonymous Functions**: Lambda expressions and closures

### 5. **Imports** (`lib/imports/`)

- **Module System**: How to import and use external code
- **Aliases**: Using `as` keyword for namespace management
- **Utilities**: Practical examples with math and string operations

## 🧪 Testing

Run the test suite:

```bash
dart test
```

## 🔍 Code Quality

This project uses Dart's built-in linter with the recommended rules:

- **Lints**: Configured in `analysis_options.yaml`
- **Code Style**: Enforces consistent formatting
- **Best Practices**: Follows Dart style guide

## 📖 Example Outputs

### Variables Example

```dart
// String example
String name = 'Alice';
print('Hello, $name!'); // Output: Hello, Alice!

// Number example
int age = 25;
double height = 175.5;
print('Age: $age, Height: $height cm');
```

### Control Flow Example

```dart
// For loop example
for (var counter = 0; counter < 5; counter++) {
  print('Counter value is $counter');
}
```

### Function Example

```dart
// Function with parameters and return value
double calculateCircleArea(double radius) {
  const double pi = 3.14159;
  return pi * radius * radius;
}
```

## 🎯 Learning Objectives

After completing this project, you will understand:

- ✅ Dart syntax and basic language features
- ✅ Variable types and their usage
- ✅ Control flow structures
- ✅ Function definition and usage
- ✅ Import system and module organization
- ✅ Code commenting and documentation
- ✅ Testing and code quality practices

## 📝 Notes

- Each example is self-contained and can be run independently
- Examples progress from basic to more advanced concepts
- Code includes comments explaining key concepts
- Follows Dart best practices and style guidelines

## 🤝 Contributing

Feel free to add more examples or improve existing ones. Make sure to:

1. Follow the existing code style
2. Add appropriate comments
3. Test your changes
4. Update this README if needed

---

**Happy Learning! 🎉**

# Dart-Essential
