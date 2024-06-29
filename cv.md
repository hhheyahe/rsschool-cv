# YEKATERINA KLIMOVICH
## Front-end developer
Minsk, Belarus
Phone: +375293220611
Email: klimovich.yekaterina@gmail.com
### Summary:
I am able to communicate effectively and clearly with others, 
to listen and understand others’ perspectives and express my ideas and thoughts.
I’m capable to collaborate and cooperate with others towards a common goal. I value the input of my teammates and contribute effectively.
I possess the ability to grasp new information and apply it quickly in practical situations.
I’m driven by strong internal motivation to achieve my goals and perform well. I take initiative, persist in the 
face of obstacles, and constantly seek ways to improve myself.

Regarding my university experience, I have been fortunate to explore a wide range of 
technologies. I have worked with programming languages such as C++, the Qt 
framework, Java (and Spring), and Python. I have also delved into web development and utilized tools 
like Figma. Additionally, we have utilized Cisco Packet Tracer for networking education. 
Furthermore, I have gained experience with database management systems such as 
MySQL and PostgreSQL, and I have familiarized myself with Docker. Currently, I am 
expanding my skills in Linux terminal usage, Apache and Nginx server administration, and 
automated testing with Java.

Additionally, during my time at IT Academy, I solidified my knowledge in HTML and CSS 
and delved into the JavaScript language. In my final project, I utilized Google Firebase for 
user authentication and data storage purposes. This experience further enhanced my 
understanding of web development and allowed me to apply my skills in a practical 
setting.
### Skills 
Front-end:
* HTML
* CSS
* JavaScript

Databases:
* MySQL
* PostgreSQL
* Google Firebase

Programming languages:
* C++
* Java
* Python

Other:
* Figma
* Cisco Packet Tracer
* Linux
* Git, GitHub, GitLab
* Jenkins
* Kubernetes

### Languages 
* Russian (native)
* Belarusian (native)
* English (Upper Intermediate)

### Code example
**Codewars**: *Jaden Smith, the son of Will Smith, is the star of films such as The Karate Kid (2010) and After Earth (2013). Jaden is also known for some of his philosophy that he delivers via Twitter. When writing on Twitter, he is known for almost always capitalizing every word. For simplicity, you'll have to capitalize each word, check out how contractions are expected to be in the example below.*
*Your task is to convert strings to how they would be written by Jaden Smith. The strings are actual quotes from Jaden Smith, but they are not capitalized in the same way he originally typed them.*
```javascript
String.prototype.toJadenCase = function () {
  let result = '';
  if (this[0] !== ' ') {
      result += `${this[0].replace(this[0], this[0].toUpperCase())}`;
    }
    for (i = 1; i < this.length; i += 1) {
      if (this[i - 1] === ' ') {
        result += `${this[i].replace(this[i], this[i].toUpperCase())}`;
      }
      else {
          result += this[i];
      }
    }
  return result;
};
```
### Projects
*08.2023-09.2023* - **Trainee, Educational Center for Programming and High Tech (IT-Academy)**
**Project role:** Front-end developer
**Project description:**  a Single-Page Application created to make monitoring your finances 
easier. It helps to track your income and expenses and to manage budget.
**Used tools / responsibilities:** HTML, CSS, JS
[Project on GitHub](https://github.com/hhheyahe/MoneyWise)

### Educationa
*2021-2025* - **Belarusian State University of Informatics and Radioelectronics**
Specialization: Infocommunications Engineer

*05.2023 - 09.2023* - **Educational Center for Programming and High Tech (IT-Academy)**
Course: Web application development with JavaScript
Certificate: [JS Certificate](https://github.com/hhheyahe/courses_certificates/blob/main/JS%20Certificate%20.pdf)

*01.2023 - 04.2023* - **Educational Center for Programming and High Tech (IT-Academy)**
Course: Web site development with HTML, CSS & JavaScript
Certificate: [Certificate](https://github.com/hhheyahe/courses_certificates/blob/main/certificate.pdf)