# Process mining - Python and pm4py

This process mining project discovers the process model of an event log using the process mining algorithms **Alpha Miner**, **Heuristics Miner** and **Inductive Miner**.  
After discovering the process models, it performs evaluation, finding it's fitness, precision, generalization and simplicity values.  
Lastly it performs conformance checking using the Replay Fitness method. Conformance checking compares the discovered model with the actual event log to identify possible deviations and potential bottlenecks.

*This project was made during my Intelligent Systems course in University.*

## How to run

1. The event log file needs to be in the same directory as the python script file.
2. Execute ```py <filename>.py```.

## Results

Alpha Miner Process model  
![Alpha Miner](C:\Users\Xrhstos\Desktop\process_mining_readme\alpha.png?raw=true)

Heuristics Miner Process model  
![Heuristics Miner](C:\Users\Xrhstos\Desktop\process_mining_readme\heuristics.png?raw=true)

Inductive Miner Process model  
![Inductive Miner](C:\Users\Xrhstos\Desktop\process_mining_readme\inductive.png?raw=true)

Evaluations

(Array)
