Download Link: https://assignmentchef.com/product/solved-solvedfinal-exam-solution
<br>
TCOs 1, 6) _____ provides quick access to programming language definitions within the code editor. (Points : 5)IntellisenseBookmarkBreak pointStep through

Question 2.2. (TCOs 1, 6) What does IDE stand for? (Points : 5)Interior Design EnvironmentIntegrated Development EnvironmentIntegrated Design EnvironmentInterior Development Environment

Question 3.3. (TCOs 1, 6) In the context of object-oriented programming, the Solution Explorer window _____. (Points : 5)exposes the properties of the controlshows the physical components of the programlists the events associated with a controllists the controls on the form

Question 4.4. (TCOs 2, 3) When the correct arithmetic operator precedence rules are applied, what will be the value of the following expression?

5 * 6 / 2 + 1 (Points : 5)1615101231

Question 5.5. (TCOs 2, 3) The keyword “void” means that a method _____. (Points : 5)clears all variables it is passeddoes not return a valueis invalidreleases memory after it is called

Question 6.6. (TCOs 2, 3) Before you start writing a program, it’s important to first thoroughly _____. (Points : 5)analyze the problemdesign the solutionspecify the problemAll of the above

Question 7.7. (TCO 4) What will be the output of this code?

int x = 5, y = 15;if (x y){Console.Write(“A, “);if (3 * x = y)Console.Write(“B, “);elseConsole.Write(“C, “);}elseConsole.Write(“D, “);

(Points : 5)B,B, D,A, B, D,D,

Question 8.8. (TCO 4) Which part of this expression will be evaluated first?

if (b &lt;= c &amp;&amp; d = e)

(Points : 5)b &lt;= cc || dd = eif()

Question 9.9. (TCO 5) In this code, the outer FOR loop executes _____ times.

int i = 1, j = 1;for (i = 1; i &lt; 4; i++){for (j = 1; j &lt; 4; j++){Console.Write(“{0}{1} “, i, j);}}

(Points : 5)threefournine16

Question 10.10. (TCO 5) With a _____ structure, the programmer specifies the number of times the block of code in a loop will repeat. (Points : 5)do-whileforgotowhile

Question 1.1. (TCOs 7, 8) Given the following method call, which would be a valid prototype for the calcLetterGrade method?

char letterGrade;letterGrade = calcLetterGrade(95.5);

(Points : 5)public static int calcLetterGrade(double val);public static char calcLetterGrade(double val);public static double calcLetterGrade(double val);public static char calcLetterGrade(int val);

Question 2.2. (TCOs 7, 8) Which is probably a call to a mutator method? (Points : 5)double yards = yds.calcYards();double yds = GetNoOfYards();CarpetCalculator plush = new CarpetCalculator();SetNoOfYards(double yds);

Question 3.3. (TCOs 7, 8) Because Main() and MyFunction() store counter in _____, the output of this code will be _____.

static void Main(){int counter = 8;Console.Write(“{0} “, counter);counter++;MyFunction(ref counter);counter++;Console.Write(“{0} “, counter);Console.Read();}

public static void MyFunction(ref int counter){Console.Write(“{0} “, counter);counter++;}

(Points : 5)different memory locations, 8 9 10the same memory location, 8 9 10different memory locations, 8 9 11the same memory location, 8 9 11

Question 4.4. (TCOs 9, 10) Type _____ to append “New Year’s Day” to an existing list of holidays in the “listHolidays” ListBox object at run time. (Points : 5)listHolidays.Items.Add(“New Year’s Day”);listHolidays.Items.Append(“New Year’s Day”);listHolidays.Add(“New Year’s Day”);listHolidays.Append(“New Year’s Day”);

Question 5.5. (TCOs 9, 10) Often, multiple _____ objects are placed together on a _____ control. The user can only select one of them. (Points : 5)TextBox, ListBoxRadioButton, GroupBoxListBox, GroupBoxCheckBox, TextBox

