
1. Do not use hyphens or underscores to separate multi-word identifiers (except for constants, which have all upper case letters).

Example
float sumOfSquares = 0;
final int DAYS_IN_YEAR = 365; //Use UPPER_CASE for constants (final variables)


2. Class names start with an upper case letter.
Example

class President {
   //code...
}

3.In-line comments should be used to explain complicated sections of code, such as loops. Use the // comment delimiter for in-line comments. Do not comment generally known features of the java language.

Example
// Do a 3D transmogrification on the matrix.
for (int i = 0; i < matrix.length; i++) {
  for (int j = 0; j < matrix.length; j++) {
    for (int k = 0; k < matrix.length; k++) {
      values.transmogrify(matrix[i],matrix[j],matrix[k]);
    }
  }
}

4. Separate all binary operators, such as "+", "-", "*", "/", "%", etc., with a single space. The exception is unary operators, such as "++", "--", unary minus "-", etc, which do not need to be separated with a single space.
Example
public static void main(String[] arg) {
    System.out.println("Hello" + " " + "World");
  }
  
