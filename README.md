# logic_simulator
The logic simulator is designed to construct logic circuits using description files provided by the users.
It then simulates the behavior of these circuits based on user input commands or actions performed on a graphical user interface (GUI).
The Logic Simulator supports two modes of interaction: command-line input and GUI interaction. Users have the flexibility to use either the command-line interface by inputting commands or through user actions performed on the GUI interface (the GUI interface also has
Japanese version).
## Start to Use
Install [wxPython](https://wxpython.org/index.html) before launch the application.
### Using Command Window
To initiate the program through the command line interface, input the following command in the command window: <br>
```logsim.py -c <file path>```<br>
<img width="411" alt="image" src="https://github.com/Amanda-Ge/logic_simulator/assets/77627236/947bf4cb-03b9-4550-b061-bfd6a7523f97">
### Using GUI
input the command:<br>
```logsim.py <file path>```<br>
If want to access the Japanese version of GUI, the command to be input will be:<br>
```logsim.py -j <file path>```<br>
<img width="773" alt="image" src="https://github.com/Amanda-Ge/logic_simulator/assets/77627236/6630ba2d-71cf-4aa0-b210-d3a56962d988">

## Description File
To launch the program successfully, the file path provided by the user need to be a valid txt description file.
The full version for the syntax rules can be found in the files.pdf.
