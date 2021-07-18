# Home_Assignment_Nikolai

Workspase - Windows 10
Project location: C:\Home_Assignment
---------
Added files:
    1. terminal.py
    2. terminal_functions.py
    3. configfiles
        - testdata.ini (thershold=7)
        - testdata.py
    4. requirements.txt
    5. read.txt
----------
All tests were done on internal "Home_Assignment" folders:
    1. mixed
    2. mixed1

The files under test form folder were  "csv, mat, dxl" format
----------

How to run:
python C:\Home_Assignment\terminal.py
------------
Menu:
1) Sort command (directory_name)
    # Automaticly print and generate mixed.log.txt or mixed1.log.txt with file name and hash table.
    # Correct input: 1 mixed; 1 mixed1;    Incorrect input: 1; 1 miy; 1uuuu; 1 yt oo rr
2) Clean command (file_name, window_size)
    # Print status and keep window of lines in mixed.log.txt or mixed1.log.txt and if window bigger
      than threshold so keep threshold size.
    # Correct input: 2 mixed 6; 2 mixed1 8;    Incorrect input: 2; 2 miy 8; 2uuuu; 2 yt oo rr
3) Stat command (file_name)
    # Automaticcaly updating, sorting and print status of Sort and Clean commands.
    # Correct input: 3 mixed; 3 mixed1;      Incorrect input: 3; 3 nn jjj
4) Script command (Not implemented yet)
5) Exit
    # Close program



