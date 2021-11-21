# Efficient-loop-unrolling-factor-prediction-algorithm-using-machine-learning-models

Loop unrolling is one of the prominent loop transformation techniques. It is used to increase speed by replicating the loop body and decreasing branches. Loop unrolling is based on the unroll factor that is used to determine the number of instructions written inside the loop. This paper describes the most efficient unroll factor in terms of time to run a loop using machine learning techniques. Using the MinGW compiler, a novel dataset “Loop Unrolling Time Efficiency Dataset” (LUTED) is formed, which records the execution time of loops for varying unroll factors. This paper includes the implementation of numerous loops with a number of iterations up to 28000, resulting in the formation of a dataset consisting of 1550 points. Various supervised machine learning models are executed on the dataset and further, an algorithm “Most Efficient Loop Unrolling Factor Prediction” (MELUFP) is proposed to automate the task in real-time to predict the optimal unroll factor. The Supervised machine learning regression model was able to perform predictions optimally with an accuracy score of 0.9997 on the LUTED dataset.
