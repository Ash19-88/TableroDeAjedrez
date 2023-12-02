# TableroDeAjedrez

This homework involves creating a simple chess game in Java. You will need to create a program that prints a chessboard to the console and allows each piece to play a turn.

## Instructions

1. **Create a new Java class**: Start by creating a new Java class. You can name it `Main`.
2. **Create the main method**: Inside the `Main` class, create a `main` method. This is the entry point of your program.
3. **Create the pieces**: Inside the `main` method, create instances of the `Pieza` class for each type of piece. You will need to create a new instance for each piece.
4. **Play the pieces**: Call the `JugarAjedrez` method on each piece. This method should print a message to the console indicating that the piece is playing chess.

Example
Here is a simple example of how you can implement this:

```import Piezas.*;

public class Main {
  public static void main(String[] args) {
      Pieza reina = new Reina();
      Pieza rey = new Rey();
      Pieza peon = new Peon();
      Pieza caballo = new Caballo();
      Pieza alfil = new Alfil();
      Pieza torre = new Torre();

      reina.JugarAjedrez();
 }
}
```
