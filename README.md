![Cover image](https://github.com/nileshparab42/Automation/blob/master/College%20Time%20Table%20Generator/Assets/TG-Cover.png)

# College Timetable Generator

Effective College Scheduling Solution

## Description

A college timetable generator is a computer program that helps students and faculty create schedules for their classes and labs. It typically allows users to input their course information, such as the name of the course, the instructor's name, and the time and location of the class. The time table generator then generates a customized schedule based on this information. The generated schedule may be presented in the form of a table or calendar view, making it easy for users to see their schedules at a glance. This type of project can be useful for college students and faculty as it helps them better plan their time and stay organized.
 
## Problem Statement

- Students and faculty may have difficulty keeping track of their schedules and ensuring that they are able to attend all of their classes and other academic activities.
- Coordinating schedules with those of other students and faculty can be challenging, particularly in larger colleges with many courses and instructors.
- Classrooms may not be used efficiently if schedules are not properly coordinated.
- Existing methods for creating and managing schedules, such as manual scheduling or using spreadsheets, can be tedious and error-prone.
- There is a need for a tool that can help students and faculty create and manage their schedules in an efficient and organized manner.

## Solution

### Representation of teacher

We developed a matrix that represents the teacher, This matrix includes details for each year including the teacher's name, shift, subject, theoretical hours, practical hours, and lab number.

![Teacher Matrix](https://github.com/nileshparab42/Amadeus/blob/master/assets/AD-Features.png)

### Allocation of lectures

1. Based on their timeslots, our system will filter teachers.
2. After that, we'll place them according to each year's schedules.
3. Teacher assignments will be made while they are still in effect.
4. Since we cycle through each teacher in each iteration, there won't be many lectures from the same teacher.
5. Parallel teacher allocation won't occur because we cycle through the teachers list and various years in each iteration at the same time.

We developed a matrix that represents the teacher, This matrix includes details for each year including the teacher's name, shift, subject, theoretical hours, practical hours, and lab number.

![Allocation strategy](https://github.com/nileshparab42/Amadeus/blob/master/assets/AD-Features.png)

### Generating word files

Finally, word documents will be generated for each schedule for each year.

![Word format](https://github.com/nileshparab42/Amadeus/blob/master/assets/AD-Features.png)

## Getting Started

### Language

* Python

### Modules

* docx
* random
* os

## Installation

### Get the College timetable generator Repository now.

To download a College timetable generator project, you can use the git clone command. This command creates a copy of the repository in a new directory on your local machine.
```
git clone https://github.com/nileshparab42/Amadeus.git
```
To set up the project, you can use the pip command to install the required packages specified in the requirements.txt file.
```
pip install -r requirements.txt
```
This will install all of the required packages for the project. If you are using a virtual environment for the project, you should activate the environment before running this command.
```
pip install virtualenv
virtualenv myenv
source myenv/bin/activate
pip install -r requirements.txt
```
This will create a new virtual environment called myenv, activate it, and then install the required packages.

### Installation of the College timetable generator 
To install an executable file of Amadeus, you can follow these steps:

1. Download the executable file from the Amadeus repository. You can do this by clicking on the file and then clicking the "Download" button, or by using the `curl` or `wget` command to download the file directly from the command line.
2. Make the file executable. In Linux or macOS, you can use the `chmod` command to give the file execute permissions:
```
chmod +x /path/to/amadeus.exe
```
3. Run the executable file. You can do this by double-clicking on the file in a file manager, or by running the following command in the terminal:
```
./amadeus.exe
```
4. Keep in mind that some executable files may require certain dependencies or libraries to be installed in order to run correctly. You may need to install these dependencies manually or using a package manager, such as `apt` or `yum`, before you can run the executable file.

## Authors

- [Nilesh Parab](https://github.com/nileshparab42) (Project Lead) - [Website](https://nileshparab10.blogspot.com/)
  

## Acknowledgements

- This project was inspired by the work of the [TheCodex](https://www.youtube.com/@TheCodex).
- We also used resources and tools from the [Aspose](https://blog.aspose.com/words/create-word-documents-using-python/) to develop and test our project.
