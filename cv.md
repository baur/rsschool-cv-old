# Yessetov Bauyrzhan
### Beginning Frontend learner
---
### Contact information:
**E-mail:** Bauyrzhan.Yessetov@gmail.com  
**Telegram:** @Baur114

---
### Summary
For a long time, I worked as a developer at a mining company. I mostly worked with databases and developed desktop applications and did not pay attention to what was going on in the IT world. One day I found out that the world was changing and IT is not the same when I graduated. I decided to make up for lost time and took up front-end development.

---
### Skills
- PL\SQL
- TSQL
- SQL Server Reporting Services (SSRS)
- Basic level of:
    - JavaScript
    - HTML/CSS
    - NodeJS

---
### Code Example
Your job is to figure out the index of which vowel is missing from a given string:
```
- [A] has an index of 0,
- [E] has an index of 1,
- [I] has an index of 2,
- [O] has an index of 3,
- [U] has an index of 4.
```
**Notes:** There is no need for string validation and every sentence given will contain all vowles but one. Also, you won't need to worry about capitals.

**Examples**
```
"John Doe hs seven red pples under his bsket"          =>  0  ; missing: "a"
"Bb Smith sent us six neatly arranged range bicycles"  =>  3  ; missing: "o"
```
**Solution**
```js
function absentVowel(x) {
  const vowels = ["A", "E", "I", "O", "U"];
  const word = x.toUpperCase();
  for (let i = 0; i < vowels.length; i++) {
    if (word.indexOf(vowels[i]) === -1) {
      return i;
    }
  }
  return 0;
}
```

---
### Experience
*IT Departament*
```
2008 - 2012 | JSC Temirbank (Kazakhstan / Almaty)
```

- Custom reports and scripts in PL/SQL (Oracle) for banking the system

*IT Departament*
```
from 2013 | Kazakhmys PLC (Kazakhstan / Zhezkazgan)
```

- Create reports in T-SQL (MS SQL Server)
- Publish reports via [SQL Server Reporting Services (SSRS)](https://en.wikipedia.org/wiki/SQL_Server_Reporting_Services)
- Create Dashboards in [Grafana](https://grafana.com/)

---
### Education
*Zhezkazgan University*
```
2001 - 2006 | Informatics (010540)
```

#### Courses and Certificates

- Udemy [JavaScript](https://www.udemy.com/certificate/UC-7c924e05-f3bd-49c3-962b-40700b6b70e3/) (completed)
- RS School [JavaScript/Front-end 2021Q3](https://rs.school/js/) (in progress)
- Hexlet [JavaScript/Front-end](https://ru.hexlet.io/programs/frontend) (in progress)

---
### English
[Level A1](https://www.efset.org/cefr/a1) (According to EPAM Еraining center test)