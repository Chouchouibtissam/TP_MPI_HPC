# TP_MPI_HPC
compile:

mpicc test.c -o test

execute: #p :number of process

mpirun -np <#p> ./test
