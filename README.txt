This code uses CUDA to un a highly parallel monte carlo simulation on GPU.

To Compile and Run:

1. Navigate to the directory where program.cu is located.
2. Compile the program with gcc using the commands below:

	/usr/local/apps/cuda/cuda-10.1/bin/nvcc -o program program.cu

3. Run the program by executing the command below:

	./p4 [threads] [size] [tries]

	where:
		[threads] = number of threads
		[size] = size of array
		[tries] = number of tries to get best performance
