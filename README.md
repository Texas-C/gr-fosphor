# gr-fosphor

## 1. How to use:
To use the fosphor blocks in Python, import it as :

    from gnuradio import fosphor

See the Doxygen documentation for details about the blocks available
in this package. A quick listing of the details can be found in Python
after importing by using:

    help(fosphor)

## 2. Build & Install:
### 2.1 Dependencies:

	g++ cmake boost

opencl:

	ocl-icd beignet(opencl for intel) nvidia-opencl-dev(for nvidia)

glfw: glfw3
	

### 2.2 Compile & install:

	mkdir build
	cmake .. -DCMAKE_INSTALL_PREFIX=/usr		# set install path to /usr
	make -j${proc}
	sudo make install
	sudo ldconfig	# ubuntu only
