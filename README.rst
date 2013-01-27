======
Conque
======

Conque is a Vim plugin which allows you to run interactive programs, such as
bash on linux or powershell.exe on Windows, inside a Vim buffer. In other words
it is a terminal emulator which uses a Vim buffer to display the program
output.

Usage
=====

Type `:ConqueTerm <command>` to run your command in vim, for example::

    :ConqueTerm bash
    :ConqueTermSplit mysql -h localhost -u joe -p sock_collection
    :ConqueTermTab Powershell.exe
    :ConqueTermVSplit C:\Python27\python.exe


History
=======

This project is a clone of the original Conque plugin by Nico Raffo, located at
http://code.google.com/p/conque/

The project had been abandoned for more than a year, and so I decided to clone
it over to github and see if I couldn't improve it.  If you'd like to
contribute, open an issue (or even better, a pull request!).  Thanks!
