nc=nvcc -deviceemu
flag=-deviceemu

all:


hello: hello_world.cu
	${nc} hello_world.cu -o hello_world.o

simple_kernel: simple_kernel.cu
	$(nc) simple_kernel.cu -o simple_kernel.o

enum_gpu: enum_gpu.cu
	$(nc) enum_gpu.cu -o $@.o