# CSE308 MUDE (Team Pine)

https://itsmude.com

CSE308, Spring 2018, Stony Brook University

## Team Members

* Lead Programmer: Wonyong Jeong (Young)
* Full Stack (UI) Engineer:    Hokyoon Woo (Jude)
* Full Stack (DATA) Engineer:   Brijesh Patel

## Stack Specification

### Backend

* JDK 8
* Spring 5
* JPA 
* Apache Tomcat 8.5

### Frontend

* Bootstrap 4
* Thymeleaf
* JavaScript
* HTML5
* CSS3

### DB & Data scraping

* MySQL
* Python
etc.

### Instructions
1. Clone the github repository
```
git clone https://github.com/judeWoo/mymude.git
cd mymude-master
```
2. Build using gradle wrapper (included in the repository)

On Linux/Mac
```
./gradlew build
java -jar build/libs/mymude-master.jar
```
On Windows
```
gradlew buildPlugin
java -jar build/libs/mymude-master.jar
```
3. Navigate to http://localhost:5000
4. Port number can be changed inside ```application.properties```
