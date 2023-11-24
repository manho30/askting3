# Usage
## Install Git on Windows
1. Navigate to the latest [Git for Windows installer](https://gitforwindows.org/) and download the latest version.
2. Once the installer has started, follow the instructions as provided in the Git Setup wizard screen until the installation is complete.
3. Open the windows command prompt (windows key + R, type cmd, press enter).
4. Type git version to verify Git was installed.


## Clone the repository
1. Open the windows command prompt (windows key + R, type cmd, press enter).
2. Navigate to the directory where you want to clone the repository.
3. Enter the following command to clone the repository:
``` bash
git clone https://github.com/manho30/askting3/tree/v2
```
4. Navigate to the directory where you cloned the repository.
5. Enter the following command to install the required packages:
``` bash
cd askting3
```
6. Initialize the project:
``` bash
python init.py
```
7. Run the project:
``` bash
python cli.py
```
8. Follow the instructions in the command prompt to use the application.