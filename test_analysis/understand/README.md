# openunderstand

## Overview
 
The objective of my project is to implement a software to mimic the functionality of Create& Createby queries available in SciTools Understand software analysis toolbox. I have utilized ANTLRv4 and SQLite database to store the outcomes. For further information regarding Understand, database schemas, and terminology, you can refer to this [link](https://m-zakeri.github.io/OpenUnderstand/).

## `What changes did I make?`
- I added new conditions to the Create and Createby file (fix the Create_Createby_g9.py) to be closer to the output of understand using Hierarchy and small test examples  like caclculator_app with checking them through the JavaParserLabeled.g4 file.  

these are my output in Windows and Linux:
- before changes in windows:
![00](https://github.com/zahrahabibolah/OpenUnderstand/blob/dev/test_analysis/00.png?raw=true)

- after changes in windows:
![01](https://github.com/zahrahabibolah/OpenUnderstand/blob/dev/test_analysis/01.png?raw=true)

  
- before changes in linux:
![02](https://github.com/zahrahabibolah/OpenUnderstand/blob/dev/test_analysis/photo_5917882626973221723_x.jpg?raw=true)

-after (linux):
![03](https://github.com/zahrahabibolah/OpenUnderstand/blob/dev/test_analysis/photo_5917882626973221722_x.jpg?raw=true)


## Result

- With these changes, in addition to bringing the numbers openunderstand and understand closer together,also bring them closer in terms of the lines,long name,name,scope etc.
