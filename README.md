# p3s

Presentation System Scheduling System

Abstract:

For UIC CST teachers to mark the time table for the final year project(FYP) presentation.

For UIC CST students to select time table and choose examiner for their FYP presentation.

Roles and Functions:

1.	Coordinator *

	Give the starting date and ending date of presentation 

	Manage teachers’ name list 

	Import students’ name list 

	Set up and reset initial passwords 

	Set up quota for each teacher 

	Set up minimum time slots for teachers to mark 

	Import FYP list 

	Export timetable for the whole class

	Edit final time table to add classroom

	Mark time that students are not available

	Clear old information except teachers login information

2.	Teacher

	Mark and update timetable

	View and Print out timetable and classroom for self

	Reset password

3.	Student 

	Choose time and examiner

	Mark timetable //not urgent

	Report when there is no matching found //not urgent

	View final time and classroom

	select examiner 




=====================
Using virtualenv

>> mkdir P3S
>> virtualenv --distribute P3S
>> cd P3S
>> source bin/activate

>> deactivate  #离开

=====================
Local project add to Github

git init //在当前项目目录中生成本地git管理,并建立一个隐藏.git目录
git add . //添加当前目录中的所有文件到索引
git commit -m "first commit" //提交到本地源码库，并附加提交注释
git remote add origin https://github.com/chape/test.git //添加到远程项目，别名为origin
git push -u origin master //把本地源码库push到github 别名为origin的远程项目中，确认提交

====================
Require Module

pip install flask
pip install MySQL-python















