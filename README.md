# Matrix Multiplication with Multithreading
This repository contains Python code to perform matrix multiplication using multithreading. The program explores the performance impact of utilizing multiple threads on CPU-bound tasks such as matrix multiplication.

## Overview
Matrix multiplication is a computationally intensive task, particularly for large matrices. By leveraging multithreading, it's possible to distribute the workload across multiple CPU cores, potentially speeding up the computation.

## Features
1. Multithreading: Utilizes Python's threading module to perform matrix multiplication concurrently on multiple threads.
2. Performance Analysis: Measures and compares the execution time for different numbers of threads.
3. Visualization: Includes a graphical representation of execution time versus the number of threads using matplotlib.

## Outputs
The program will output the execution time for different numbers of threads, demonstrating the impact of multithreading on performance. 

<img src="https://github.com/aarushijain-24/Multi-Threading/assets/144267641/aa6e779b-5826-4dca-9de5-41e09f5cae57" width="500"/>
</br>
</br>
Additionally, a graphical representation of execution time versus the number of threads will be displayed.
</br>
</br>
<img src="https://github.com/aarushijain-24/Multi-Threading/assets/144267641/de70f937-a188-4f31-876a-04164ac87b89" width="750"/>
</br>
</br>
The CPU usage illustrates the system's resource utilization during the execution of the program, providing insights into the efficiency of multithreading and the distribution of computational workload across CPU cores.

</br>
</br>
<img src="https://github.com/aarushijain-24/Multi-Threading/blob/main/CPU_usage.png" width="600"/>

## Result
With four CPU cores available, the execution time decreased as the number of threads increased up to four. However, as we continued to increase the number of threads beyond the available cores, from five to eight, the execution time also increased slightly. This suggests that while utilizing up to the number of available CPU cores can significantly improve performance, exceeding that number can lead to diminishing returns and even slight performance degradation due to increased overhead.
