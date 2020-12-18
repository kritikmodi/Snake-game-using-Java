### CONCEPTS USED :

* **Inheritance :** The concept wherein one class inherits the elements of another class is known as _Inheritance_. The class which inherits is known as the _sub-class_ and the class whose elements are inherited is known as the _super-class._ For using inheritance in Java programs, the `extends` keyword is used.

  > _Syntax_ : `(sub-class) extends (super-class)`

* **Interfaces :** An _interface_ is an abstract class which is used to group together similar methods with empty bodies. To use the methods of an interface in another class, we use the `implements` keyword.

  > _Syntax_ : `interface (name)`
  >
  > `{`
  >
  > ​    `method1();`
  >
  > ​    `method2();`
  >
  > ` }`
  >
  > `(class) implements (interface)`

* **Java GUI Frameworks :** GUI frameworks are tools which help the user to create graphical features in the program. Java offers many GUI frameworks to choose from.

  > Some of them are : 
  >
  > - JavaFX
  > - AWT
  > - Swing
  > - SWT
  > - Apache Pivot
  > - SwingX
  > - JGoodies
  > - QtJambi
  > - Blade
  > - GWT

  > Read more about Java GUI frameworks [here.](https://techsore.com/java-applications/#:~:text=JGoodies%20java%20GUI%20framework%20offers,create%20a%20java%20user%20interface.)

  In this game, we have used `Swing(javax.swing)` and `AWT(java.awt)`.

### PACKAGES USED : 

* **`javax.swing` :** Imports the complete _Swing_ GUI which provides lightweight GUI components which work on almost all platforms.
* **`javax.swing.JFrame :`** This line imports the _Swing_ component architecture, more specifically - the `JFrame` class. The `Jframe` class is an extended version of the `java.awt.Frame` class.
* **`java.awt :`** This is the _AWT_ or _Abstract Window Toolkit_ package. AWT is an API to develop GUI or window-based applications in Java. 
* **`java.util.random` :** The line imports the `random()` method from Java _Utility_ package. The random() method is used to generate random numbers either indefinitely or within any specified range. 

### CLASSES CREATED : 

3 classes have been created for implementing this game : `SnakeGame(), GameFrame() and GamePanel()`. 

* **`SnakeGame()` :** This is the main class of the game which declares/calls the `GameFrame()` class.
* **`GameFrame()` :** This class extends the `JFrame` class and creates a new frame. It also declares/calls the `GamePanel()` class.
* **`GamePanel()` :** This class extends the `JPanel` class and also implements the `ActionListener()` interface. It creates a new panel inside the frame created earlier and handles the gameplay of the game.