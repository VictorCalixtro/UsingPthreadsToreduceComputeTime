# UsingPthreadsToreduceComputeTime

To compile and run using linux

gcc -g -Wall -o Collatz collatzConjecturePthreads.cpp -lpthread
./collatz 1234567 16
where the first number must be odd and the second number represents the number of threads
