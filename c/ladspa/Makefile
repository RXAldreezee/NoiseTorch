default: 
	$(CC) -Wall -Werror -O2 -c -fPIC ../ringbuf.c ../rnnoise/*.c module.c 
	$(CC) -shared -Wl,--version-script=export.txt -o rnnoise_ladspa.so *.o
