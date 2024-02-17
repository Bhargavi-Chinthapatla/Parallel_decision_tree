# Scalable Implementation of Distributed Decision Tree

## Overview
This document presents a study on the implementation of a distributed decision tree algorithm, specifically focusing on the C4.5 algorithm, enhanced for parallel processing. The research aims to address challenges related to handling high-dimensional data and the curse of dimensionality by leveraging parallelism to improve scalability and performance.

## Methodology
The methodology section details the approach taken to implement the C4.5 decision tree algorithm using multiprocessing. It discusses the preprocessing steps, decision tree construction, and the parallelization technique employed to distribute the workload across multiple processors effectively.



<img width="301" alt="Screenshot 2024-02-17 at 2 15 23 AM" src="https://github.com/Bhargavi-Chinthapatla/stock_prediction/assets/149857162/cfb9d5cf-d60f-4d60-8de7-347f94c68f5f">

<img width="504" alt="Screenshot 2024-02-17 at 2 15 58 AM" src="https://github.com/Bhargavi-Chinthapatla/stock_prediction/assets/149857162/92c71273-5da1-448e-a290-9557de666b31">


## Key Findings

### Performance Improvement: 
The implementation demonstrates significant performance improvements in both model training and prediction phases when utilizing parallel processing compared to serial execution.
### Scalability: 
The study shows that the parallelized version of the C4.5 decision tree algorithm scales effectively with the increase in data size without compromising on accuracy or performance.
### Trade-offs: 
While parallel processing introduces some overhead, particularly in communication among processors, the overall benefits in terms of reduced execution time and maintained accuracy are highlighted.
<img width="504" alt="Screenshot 2024-02-17 at 2 16 13 AM" src="https://github.com/Bhargavi-Chinthapatla/stock_prediction/assets/149857162/3d403aee-bdf1-4b67-8582-fc68ee8968a8">

<img width="474" alt="Screenshot 2024-02-17 at 2 16 32 AM" src="https://github.com/Bhargavi-Chinthapatla/stock_prediction/assets/149857162/cdb266d5-1070-487b-ad9c-501eef2d89a4">

## Conclusion
The scalable implementation of the distributed decision tree using the C4.5 algorithm showcases the potential of parallel processing in overcoming the limitations posed by high-dimensional data in decision tree algorithms. Future work may explore further optimization techniques and the application of this approach to other machine learning algorithms.

Images
Architecture Diagram: Illustrates the distributed processing model used for the C4.5 decision tree algorithm.
Performance Comparison: Graphs showing the comparison of execution time and accuracy between serial and parallel implementations.
Parallel Processing Approach: A diagram explaining how tasks are distributed and managed across multiple processors.
For detailed methodologies, experimental results, and further discussions, refer to the full document.
