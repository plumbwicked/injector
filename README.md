# plumbwicked LoadLibrary injector

![Screenshot_861](https://user-images.githubusercontent.com/62859332/180056653-dee88e14-f57c-400a-9d1d-a578da33e2cf.png)

A very simple load library injector

You can either use the injector in `Interactive mode` where you can enter the dll name and process name 
or create a batch file to do it for you - 
help is displayed when you run the program with no arguments.

Not too dissimilar from GameOwner - this injector is simple:
 - No gui
 - No manual mapping
 - No process title (making the process title the filename)

If you are building from scratch make sure that:
 - You set the configuration to `Release` mode
 - If you are targeting `x64` change the platform to `x64` or if you are targeting `x86` change the platform to `x86`
 

## Some other notes that I feel make this injector better than GameOwner
 - GameOwner is tried and tested - a good 3 years without being detected however, this injector is open source. Change what you want - re-release this with your own name.
 - The program only waits for a keypress on exit if there is an error and only asks for input if you do not specify a process name and dll name. For me this is one of the problems with Gameowner - it is simply not fast enough
 - Not having to carry around a `.ini` library helps to make this injector less than half the size of GameOwner.
