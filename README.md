# Tugas 1  Sistem Pakar Semester 6 DIV Teknik Informatika 3A

Lecturer/Dosen :  M Nurkamal Fauzan, S.T., M.T.

Name/Nama : * **Rizaluardi Achmad Pratama** - *1184102* - [rizaluardi](https://github.com/rizaluardi)

Npm : 1184102


## Halal-Bot Is Smarter Than You!

Authors: Matthew Kearns and Ahmed Youssef.- [mdkearns](https://github.com/mdkearns/expert-system-shell)

## Indonesia Explanation:

Berikut merupakan sistem pakar sederhana yang mempelajari informasi untuk menjawab
pertanyaan seputar yang ditanyakan dalam console. dengan menggunakan forward chaining
untuk mempelajari role/rules yang diberikan dan variabel yang disediakan oleh pengguna
(baik sistem root atau sistem learned), dan digunakan backward chaining untuk membuat
penjelasan terkait inputan yang diberikan ke values dari variabel dalam sistem dan rules.

perbedaan dari variabel root dan variabel learned adalah:

variabel root adalah variabel yang nilai kebenarannya diketahui oleh
user, dan user dapat men-set value menjadi benar atau salah
value yang benar merupakan variabel dari learned, bagaimanapun, tergantung pada aturan
sistem dan nilai variabel root yang bergatung padanya

## Petunjuk penggunaan:
```
1. Teach [-R/-L] Var = String
Mengajari sistem untuk menulis dan membuat value dari variabel

2. Teach Var = [True/False]
Mengajari sistem kebenaran value dalam variabel

3. Teach Expression -> Var
Mengajari sistem untuk membuat rule baru

4. List
Melihat list dari value dari semua variabel root dan learned
Serta membuat list dari current rules dan learned rules di dalam sistem

5. Learn
Membuat rules baru berdasarkan aturan yang sudah disediakan dalam sistem
dan memperbarui values dari kebenaran variabel berdasarkan rules

6. Query Expression
Kueri yang mengembalikan nilai kebenaran values dari ekspresi berdasarkan semua
aturan dan variabel saat ini dalam sistem

7. Why Expression
Memberikan penjelasan mengapa ekspresi yang disediakan user itu true atau false
mengingat rule saat ini dan nilai variabel yang dipegang oleh sistem

Kunci:
-R = variable root
-L = variable learned
Var = user-defined variable name
String = A string of the form "Today is Monday" or "Matt likes ice cream"
Expression = Any valid expression of the form A&B->C or (!((A|B))&C)->D
```


## English Explanation

Brief Explanation:

This is a simple expert system that learns information to answer questions
about its behavior. It uses forward-chaining to learn new rules given 
user-supplied rules and variables (either root or learned), and it uses 
backward-chaining to create explanations for its behavior given the values 
of the variables in the system and the learned rules.

The difference between a root variable and a learned variable:

A root variable is a variable whose truth value is known by the
user, and the user can set its value to either true or false. The
truth value of a learned variable, however, depends on the rules of
the system and the values of the root variables that it depends on.


Usage Instructions:

	1. Teach [-R/-L] Var = String
	
		Teaches the system the type and value of a variable.
		
	2. Teach Var = [True/False]
	
		Teaches the system the truth value of the variable.
		
	3. Teach Expression -> Var
	
		Teaches the system a new rule.
		
	4. List
	
		Lists the values of all root and learned variables, and
		lists all of the current rules and learned rules in the
		system.
		
	5. Learn
	
		Creates new rules based on rules already supplied in the system
		and updates the truth values of the variables based on the rules.
		
	6. Query Expression
	
		Query returns the truth value of the expression based on all of 
		the current rules and variables in the system.
		
	7. Why Expression
	
		Why gives an explanation of why the user-supplied expression is true
		or false given the current rules and variable values held by the
		system.
		
	Key:
	
	-R = root variable
	-L = learned variable
	Var = user-defined variable name
	String = A string of the form "Today is Monday" or "Matt likes ice cream"
	Expression = Any valid expression of the form A&B->C or (!((A|B))&C)->D

