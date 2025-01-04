def fibonacci_series(n):
    """
    Generate a Fibonacci series up to the nth term.

    :param n: Number of terms in the Fibonacci series
    :return: List containing the Fibonacci series
    """
    if n <= 0:
        return []
    elif n == 1:
        return [0]
    elif n == 2:
        return [0, 1]
    
    # Initialize the first two terms
    series = [0, 1]
    
    # Generate the series
    for i in range(2, n):
        next_term = series[-1] + series[-2]
        series.append(next_term)
    
    return series

# Example usage
num_terms = int(input("Enter the number of terms: "))
print(f"Fibonacci series up to {num_terms} terms: {fibonacci_series(num_terms)}")
