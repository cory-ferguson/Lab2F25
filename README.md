# Lab2F25
Bubbles and Pointers

This program will be sorting an array of 9 integers
Sorting will be done using a bubble sort

functions used/needed:
a print values function
a sort function
a swap function

Algorithm:

// the algorithm given to us from the assignment
constant MAX is max length of array
function sort (array):
    create integer variables i and j
    for i from zero to MAX - 1:
        for j from zero to MAX - 1:
            if array[j] > array[j+1]:
                swap array[j] with array[j+1]
                printArray(array)


function printValues(int pointer);
    print the current array // printf("%d", arrayName[0]);


function swap(int, int);  // use pointers
    create integer varibles a and b
    print current a and b
    call swap function with addresses to a and b
    print the new a and b



main() // this is an incredibly simplified version of the starter code given to us
    initialize the array
    call printValues()
    
    call swap() 

    call sort()
    call printValues()


