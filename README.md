This repository contains only two files with the main code for the project. The full version of the project, including dependencies, assets, and launch scripts, is located in the main course repository.  
**To run the project:**  
1.Clone the main course repository:  
`git clone https://github.com/fipl-hse/2025-2-level-labs`  
2.Enter the cloned directory:  
`cd 2025-2-level-labs`  
3.Navigate to the laboratory work #3:  
`cd lab_3_generate_by_ngarms`  
4.Replace the files in the corresponding laboratory work with the files from this repository.  
5.Run the program to verify that it works correctly and to see the results.  

**Laboratory work description**  
Text generation is the process of creating continuous texts by collecting and analyzing available data.  
This laboratory work contains n-gram-based text generation algorithms.  
N-gram - a sequence of n elements included in another sequence.  
Example: encoded text (1, 2, 3). Bigrams: (1,2); (2,3)  
Three algorithms were implemented:  
1) Greedy algorithm  
**The greedy algorithm** is an approach that builds a solution step by step by always choosing the locally optimal option at each stage. Such algorithms are efficient and easy to implement, but they do not always guarantee a globally optimal solution.  
2) Beam Search algorithm  
**The Beam Search algorithm** generates text by exploring multiple possible continuations of a sequence and keeping only the top-N most probable candidates at each step (where N is the beam width). This approach is more robust than a greedy algorithm, as it considers several options simultaneously to produce higher-quality sequences.  
3) BackOff algorithm  
**The BackOff algorithm** generates text using multiple n-gram models of different orders. It first tries to select the next token from the largest n-gram model and backs off to smaller models if no candidates are found, making the generation more robust.
   
