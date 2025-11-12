# AVL Tree in C++

This project is a C++ implementation of a **Self-Balancing Binary Search Tree (AVL)**.

The AVL Tree is a fundamental data structure that guarantees a search, insertion, and deletion time complexity of **O(log n)**, avoiding the worst-case scenario of a simple binary search tree (which would be O(n)).

## Demonstrated Concepts

*   **Advanced Data Structures:** Complete implementation of the AVL Tree logic.
*   **Object-Oriented Programming (OOP):** Use of classes, inheritance (`MinhaArvoreAVL` inherits from `ArvoreBinariaDeBusca`), and templates (`template <typename T>`) to create a generic structure.
*   **Balancing Algorithms:** Implementation of the four rotation operations necessary to maintain the AVL property:
    *   **Simple Right Rotation**
    *   **Simple Left Rotation**
    *   **Double Left-Right Rotation**
    *   **Double Right-Left Rotation**
*   **Recursion:** Extensive use of recursive functions for operations such as insertion, deletion, node counting, and traversals (in-order, pre-order, post-order).
*   **Memory Management:** Use of `new` and `delete` for dynamic node allocation and deallocation.

## Project Structure

*   `MinhaArvoreAVL.h`: Contains the implementation of the `MinhaArvoreAVL` class with all the balancing logic and operations.
*   `ArvoreBinariaDeBusca.h`: Base header file (likely provided by the instructor) that defines the Binary Search Tree interface.
*   `MinhaListaEncadeada.h`, `ListaEncadeadaAbstrata.h`, `Elemento.h`, `excecoes.h`: Auxiliary files for the implementation of traversals (which return a linked list).

## How to Compile and Run

This project is a set of header and implementation files. To compile, a `main.cpp` file (present in the directory) that instantiates and tests the `MinhaArvoreAVL` class is required.

1.  Ensure you have a C++ compiler (such as g++) installed.
2.  Compile the project:
    
    ```shell
    g++ -std=c++17 main.cpp -o avl_test
    ```
    
3.  Run the test:
    
    ```shell
    ./avl_test
    ```
    

**Language:** C++ **Topics:** AVL Tree, Data Structures, Balancing Algorithms, OOP, Recursion.
