
## Taylor Cruz ePortfolio

### Self-Assessment
Throughout the Computer Science program at Southern New Hampshire University, I have gained new skills. While taking Software Development Lifecycle as well as Collaboration and Team Project, I learned the importance of working as a team. I discovered the importance of using Scrum to work together as a team. Scrum allows the team to complete a task within a certain time frame before moving on to the next phase. It also ensures that the team is on the same page by all team members being able to see which tasks are completed, which tasks are currently being worked on, and which tasks still need to be worked on. I also discovered how important communication is with the client or stakeholders, specifically through the UI/UX Design and Development course. Discussing the client’s needs for a product prior to the coding phase is crucial in ensuring that the company is releasing the best product. Prior to development, an interview with the client should be performed to gather the requirements for the product. A list of requirements will then be made in order to decide how the product will function. Once a plan is written up for how the product will function, it is important to then meet with the client or potential customers again to show them how the product will work and gather feedback. This feedback will be used to create a paper prototype of the product which will be shown to the client/customer again to gather more feedback. Once the requirements are met and the client is happy, the team is able to move on to the development phase. While learning about data structures and algorithms I created algorithms to sort bids in the Data Structures class that I took. Two algorithms that stuck out the most to me were the selection sort algorithms and the quicksort algorithms. My creation of the selection sort algorithm displays my knowledge of how to create this type of algorithm to sort a value from lowest to highest. My creation of the quicksort algorithm displays my knowledge of how to create an algorithm that is more in depth. The quicksort algorithm required code for a partition method as well to show the value from the beginning to the middle point and then from the middle point to the end. Throughout my time at SNHU, many of my classes utilized software design and engineering as a majority of the core computer science courses required creating functional code. I learned how to meet the requirements of a project to ensure that the program functions properly, how to define variables, how to define functions, how to call them back, how to utilize while loops and if-else statements, as well as gaining overall knowledge in specific programming languages such as C++ and Java. My first enhancement of the clock project showcases my ability to implement those skills and is included in my ePortfolio. I have had the opportunity to work with databases by utilizing SQL as well as MongoDB. I enjoyed working with MongoDB more and have included an enhancement where I utilize a Python module that I created and MongoDB to display an Animal Shelters information onto a webpage from their database in my ePortfolio. In the class where I learned about MongoDB I also learned a little about security and how to authorize a user to make changes to a database. Security is crucial in the computer science field. It is important to keep private information safe from hackers or any other outside sources. It is also important to create specific users with passwords that are allowed access to certain aspects of a software. 
Overall, each of the included enhancements show my full range of computer science abilities. The skills that I have showcased in each of my artifacts have made me a well-rounded candidate. I have developed many different skills while obtaining my degree and am excited to continue to learn more as technology evolves and in my future career.

### [Code Review](https://1drv.ms/u/s!Ap-5SRWG6rXqgSqTCjm9N54S49Ot?e=uDeG8m)
Prior to starting the enhancements for the different artifacts, I conducted an in-depth code review. The code review describes each of the artifacts and looks for mistakes and areas that need improvement.

### [Software Design and Engineering](https://github.com/taylorcruz/taylorcruz.github.io/tree/main/Clock.vcxproj)

The artifact that I chose to enhance for the software design and engineering category is a program that displays two clocks: a standard 12 hour clock and a clock showing military time. The user can make enhancements to the clock based on inputting a number one through four. This was created March 21st, 2021 for the CS 210 Programming Languages course. I chose this item to showcase my knowledge in software design and engineering because it shows my capabilities to create a functional software that meets the requirements of the project. This program also shows my ability to define functions, to call them back, while loops, if-else statements, and my overall knowledge of the C++ programming language. So far, I have improved the artifact by defining the variable “input” in the userInput function rather than in the main. I have also modified the variables “addHour”, “addMinute”, “addSecond”, and “exit” in the if-else statements to “input” as the statements will be checking the value of the user’s input to modify the clocks. I also removed the cin statement from the main along with the other variables that were defined and am only calling the functions in main. 

### [Algorithms and Data Structure](https://github.com/taylorcruz/taylorcruz.github.io/tree/main/VectorSorting)

The artifact that I chose for the Algorithms and Data Structure category is the vector sorting project from the CS 260 Data Structures class that I submitted on May 27, 2021. The purpose of this program is to implement the selection sort algorithm and the quicksort algorithm while also invoking both methods with the timing results. The bid title is used to sort the bids in order from lowest to highest with the selection sort algorithm. The quicksort algorithm utilizes the bid title to sort the bids by finding a pivot point and middle value. This algorithm is more in depth to code because I also needed to code for the partition method. The code is split up into sections to show the bids from beginning to middle point and then from middle point to the end. I chose this artifact for this category because it is a good representation of how the selection sort algorithm and quicksort algorithm are created and implemented. I successfully coded the selection sort algorithm which utilized the vector “Bids”. I used a for loop to ensure that the algorithm was taking the value and checking it against the position of the value to ensure this was being sorted from lowest to highest. I also successfully coded a partition method that finds the pivot point and then utilizes a while loop to increment low if it is less than the pivot or decrement high as long as its less than the pivot. There was also an if-else statement that would check if the low value was greater than or equal to the high value, if it was than the loop is done, else the low and high bids would be swapped using the built-in vector method. I then created the quicksort algorithm which would check if the begin value was greater or equal to the end value. The partition method is also called to partition bids into low and high part, the quicksort is called using the midpoint value to go from beginning to midpoint, and the quicksort method is called again using the midpoint value to go from midpoint + 1 to the end. This artifact showcases my skills in developing a quicksort method, partition method, and selection sort method. For the enhancements of this artifact my goal was to get the selection sort bids and quicksort bids to display if the user chose option three or four from the menu. I did this by using cases. In case three I invoked the selection sort method and report timing results. I used a for loop to display all the selection sort bids in the correct order, from lowest to highest. I then enhanced case four to invoke the quick sort method and report timing results by also adding a for loop that displays all the quicksort bids in the correct order. Based on the CS 260 textbook I believe that these enhancements should work to properly display the algorithms. While looking over the code, I was not sure where to begin, but once I utilized the textbook on zyBooks I read through the selection sort and quicksort chapters and found example code that shows the use of the for loop to display the bids. This helped me implement the proper code for the enhancement.

### [Databases](https://github.com/taylorcruz/taylorcruz.github.io/tree/main/Artifact3)

For the databases category I chose project two from the CS 340 – Client/Server Development course which was created on December 9th, 2021. The goal of this project was to create a Python module that utilized mongoDB to access the mongoDB databases as an authorized user and implements CRUD methods. The database being accessed was the AAC animal shelter database. I also needed to create code for the web application dashboard. The dashboard imported the AnimalShelter Python module so that data could be taken from the AAC database and put into the data table on the dashboard. The dashboard also needed a unique identifier and to include the logo for Grazioso Salvare. There also needed to be interactive filtering options for the search and rescue training options, an interactive data table, a pie chart, and a geolocation chart that were all user-friendly. 
	This project displays my ability to write code in python and use of dash. It showcases my abilities to write the proper code for the user to utilize interactive options on the web application as well as incorporate data from a specific database. My ability to create code for a CRUD module and implement that module is also showcased. My goal for the enhancement of this project was to add a pie chart that will display the different rescue and search training options and the percentage of breeds that the animal shelter has, age, and sex for each of the training options. I was able to write the code for this and implement it into the dashboard. The user will be displayed with two dropdown options, the first one for the rescue and training options and the second one for the specifications (breed, sex, and age). I struggled at first with the code for the dropdown options but I believe I implemented it properly.
