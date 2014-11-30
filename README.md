R-Facebook-friends-birthdays
============================

A project analyzing Facebook friends' birthdays, using R programming language.

Plot images:
https://cloud.githubusercontent.com/assets/7876482/5239592/bcc9c26a-78ac-11e4-87ff-ac697c55bd1f.jpeg
https://cloud.githubusercontent.com/assets/7876482/5239594/c6279a12-78ac-11e4-8de4-2323e72054ff.jpeg

Sample summary statistics:

summary(birthday$day)
Min. 1st Qu. Median Mean  3rd Qu. Max. 
1.00 8.00    15.00  15.29 23.00  31.00

summary(birthday$month)
Min. 1st Qu. Median Mean 3rd Qu. Max. 
1.0  3.0     6.0    5.7   8.0    12.0

table(birthday$month)

month 1  2  3  4  5  6  7  8  9 10 11 12  
count 33 26 34 34 25 28 33 30 34 1 1  28
