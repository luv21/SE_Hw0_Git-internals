# HW0-510
SE (510) Homework 0 repository
# CSC 510 Software Engineering - HW-0

 
## Task 1 – Setting up the course modules

### 1.1 – Profile Creation (Moodle, Mattermost and StackOverflow)

![](/Images/p1.png)

![](/Images/p2.png)

![](/Images/p3.png)

### 1.2 – Github

Profile has been created on Github

### 1.3 – Stackoverflow 

Questions have been asked on Stack Overflow
ANswers haev been given over stackoverflow
![](/Images/p3.png)

## Task 2 – Engineering Basics Workshop

### 2.1 – Shells Exercise

##### Count the number of columns inside the "users.*.csv" file. [data-ans1.txt]


`head -1 users--2016-04-01_14-36-26-UTC.csv | tr ';' ' ' | wc -w >data-ans1.txt`

##### Count the number of times "bitcoin" is referenced inside a the post's file "tagline" column. [data-ans2.txt]


`cut -f 4 -d ';' posts*.csv | grep -o 'bitcoin' | wc -l>data-ans2.txt`


##### Find the row of post with the highest number of upvotes. [data-ans3.txt]


`sort -k7 -t ";" -n posts--2016-04-01_14-36-24-UTC.csv|tail -1>data-ans3.txt`

### 2.2 – Github Tasks
Local and remote repository has been created

Issue has been created

TA and Professor have been added as the collaborators

![](/Images/git_profile.png)
![](/Images/git_issue.png)
![](/Images/git_coll.png)

### 2.3 - Github Exercises

All the five levels of Github Exercises have been finished

![](/Images/git_ex.png)


### 2.3 - Opunit System Tests

All the tests in the opunit.yaml file passed

![](/Images/opunit1.png)

opunit verify local 

![](/Images/opunit2.png)






