# CS50-ai-degrees

Using search algorithms to find the closest relation between actors and their work



🎬 Degrees of Separation (CS50 AI)



\## 📌 Overview

This project implements a program that determines how two actors are connected through movies — computing the \*\*degrees of separation\*\* between them.



Using real-world data of actors and films, the program finds the shortest path between two people, similar to the “Six Degrees of Kevin Bacon” concept.



\---



\## 🧠 How It Works



The dataset is modeled as a \*\*graph\*\*:



\- \*\*Nodes\*\* → Actors  

\- \*\*Edges\*\* → Movies connecting actors  



To find the shortest path between two actors, the program uses:



\*\*Breadth-First Search (BFS)\*\*



This guarantees the shortest connection in terms of number of steps.



\---



\## ⚙️ Features



\- Finds the shortest path between any two actors  

\- Works with both small and large datasets  

\- Avoids revisiting nodes using an explored set  

\- Outputs the connection step-by-step  



\---



\## 📂 Project Structure



```

degrees/

│── degrees.py       # Main program

│── util.py          # Data structures (Node, Queue, Stack)

│── small/           # Small dataset (for testing)

│── large/           # Full dataset

```



\---



\## ▶️ Usage



Run the program:



```bash

python3 degrees.py large

```



Then input two actor names when prompted.



\---



\## 🧪 Example



```

Name: Emma Watson

Name: Tom Hanks

```



Example output:



```

3 degrees of separation.

1: Emma Watson and Actor X starred in Movie A

2: Actor X and Actor Y starred in Movie B

3: Actor Y and Tom Hanks starred in Movie C

```



\---



\## 🧩 Key Concepts



\- Graph theory  

\- Breadth-First Search (BFS)  

\- State space search  

\- Queue-based exploration  



\---



\## 🚀 Possible Improvements



\- Add a graphical user interface  

\- Optimize performance for large datasets  

\- Cache frequent queries  

\- Visualize the actor network  



\---



\## 📚 Acknowledgements



This project is part of Harvard's \*\*CS50: Introduction to Artificial Intelligence with Python\*\*.



\---



\## 👨‍💻 Author



Karl Henrik May  

https://github.com/khmmay

