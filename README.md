# INCREASING_ORDER_BY_LAST_ELEMENT-
tuples = [(2, 5), (1, 2), (4, 4), (2, 3), (2, 1)]
n = len(tuples)
for i in range(n):
    for j in range(0, n-i-1):
        if tuples[j][-1] > tuples[j+1][-1]:
            tuples[j], tuples[j+1] = tuples[j+1], tuples[j] #SWAPPING
print(tuples)
