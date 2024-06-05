# Random-Matrix-Coin-Toss-Simulation
<p> This Python script simulates a matrix-based probability experiment. It generates random matrices, classifies elements based on divisibility by 3, and calculates the probability of these classifications over multiple iterations.</p>
<br> 


## What the Code Does

1. Generate a 3x3 matrix of random integers between 1 and 19.
2. Classify each integer in the matrix as either 'h' (head) if divisible by 3, or 't' (tail) if not.
3. Count the number of heads and tails in each matrix.
4. Repeat the above steps for 5 iterations.
5. Calculate the probability of heads and tails for each iteration.
6. Compute the overall probability of heads and tails across all iterations.

## Practical Interpretation

- **Matrix Generation**: Simulates random events (like flipping coins).
- **Classification**: Determines outcomes based on a condition (divisibility by 3).
- **Counting and Probability Calculation**: Helps understand the likelihood of events (heads or tails) over multiple trials.
- **Multiple Iterations**: Ensures that the results are statistically significant by averaging over several trials.

## Requirements

- Python 3.x
- NumPy library
# Code Explanation

The script performs the following steps:

1. **Initial Setup**: Imports the necessary library and initializes the head and tail counters.
2. **Matrix Generation**: Creates a 3x3 matrix of random integers between 1 and 19.
3. **Classification and Counting**: Classifies each element in the matrix as 'h' or 't', counts them, and prints the results.
4. **Probability Calculation**: Calculates and prints the probability of heads and tails for each iteration.
5. **Multiple Iterations**: Repeats the process for 5 iterations to ensure statistical significance.
6. **Overall Probability Calculation**: Computes the overall probability of heads and tails across all iterations.

## Example Output
<pre>
Iteration 1:
Original Matrix:
[[ 8 3 7]
[ 9 12 15]
[18 10 11]]
Toss Result Matrix:
[[1 0 1]
[0 0 0]
[0 1 1]]
Number of heads = 5 and number of tails = 4
Probability of getting head = 0.5555555555555556
Probability of getting tail = 0.4444444444444444

...

Overall Probability of getting H (all events combined) = 0.4888888888888889
Overall Probability of getting T (all events combined) = 0.5111111111111111
</pre>
<b>Contributions are welcome! Please feel free to submit a Pull Request.</b> 

