def LargestPrimeFactor(x):
    """
    Finds the largest prime factor of a positive integer x.
    """
    factors = []
    while x > 1:
        t = 2
        while t <= x:
            if not(x % t):
                x /= t
                factors.append(t)
                break
            t += 1
    return max(factors)
            
