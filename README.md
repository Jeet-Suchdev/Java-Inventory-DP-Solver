Here is a complete README file for your project.

# Java Inventory Solver using Dynamic Programming

A Java application that solves the dynamic lot-sizing problem using a **dynamic programming** algorithm. It features a simple graphical user interface (GUI) built with **Java AWT** to calculate the optimal ordering policy that minimizes total inventory costs over multiple periods. The project is also structured to demonstrate key **Object-Oriented Programming (OOP)** principles.

-----

## Features 📋

  * **Dynamic Programming Core:** Implements a DP algorithm to find the most cost-effective inventory strategy for variable demand.
  * **Simple GUI:** An easy-to-use interface built with Java AWT to input data and view results without needing to touch the code.
  * **OOP by Design:** Clearly demonstrates abstraction, inheritance, and encapsulation for educational purposes.
  * **Error Handling:** Basic validation to handle non-numeric inputs gracefully.

-----

## How to Run 🚀

You can compile and run this project using any standard Java IDE or directly from the command line.

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/Jeet-Suchdev/Java-Inventory-DP-Solver.git
    cd Java-Inventory-DP-Solver
    ```

2.  **Compile the Java code:**

    ```bash
    javac inventory_control_dp.java
    ```

3.  **Run the application:**

    ```bash
    java inventory_control_dp
    ```

    This will launch the GUI window.

-----

## How to Use the Application 💡

1.  **Launch the application** using the steps above.
2.  **Enter Demand:** In the "Demand per Period" field, enter the demand for each period, separated by commas (e.g., `10,20,15,30`).
3.  **Enter Costs:** Fill in the "Holding Cost per Unit per Year" and "Order Cost (per order)" fields with numeric values.
4.  **Enter Periods:** Provide the "Number of Periods" you are calculating for.
5.  **Calculate:** Click the **"Calculate EOQ"** button.
6.  **View Result:** The calculated minimum total cost for the optimal ordering plan will appear in the text area at the bottom.
