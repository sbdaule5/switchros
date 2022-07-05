# switchros
## 1. Installation
Copy the file switchros into your `.local` folder (`~/.local`) or any other place where you store your local scripts, and add this folder to your path by adding following lines to your `.bashrc` file: <br><br>
`export PATH=~/.local:$PATH` <br>
`. switchros`
<br><br>
Also do not forget to remove/comment any source commands you have added your `.bashrc` file
## 2. Usage 

To switch ROS version, enter the following command in terminal: <br>
`switchros <version>` <br>
Where version is the version of ros you want to use.

---
### Additional Notes
- By default it will use noetic for ros 1 and galectic for ros 2. This can be changed by editing script file.
- If you want to execute any other command other than sourcing your ros installation, you can add it in the section present in shell script.
- This script will also create a hidden file in your `home` directory with name `.rosversion`.
---
### TODOs
- Add a more convinient way to change default ros version.
- Seperate user defined commands from the main script file.
