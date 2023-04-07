# Ultimate Werewolf Dashboard
A dashboard for games of ULTIMATE WEREWOLF

## Installation
### Option 1 - Downloading software directly from [here](INSERT EXE/MSI HERE)
This one click installer will install the program to your system with Electron.
This is the quickest and easiest option.

### Option 2 - Downloading [html/css/js zip file](INSERT ZIP HERE) and running from browser
This option will not install any program to your system, rather you will be running a regular html file directly from your browser. This also means you have to run the file each time instead of opening an application.
This is a safe option while still having an easy installation.
#### Step 1
Downloading and unpacking the built ZIP file [here](INSERT ZIP HERE).
#### Step 2
Double clicking on the HTML file in the top directory of the folder and, if prompted, choosing your browser of choice.

### Option 3 - Building the program yourself
This option requires previous technical knowledge of node, the command line and preferrably electron.
Required programs to begin are Node.js, a text editor and preferrably [Terminal](https://apps.microsoft.com/store/detail/windows-terminal/9N0DX20HK701) (Not essential) as your command line if you are on windows for a clean experience.
This is the safest option but takes the most time.
This is the 
#### Step 1
Downloading and unpacking the unbuilt ZIP file [here](INSERT ZIP HERE).
#### Step 2
Opening your command line (command prompt on windows, terminal on mac and terminal if you are using terminal on windows) and opening the folder inside of it by running `cd [INSERT PATH HERE]` replacing the `[INSERT PATH HERE]` with the path to your folder. After that, test you have node installed by running `node -v`, this should output a version number to show it is working.
#### Step 3
Install all required packages to the project by running `npm install`
#### Step 4
Run `npm run build` to build the project into a single "build" folder that a web browser can understand. You can stop here if all you need is a browser readable folder, this does not install any programs onto the system. If you would like a program instead I recommend Electron that is what the EXE/MSI is built with. There are plenty of tutorials on the internet just search `build electron app`. One that I would like to point out is the official tutorial from [Electron](https://www.electronjs.org/docs/latest/tutorial/tutorial-prerequisites). Just make sure that instead of the `index.html` file you move the "build" folder into the project and reference the html file inside the folder with `build/index.html`. If your have any problems, either email me if you know me in person or create an issue thread in this repository.

## Questions? Problems? Suggestions? Let me know!
If you have any questions, problems or suggestions, let me know by creating a thread in the issues tab and add a label for the type! Or, if you know me in person, email me, you know my email address!
