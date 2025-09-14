# Vidhathri's Level 0 AIML Marvel Report

## Task 2: API (Application Programming Interface)

I built a weather web app using the **OpenWeather API** and a **jQuery plugin** to show real-time weather data. I cloned a GitHub repository, opened it in **VS Code**, and worked with the `index.html` file in the **demo** folder.

To make the app dynamic, I moved the weather-fetching code into a new `getWeather()` function that takes user input for the **city name**. This way, the app displays weather details based on the city entered by the user, instead of using a default one.

This helped me understand how to use **APIs** to fetch and display live data in a web application.

![Weather App](https://postimg.cc/kDSwF7Vt)

---

## Task 3: Working with GitHub 

Git is a version control system used to track changes in code, and GitHub is a platform that hosts Git repositories and enables collaboration through features like branches, pull requests, and issues.

For this task, I learned the basic Git and GitHub commands such as `add`, `commit`, `push`, `pull`, `fork`, and branching.

### Steps I followed:
- Forked the main repository to my GitHub account.
- Cloned it locally and created a new branch.
- Made changes in VS Code, then staged and committed them.
- Pushed the changes to GitHub.
- Created a pull request to the main repository.

I find Git and GitHub to be quite fascinating and will have to get more familiar with it.

![Github Pull Request](https://postimg.cc/9wcpQ7W5)

---

## Task 4: Ubuntu

In this task, I practiced using basic command line operations on Ubuntu. I began by creating a new directory named `test` using the `mkdir` command and navigated into it using `cd`. Inside the folder, I created a blank file without using any text editor by executing `touch filename`. To verify file creation, I listed all files in the directory using `ls`.

Next, I created 2600 folders. Finally, I concatenated two text files using the `cat` command and displayed their combined contents directly on the terminal.

This exercise helped me become more comfortable with essential terminal commands in Linux.

![UbuntuTerminal1](https://postimg.cc/68ZGFQXd)

![UbuntuTerminal2](https://postimg.cc/RWx06QkH)

---

## Task 5: Linear Regression

Linear regression models the relationship between a dependent variable and an independent variable using a straight line. The goal is to find the line that best fits the data by minimizing the total difference between the actual data points and the predicted values. This difference is measured by the squared errors to emphasize larger mistakes.

The slope of the line indicates how much the dependent variable changes when the independent variable increases by one unit. The intercept represents the value of the dependent variable when the independent variable is zero.

The method used to find the best-fitting line is called **least squares**. It ensures that the predictions are as close as possible to the observed data.

Linear regression is widely used because it is simple and interpretable.

---

## Task 6: The Matrix Puzzle

I began by loading the scrambled matrix from the provided `.npy` file using NumPy’s `np.load()` function.

Next, I examined the array's shape and total elements to determine an appropriate square shape for reshaping.

After reshaping the array into a 2D square (100×100), I identified that the image orientation was incorrect.

Using `np.rot90()` with `k=-1`, I rotated the matrix 90 degrees clockwise to correct the orientation.

I then visualized the result with `matplotlib.pyplot.imshow()`.

Through this process, I decoded and revealed the hidden image while practicing key NumPy and Matplotlib operations.

This is quite an interesting topic, and I will look into it more.

![ProperImage](https://postimg.cc/QVcwNQJP)

---

## Task 7: Portfolio Webpage 

I created a responsive portfolio website that showcases my information, interests, hobbies, and social media profiles. The site was designed using HTML and CSS, with responsiveness ensured through media queries for smooth viewing on various devices. I structured the content and added navigation links for easy access to different sections. The project code was pushed to a GitHub repository for remote storage. This task enhanced my skills in web design.

[Github Link](https://github.com/TimeToCode365/MarvelTask7)
[Website Link](https://timetocode365.github.io/MarvelTask7/)

---

## Task 8: Writing Resource Article Using Markdown

I successfully wrote a technical resource article titled **"How Rainbows Are Formed"** using Markdown. The process was surprisingly easy and more straightforward than HTML, making it enjoyable to create. I also learned how to publish the article as a live website using GitHub Pages. It was a rewarding and fun learning experience.

[Website Link](https://timetocode365.github.io/Task8Marvel/)

---

## Task 10: Speed of DC Motor

The speed of a DC motor is how fast its shaft rotates, usually measured in revolutions per minute (RPM). It depends mainly on two factors: the voltage applied to the motor and the load (how much work the motor is doing).

When you increase the voltage, the motor spins faster. If the motor has to move a heavier load, its speed decreases.

The speed can also be controlled using electronic methods like **Pulse Width Modulation (PWM)**, which adjusts the power supplied to the motor.
The L298N motor driver acts as an interface between the low-power Arduino signals and the higher current required by the DC motor.

![Speed of DC motor](https://postimg.cc/Y4TLpncL)

---

## Task 12: Soldering

Soldering is a process used to join metal parts by melting a metal alloy called **solder**. It creates a strong electrical and mechanical connection between components.

A soldering iron heats the parts to be joined, allowing the solder to melt and flow into the joint. Once cooled, the solder solidifies, securing the connection.

Soldering is essential in building and repairing electronic circuits to ensure good conductivity. Safety is important, including working in a ventilated area and handling the hot soldering iron carefully.

Overall, soldering is a key skill in electronics assembly and repair.

![Soldering](https://postimg.cc/QFxf5tFk)

---

## Task 14: Kmap and Logic Circuit

This task demonstrates how Karnaugh Maps simplify logic circuits. The alarm system was successfully implemented using basic digital components.

The Kmap, logic circuit, and burglar alarm implementation are shown below.


### Alarm System Logic

The system has two inputs:  
- **D (Door)** → `0 = closed`, `1 = open`  
- **K (Key)** → `0 = not pressed`, `1 = pressed`  

The **Alarm** should turn ON (e.g., blink LED or activate buzzer) **only when the door is open and the key is not pressed**.

---

### Truth Table

| Door (D) | Key (K) | Alarm |
|----------|---------|--------|
| 0        | 0       | 0      |
| 0        | 1       | 0      |
| 1        | 0       | 1      |
| 1        | 1       | 0      |

---

### Karnaugh Map

For 2 variables (D, K):

|       | K' | K |
|-------|----|---|
| D'    | 0  | 0 |
| D     | 1  | 0 |

The `1` is at **(D = 1, K = 0)**.

---

### Boolean Expression

From the K-map:  
**Alarm = D · K′**  
(Alarm is ON when the **Door is open** and the **Key is NOT pressed**)


![Circuit](https://postimg.cc/4K5Mbsmg)

---

## Task 15: Active Participation

**Participated in Hackathon: Codefury**

- Gained hands-on experience in web development and collaborative coding under a time-constrained, problem-solving environment.  
- Discovered the joy of applying programming skills creatively, shifting from passive learning to active implementation.  
- Motivated to further improve web development skills and build more impactful solutions in future projects.

![Codefury Certificate](https://postimg.cc/kDV1DxF9)
---

## Task 17: Introduction to VR

In this task, I was introduced to the fundamentals of **Virtual Reality (VR)**.  

[View Article](https://timetocode365.github.io/Task17Marvel/)

---

## Task 18: Sad Servers

For this task, I worked on a challenge called **Command Line Murders** on the **Sadservers** platform. It was all about using the Linux command line to explore folders, check files, and find clues to solve a mystery.

I had a lot of fun moving around the file system and trying out different commands. Along the way, I also learned some new Linux commands, which made the experience even better.

Overall, it was a fun and interesting way to practice **Linux troubleshooting**.

![Victory](https://postimg.cc/YLKb5CnZ)
---

## Task 20: Jupyter Notebooks 

I learned:

- How to write in **Markdown** (headings, lists, bold, italics, images, and code snippets)
- How to do basic math in **Python**
- How to create a simple plot using `matplotlib`

This helps build a strong foundation for creating readable and professional data notebooks!

I had lots of fun doing this!!!

[My Notebook](https://github.com/TimeToCode365/Task20Marvel/blob/main/Task_20.ipynb)

---

## Task 21: Intro to Machine Learning 

Understanding foundational ML concepts and data preparation techniques by watching two beginner-friendly videos and writing an article.

[Article](https://timetocode365.github.io/Task21Marvel/)

---







