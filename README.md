# Pyramid
This program generates a pyramid in the form of small 1's. This isn't really a practical program, it's just fun.
![](https://github.com/crjase/Pyramid/blob/main/Screenshots/Far.jpg)
![](https://github.com/crjase/Pyramid/blob/main/Screenshots/Close.jpg)

# Usage
To run the program, you now have to specify an "amount" or limit. This limit is the limit for loop iterations. I recommend 10,000 if you usually have 1GB of ram free, but if you don't, then use 1,000. It will run slower with 1,000, as it has to save to the file every 1,000 loops.

I recommend you use a run file for quick access. Create a run.bat file and paste this code code into it.
`Pyramid.exe <limit>` or if you're using dotnet `dotnet run <limit>`
**Where it says <limit>, replace that with the <limit> you'd like**.

## Important
If you're making a ``run.bat`` file, make sure you put it in the same directory as the executable.
