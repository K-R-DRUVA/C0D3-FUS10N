## the below function is a recursion, the task is to find the missing values i.e. a and b

## use the sample inputs and sample outputs to find the values of a and b

def recursive_product(n):
    if n == 1:
        return __a__  #missing value
    else:
        return n * recursive_product(n - 1) +  __b__ # missing value

## print(recursive_product(3))  Output: 21
## print(recursive_product(4))  Output: 64
## print(recursive_product(5))  Output: 325

## Flag: Fill in the missing values to find the correct flag.

## flag: FLAG-RAID{ab}