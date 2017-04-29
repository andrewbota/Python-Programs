# This program carries commands from an LXTerminal.

print('''Commands:
hostname(type): Type can be 'ip' or 'name'.

mkdir(folder): Makes folder in current directory.

chdir(loc): Changes the current directory.

rmtree(folder): Deletes a folder and its contents.

rmdir(folder): Removes and empty folder.

all(): Prints any useful information including:
Your Hostname
IP Address
Current User (More Complicated)
Python Version
Current Directory
''')

import socket
import subprocess
import sys
import os
import shutil
import psutil
import time
import random


main_dir = '/home/andrew/'
ANDREW_USB = '/media/andrew/ANDREW USB/'

def hostname(type):
    if type == 'ip':
        print(socket.gethostbyname(socket.gethostname()))
    if type == 'name':
        print(socket.gethostname())


def mkdir(folder):
    os.mkdir(folder)


def chdir(loc):
    os.chdir(loc)


def rmtree(folder):
    shutil.rmtree(folder)


def rmdir(folder):
    os.rmdir(folder)
    


def all():
    print('Hostname: ' + socket.gethostname())
    print()
    print('Logged In User: ' + str(psutil.get_users()))
    print()
    print('IP Address: ' + socket.gethostbyname(socket.gethostbyname(socket.gethostname()))
    print()
    print('Python Version: ' + sys.version())
    print()
    print('Current Directory: ' + os.getcwd())
    



