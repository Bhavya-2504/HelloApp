# HelloApp Use Cases

## UC1 – Display Hello World

### Description
The application prints a basic greeting message "Hello World" to the console.

### Disadvantages of Previous Use Case
There is no previous use case.

### Preconditions
Java must be installed on the system.

### Main Flow
1. User runs the application.
2. The program starts execution.
3. The console displays "Hello World".

### Post Conditions
The greeting message is shown in the console.

### Hints
Use `System.out.println()` to print text.

### Code Snippet Example

public class HelloApp {
    public static void main(String[] args) {
        System.out.println("Hello World");
    }
}

### Concepts Learned
- Java program structure
- main() method
- Console output