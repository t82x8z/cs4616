java c
Computing for Engineers – Assessed Lab 1 (2 hours) 
11-12 November 2024 (Week 7 Semester 1)
This is an assessed lab exercise. 
Statement of good academic conduct 
By submitting this assignment, I understand that I am agreeing to the following statement of good academic conduct. 
I confirm that this assignment is my own work and I have not worked with others in answering the exercises in this assignment. 
I confirm that I have not asked, or paid, others to undertake any part of this work for me. I confirm that I have read and understood the University regulations on plagiarism 
https://intranet.birmingham.ac.uk/as/registry/policy/conduct/plagiarism/index.aspx. 
I understand that if concerns are raised about my work I may need to participate in a viva (oral examination) of my work. I also understand that my progress and/or graduation maybe delayed whilst these concerns are investigated under the Code of Practice on Academic Integrity or Code of Practice on Plagiarism. 
Your C Source code for Exercise A and Exercise B must be uploaded to Canvas by 
Tuesday 12 November, 24:00 (midnight, end of Tuesday) UK Time
Your code must be uploaded as a .c file (C Source file).
In most cases you will need to upload the two files called “main.c” (one for each exercise).
Do not upload .docx files, .pdf or any other format.
Do not email the code to the course lecturer or to any other member of staff or PGTA.
Only Canvas submissions will be marked.
If you have any problems uploading your code, consult the Module Lecturer well before the above deadline. Once the deadline has expired, your mark for the Assessment will be deducted 5 marks per day or part of a day.
The Module Lecturer cannot extend any deadlines for this assignment for any reason. If you wish to be considered for an extension, you will need to apply for Extenuating Circumstances via Engineering Welfare.
Do not discuss the exercise with any other person, inside or outside the University. Do not get help from any other person. The submitted assessment must be your own work.
You may only use Canvas, your own notes and your own programs as sources of help.
You should only use techniques which have been discussed during Lectures, Labs or Tutorials.
Acceptable sources of help:
• Your own notes
• The Study Guide on Canvas for this module
• The Lecture / Lab and Tutorial videos for this module on Canvas / Panopto
• Any programs which you have written yourself during the labs this Semester
• You may use published Books, as long as you provide a full reference (Name and Author of Book, Publisher Name, Year of Publication).
Sources which are not acceptable:
• Help from any other person, inside or outside the University
• Any website, forum, social media, video, audio, email or messaging, or any other information source, other than the Canvas page for this module
• Self-published books and course notes from ot代 写Computing for Engineers – Assessed Lab 1R
代做程序编程语言her Universities or online courses
Exercise A: 
A small delivery company requires a programme to track the distance, fuel usage and fuel efficiency of its fleet of 3 vehicles. They need to be able to enter distances travelled, whether the trips are on open road or in town driving and the fuel used in the trip in litres. As an output they need a table listing each vehicle, it’s total distance driving in town, it’s total distance on the open road, the total combined distance and then the fuel efficiency of each in miles per gallon (mpg). 
You are given the following: 1 UK gallon = 4.54609 L
You can calculate fuel efficiency using the equation: fuel efficiency = distance in miles / fuel used in gallons.
You may not use an array to store the data. You do not need to produce a list of all the trips, only the summary for each vehicle.
The programme should continue collecting information until a vehicle number of -1 is entered. Data should only be collected for vehicles numbered 1, 2 or 3.
Your output should produce a summary table that looks like this: (assuming 9 trip ’s were entered).

Hint: use the following variable declarations: 
float vehicle 1 distance_town=0.0, vehicle 1 distance_openroad=0.0; //distance info for vehicle 1 float vehicle 1 fuel_town=0.0, vehicle 1 fuel_openroad=0.0; //stores the fuel used for vehicle 1 float vehicle 2 distance_town=0.0, vehicle 2 distance_openroad=0.0; //distance info for vehicle 2 float vehicle 2 fuel_town=0.0, vehicle 2 fuel_openroad=0.0; //stores the fuel used for vehicle 1 float vehicle 3 distance_town=0.0, vehicle 3 distance_openroad=0.0; //distance info for vehicle 3 float vehicle 3 fuel_town=0.0, vehicle 3 fuel_openroad=0.0; //stores the fuel used for vehicle 3 int INP_vehicle=0; //gets the vehicle number being input 
int INP_distance=0.0,INP_fuel=0,INP_triptype=0.0; //Gets input data for the current trip 
Exercise B: 
Create a C console programme that will allow users to generate mathematical quizzes testing multiplication and division. Each quiz run shall:
-     have between 2 and 10 questions (in increments of 2)
-     be based on a selection of a times table entered by the user (between the 1 and 12 times table)
-    test both multiplication and division (decided randomly for each question)
-     use random selections of numbers and ensure that any division question will work.
The programme must not use arrays and must not use functions and should provide helpful responses to the answers entered.
Once the questions for the particular times table are completed, the user should be asked if they want to do another times table.
The programme shall score the total accuracy of the responses at the end.
Hint: ensure to use #inlcude and to have the code: srand(time(NULL)); 
at the start of the “main.c ” . 
Hint: the programme will only need to use integer data types for all numbers. 

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