Question 6.6. (TCOs 9, 10) Which of the following statements will retrieve the selected item of comboBoxEntrees and place it in a myString variable called “myStr”? (Points : 5)myString myStr = comboBoxEntrees.SelectedItem;myString myStr = comboBoxEntrees.Selection();myString myStr = comboBoxEntrees.Text;myString myStr = comboBoxEntrees.getText();

Question 7.7. (TCOs 11, 12) In the following code, “val” represents the _____.

int[] numTVs = {2,3,5,6,4,5};foreach (int val in numTVs)Console.Write(“{0} “,val);

(Points : 5)array namememory address of an array elementnumber of times the loop will executevalue of an array element

Question 8.8. (TCOs 11, 12) To pass the entire myInfo array to the PrintElements method, replace the commented line below with _____.

static void Main(){int[] myInfo = {6,7,8,9};//call PrintElements}public static void PrintElements(params int[] item){for (int i=0; i&lt;item.Length; i++)Console.Write(“{0} “,item[i]);}

(Points : 5)PrintElements(myInfo);PrintElements(myInfo[0]);PrintElements(ref myInfo);PrintElements(6,7,8,9);

Question 9.9. (TCOs 11, 12) What will be the output of this code?

int[] courses = {2,3,5,6,4,5};Array.Sort(courses);foreach (int val in courses)Console.Write(“{0} “, val);

(Points : 5)2 3 4 5 5 65 4 6 5 3 26 5 5 4 3 22 3 5 6 4 5

Question 10.10. (TCO 13) To print out the time a file called “timeSheet.txt” was created, write _____. (Points : 5)Console.WriteLine(File.GetCreationTime(“timeSheet.txt”));Console.WriteLine(GetFileInfo(“timeSheet.txt”);Console.WriteLine(GetCreationTime(“timeSheet.txt”);Console.WriteLine(File.FileInfo(“timeSheet.txt”);

Question 11.11. (TCO 13) The _____ namespace enables your C# program to work with files and directories. (Points : 5)System.FILE.IOSystem.Collections.GenericSystemSystem.IO

Question 12.12. (TCO 13) To avoid runtime errors when accessing text files, make sure your C# program _____. (Points : 5)encloses file access statements inside try…catch blocksopens a file before writing to ithandles all file IO exceptionsAll of the above

1. (TCO 3) Show the source code for a C# console application called “Area” to display the area of a parking lot with length 203.5 ft. and width 30.5 ft. (Note that area is length times width.)

· Declare and initialize appropriate variables for length and width.

· Include at least three descriptive comments.

· State what your program displays when it runs.

· State how you would use the debugger to check the values of your variables as your program runs.

(Points : 20)

Question 2.2. (TCO 5) Describe two types of loops that can be used to print every third integer from 0 to 300 (i.e., 0, 3, 6, 9, etc.), each on its own line. Which would be a better choice and why? Write the code using that type of loop. (Points : 20)

Question 3.3. (TCO 8) Briefly describe how parameter passing by-value and by-reference are accomplished in memory. Write statement 1 to call method A below. Write statement 2 to call method B. Which method uses pass by-value? Which method uses pass by-reference?

static void Main(){int balance = 20000;//statement 1//statement 2}

//method Apublic static void getBalance(ref int balance){balance = balance + 500;}

//method Bpublic static int getBalance(int balance){return (balance + 500);}

(Points : 20)

Question 4.4. (TCO 9) Identify an example of one of each of the following GUI design errors in Figure 2:

· inconsistency

· misalignment

· clutter

How could each of the three errors be corrected to improve the user experience?

Image Description

(Points : 20)

Question 5.5. (TCO 2) Although the following code compiles and runs, the programmer made some major readability errors. Describe at least three changes that would make it easier for other programmers to read and understand the code.

class Program

{

static void Main() //main

{

int a;

int Double = 10; // ints

for(int i = 0;i &lt; Double;i++) /*loop */{

a=method(i);

Console.WriteLine(a);

}

Console.Read(); //read

}

public static int method(int a) //method

{

return (int)(Math.Pow((double)a,4.0));

}

}

(Points : 20)

Question 6.6. (TCO 11) Write a C# program to store an array of integers 1 through 9. Use an appropriate loop to sum the values in the list. Print out the sum. (Points : 20)