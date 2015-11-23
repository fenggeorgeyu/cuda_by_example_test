nc=nvcc 
# edvice emulation is obsoleted
# use gpuoclet? instead
#flag=-deviceemu

all:


hello: hello_world.cu
	${nc} $(flag) hello_world.cu -o hello_world.o

simple_kernel: simple_kernel.cu
	$(nc) $(flag) simple_kernel.cu -o simple_kernel.o

enum_gpu: enum_gpu.cu
	$(nc) $(flag) enum_gpu.cu -o $@.o