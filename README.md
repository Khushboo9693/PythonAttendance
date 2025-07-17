# Seating Arrangement For Exam

Task 1 : Design a Python code for seating arrangement for exam
Task 2:  Design a class wise attendance sheet based on the above. You know that attendance sheet in the exam contains your roll, name, sign in excel format. At the bottom there should be 5 rows and two cols for signatures of invigilator and tas. Just make 5 rows 2 cols blank in the attendance file. The file should be renamed like: [use in_4 for roll name mapping]

dd_mm_yyyy_sub_code_room_num_(morning/evening).xlsx

Points to be taken care are in first sheet 

Rest is self explanatory 

Assume input to be of csv formatted with ; as separator

ip_1, ip_2, ip_3, ip_4 are input. 

ip_1 tell the roll, sem num, and the course in which students are registering. Ignore schedule_sem 
ip_2 is exam tt 
ip_3 is room capacity. This can be added over time, so keep the code dynamic 
Ip_4 is roll-studname mapping. Will be useful for task 2

op_1, op_2 are self explanatory. output should be csv (; separated) as well as excel file
You are free to use any library and take any help.


Points to be taken care.
1	Fill large courses first
2	Block 9 first; then goto LT
3	Dont try to split exam in both block 9 and LT
4	keep buffer of 5 students per classroom. make it as variable. if I enter 0 then no buffer
5	Two options. 1) Dense. So if capacity of class is 30; then all 30 can be of one course. 
	2) Sparse: If capacity is 30; max 15 (half) can be of one course. This again in a variable or user input
6   Keep in mind that you should reduce number of classroom required.. Also try to optimize locality of room. One exam in 101 and other in 401 should be avoided initially, but if nothing suffices you may allocate


Important: 
Assume input to be of csv formatted with ; as separator
