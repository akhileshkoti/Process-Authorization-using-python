# Process Authorization using Python


## Install

Clone this repository using the following command

> `git clone https://github.com/akhileshkoti/Process-Authorization-using-python.git`

or you can download the zip file [here](https://github.com/akhileshkoti/Process-Authorization-using-python/archive/master.zip).

## Usage

### Input

- Run the input.py file that prompts to enter the names of the processes that you want to restrict.

- **Note:**
  - **Use "q" when you are done with the input.**

### Running the script on startup
- Now create a shortcut to the **startup.bat** file and move that file to the windows startup folder.
- To do that
  - Open Run dialogbox
  - Type shell:startup and press Enter
  - Now paste the startup.bat shorcut in this location
- The next time you boot up the script restricts the blacklisted apps from being accessed.

### Terminating the Script

- If you want to open the blacklisted apps then you have to run the kill code **kill.py**.
- This will terminate the process initiated by **startup.bat**.

This Project is inspired by [Ronin](https://github.com/akhileshkoti/Proccess-Authorization).
