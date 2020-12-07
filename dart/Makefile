


osx-install:
	brew install llvm

ffi-setup:
	pub run ffigen:setup \
		-I/usr/local/opt/llvm/include \
		-L/usr/local/opt/llvm/lib

ffi-gen:
	pub run ffigen
