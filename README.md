# CS 499 ePortfolio: Showcase of Computer Science Skills

Welcome to my ePortfolio here. Key projects ( items) in three fundamental fields of computer science—**Software Engineering and Design**, **Algorithms and Data Structures**, and **Databases**—showcase my development and competency in each. Descriptions of every artifact, intended improvements, and how each project fits with course outcomes and fundamental computer science knowledge are found below.



----



## 1. Weight Tracking App

**Category**: Software Engineering and Design  

Personal Project **Source**:



### Project Overview:

Simple and easy to use, the Weight Tracking App lets users:

**register and log in** to their personally owned account safely.

Track their development by adding and changing weight entries.

Establish **goals** for weight control.

Get **notifications** to prod them to record their weight.



### Improvement Strategy

I intend to add the following fixes to raise the functionality of the app:

Simplify the UI to make it more user-friendly and navigable for consumers of all technical proficiency.

Provide a simple text-based tool showing users their advancement toward their weight objectives (e.g., "You are 5 lbs away from your goal").

Allow users to adjust when they get reminders to enter their weight, therefore improving the notifying mechanism.



### Skills displayed:

Improving the UI of the app will help to increase user experience.

Establishing a notification system compatible for several devices is **basic**.

**User authentication** : Guaranturing safe user data management and login.



### Course Outcomes Aligned:

Create, design, and present professionally produced, user-need compliant software.

Use techniques for creating safe and easy-to-use software.

# Pseudocode for calculating goal progress in the Weight Tracking App

function checkGoalProgress(currentWeight, goalWeight):
    difference = goalWeight - currentWeight

    if difference > 0:
        print "You are " + difference + " lbs away from your goal."
    else if difference == 0:
        print "Congratulations! You've reached your goal!"
    else:
        print "You've surpassed your goal by " + abs(difference) + " lbs. Great job!"

# Example usage
currentWeight = 175
goalWeight = 170
checkGoalProgress(currentWeight, goalWeight)


—



## 2. Dog Search-and-Rescue Identification Project

** Category** : Data structures and algorithms  

**Source** : Course Project (Grazioso Salvare)



### Project Commentary:

Designed to assist a client (Grazioso Salvare) find appropriate canines from a database of shelter dogs for search-and-rescue training, this project To assist the client in making wise dog choices, the program sorts and filters canines depending on **breed**, **age**, and **weight**.



### Enhancement Scheme:

I intend to: help the project to run better by:

**Optize the filtering algorithm** to boost the accuracy and quickness in choosing appropriate canines.

Add **error handling** to guarantee flawless operation even in the case of unanticipated data or inputs lacking.

  

### Skills Clearly Showed:

Enhancing the efficiency of the choosing method is **algorithm design and optimization**.

Including steps to manage erroneous or absent inputs helps to **error handling**.

Creating a mechanism to rapidly and precisely sort through massive databases is **data filtering**.



### Course Results Consistent:

Using algorithmic ideas, design and assess computing solutions.

Optimize data handling and algorithm performance using well-founded approaches.


# flowchart:

Start
   |
[Input dog data from the database]
   |
[For each dog, apply filtering criteria: age, breed, weight]
   |
[Sort remaining dogs based on suitability score (using existing criteria)]
   |
[Output filtered list of eligible dogs]
   |
End



---->



## 3. Artemis Financial Secure Communication Project

** Category** : Design and Software Engineering and Database  

** Source**: Course Project



### Project Outlook:

Working with **Artemis Financial**, this project refactorated their online application and included safe communication systems. By adding encryption, checksum checking, and switching from HTTP to HTTPS, the security of customer data and payment information was hoped to be enhanced.



### Improvement Schedule:

I'll highlight the following improvements:

Use an encryption method for safe data moves between servers and clients.

Provide a mechanism employing checksum technology to confirm the integrity of imported data.

Refactor the code to substitute HTTPS for HTTP such that every communication is safely encrypted.



### Skills Showed:

Using encryption techniques helps to protect data moves.

Ensuring all correspondence between the client and server is encrypted via HTTPS guarantees **secure communication**.

Confirming that data is not corrupted or altered during transport by means of checksum verification helps to **data integrity**.



### Course Results in Line

Change your attitude to security and apply safe software programs.

Using industry-standard techniques will help to safeguard data and guarantee safe system connectivity.

# Pseudocode for enabling HTTPS in Artemis Financial project

# Step 1: Generate an SSL certificate using keytool
keytool -genkey -alias mydomain -keyalg RSA -keystore keystore.jks -keysize 2048

# Step 2: Configure the Spring Boot application to use HTTPS

# application.properties
server.port=8443
server.ssl.key-store=classpath:keystore.jks
server.ssl.key-store-password=changeit
server.ssl.key-password=changeit

# Step 3: Ensure that all traffic is redirected to HTTPS
class HttpsRedirectConfig extends WebSecurityConfigurerAdapter:
    
    protected void configure(HttpSecurity http):
        http.requiresChannel().anyRequest().requiresSecure()

# Now, the application will serve all requests over HTTPS


-------



## Overall Demonstrated in ePortfolio:

From user interface design to guaranteeing safe communication between systems, I have shown my capacity to create and polish professionally-quality software.

Optimizing data filtering and raising algorithm efficiency has helped me to demonstrate my abilities in managing vast amounts of data and generating scalable solutions.

Projects like Artemis Financial have helped me to show that I grasp safe database handling, encryption, and secure communication techniques.



Thank you for reviewing my ePortfolio. Each artifact has been carefully selected and enhanced to demonstrate my continued growth and proficiency in computer science. Please feel free to explore each project through the links provided.




