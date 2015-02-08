# Memory Stressor

A super-simple program to stress the memory subsystem of your servers (i.e. get your system deep into swap and keep swapping).

### Usage

	make
	./memory-stressor 1234

This will pre-allocate 1234MB and then loop randomly touching chunks of that memory and then sleeping for 1s. Use large enough numbers to get your system heavily into swap, but not so much that you trigger out of memory.

This is a good tool for seeing how the rest of your system behaves when under memory pressure.

Project home: https://github.com/mbenna/memory_stressor

Please feel free to contribute changes! Enjoy!

Mike
