# Larysa Bilychenko
### Front-end developer based in Europe
![Photo](https://github.com/LarysaBilychenko/rsschool-cv/raw/gh-pages/logo_Larysa.jpg)

********* 
### Let's get in touch
* #### Email: larisaubfster@gmail.com
* #### Phone: +38066 415 10 45
* #### Telegram: @larysabilychenko
* #### Discort rs-school: @larysa#7878
********* 
### About me
My name is Larysa, I am from Ukraine, temporarily living in Slovakia. I am a graduate of the Faculty of Physics, a former teacher, and now I am engaged in front-end development. Last year I successfully completed my studies at SheCodes worshops. Now I continue to actively work on improving my practical skills in creating websites and applications. 
********* 
### Skills
* HTML/CSS
* Responsive web development
* React
* JavaScript
* VSCode
* OpenAPI integration
* Git/GitHub
* Figma
******************* 
### Code example
This code allows us to get the current date and time from openApi and display it in a form: "date", "hours":"minutes" (for example: Monday, 10:00)
```
export default function FormattedDate(props) {
  let days = [
    "Sunday",
    "Monday",
    "Tuesday",
    "Wednesday",
    "Thursday",
    "Friday",
    "Saturday",
  ];
  let day = days[props.date.getDay()];
  let hours = props.date.getHours();
  if (hours < 10) {
    hours = `0${hours}`;
  }
  let minutes = props.date.getMinutes();
  if (minutes < 10) {
    minutes = `0${minutes}`;
  }
  return (
    <div>
      {day}, {hours}:{minutes}
    </div>
  );
}
```
**************** 
### Work experience
* Portfolio project (HTML, CSS, JS, Bootstrap, responsive): 
    + https://lambent-kringle-dfa3ec.netlify.app/ 
    + https://github.com/LarysaBilychenko/portfolio-project
* WeatherApp (HTML, CSS, JS, React, Bootstrap, openApi):
    + https://steady-meringue-b07717.netlify.app/
    + https://github.com/LarysaBilychenko/Final-React-Weather-App
****************************
### Education
* Kyiv National University, Master's degree
* Graduated from 
    + SheCodes Basics, 
    + SheCodes Plus, 
    + SheCodes Responsive, 
    + SheCodes React
****************************
### Level of English
* B2, worked in an English-speaking school for about 7 years as a teacher's assistant and later as a teacher
