# swtp6800_hello
The hello program from Mike Douglas' (deramp5113) demo of the SWTP6800 microcomputer

YouTube Video here: https://www.youtube.com/watch?v=oZ3eraQ699M

The program that Mike enters in the demo is detailed in a ASM-like way in hello.txt

If you'd like to skip all that work and use SIMH, then try this:

1. Compile the swtp6800mp-a2 simulator and replace the .ini file with the one here
2. Place the hello file (virtual paper tape) and the swtbug.bin in the same location as the simulator
3. start the simulator; you'll see the $ prompt if all goes well
4. Type L to load the paper tape
5. Check if the paper take loaded OK by: M 0000, you should see $0000 CE
6. Type J 0000 to start the program, you should see NAME?
7. Have fun - I did!
