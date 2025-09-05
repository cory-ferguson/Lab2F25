# Lab2F25
Bubbles and Pointers

This program will be sorting an array of 9 integers
Sorting will be done using a bubble sort

functions used/needed:
a print values function
a sort function
a swap function

Algorithm:

void sort(int* )
void swap(int* , int* )
void printValues(int* )

int main() // this is an incredibly simplified version of the main we were given 
    initialize array
    call printValues()
    
    call swap()

    call sort()
    call printValues()

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
    print start bracket
    use a for loop (i = 0, i < MAX, i++)
        print the values of i
    print end bracket


function swap(int, int);  // use pointers
    create integer varibles a and b
    create a temp variable
    set temp to the value of a
    set a to the value of b
    set b to the value of a


