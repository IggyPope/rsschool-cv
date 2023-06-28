# Igor Vakulchik

#### JavaScript Developer

---

## Location:

**Belarus, Minsk.** Willing to move to Poland (have a PBH visa not linked to an employer).

---

## Contact information:

**Phone:** +375-29-368-0770\
**Email:** igor.a.vakulchik@gmail.com\
**Telegram:** [@Iggy_Rock](https://t.me/Iggy_Rock)\
[LinkedIn](https://www.linkedin.com/in/igor-vakulchik/)

---

## About me:

Having started my career as a financial analyst, I quickly fell in love with the more "technical" side of things: automating routine and time-consuming tasks with VBA code and Python scripts, working with SQL databases, creating Office extensions with C# and so on. I was growing in the field and became a team leader within FP&A department of a large tech company, but it didn't satisfy my passion for programming. So finally I have decided to pursue my dream career in the field of software development.

I am a keen learner and I feel like my ability and willingness to be constantly gaining new skills and knowledge is something that will lead me through this path of becoming a proficient Software Engineer.

---

## Skills:

- HTML5, CSS3
- JavaScript, TypeScript
- React, Next.js
- Node.js, Express
- SQL (MSSQL Server), NoSQL (MongoDB)

---

## Code example:

**'So Many Permutations!' Kata on Codewars (4 kyu):**\
_In this kata, your task is to create all permutations of a non-empty input string and remove duplicates, if present._

```javascript
function permutations(string) {
  if (string.length === 1) return [string]; // if the input is 1 char long, return input

  let result = [];

  const array = string.split(''); // convert the string to an array of characters

  // take each character...
  for (let charIndex in array) {
    let splicedArray = [...array];
    splicedArray.splice(charIndex, 1); // remove it from the array...

    // and recursively...
    for (let permutation of permutations(splicedArray.join(''))) {
      let variation = array[charIndex] + permutation; // combine it with the combinations of the rest of the chars
      if (!result.includes(variation)) result.push(variation);
    }
  }
  return result;
}
```

---

## Work experience:

- 2018-2022: EPAM Systems Inc. - Lead Financial Analyst, FP&A department
- 2016-2018: EPAM Systems Inc. - Senior Financial Analyst, FP&A department
- 2012-2016: EPAM Systems Inc. - Financial Analyst, FP&A department
- 2010-2012: A1 (ex-VELCOM) - Junior Controller, Controlling department

---

## Education:

- 2006-2011: Belarusian State Economic University, Bachelor of Finance

---

## Courses and certificates:

- [Rolling Scopes School](https://rs.school/) - JS / Front-End. Stage 0 (_in progress_)
- [Rolling Scopes School](https://rs.school/) - Node.js (_in progress_)
- [Udemy - The Complete 2023 Web Development Bootcamp](https://www.udemy.com/course/the-complete-web-development-bootcamp/)
- [Udemy - React - The Complete Guide 2023 (incl. React Router & Redux)](https://www.udemy.com/course/react-the-complete-guide-incl-redux/)

---
