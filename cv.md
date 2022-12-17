![avatar](https://lh3.googleusercontent.com/a/AEdFTp7w4hxgEISVUWPYtjcOgX3d9yDsU0ZfVJ_MfX4EKw=s288-p-rw-no "Avatar")
# Mehdihanov Elmadin
***
## Contacts
*	Phone: +380996491673
*	E-mail: ster1904@gmail.com
*	GitHub: DartSter
*	Location: Lozova, Kharkiv region, Ukraine
***
## About Me
Persistent self-education day by day no day-off over 18 month. No real experience in projects yet.
***
## Skills
*	HTML
*	CSS/SASS (Basic)
*	JS (Basic)
*	React (Basic)
* TS (Basic)
***
## Code Example
**Description**: Your task is to implement our beloved Array.prototype.map function from a scratch, and yes, it has to be inside the Array's prototype. Don't know what a 'prototype' is? This could help you a little as well as this kata.

Moving on, the defaults for Array.prototype.map, Array.prototype.reduce, Array.prototype.reduceRight and Array.prototype.forEach will be banned, in other words you'll have to create map from scratch.

```
function map(f, context) {
  const result = [];
  let array = this;
  for (let index = 0; index < array.length; index++) {
    const item = array[index];
    const i = index;
    const arr = array;
    const bindedThis = f.bind(context);
    if (item === null || item || i in arr) {
      result.push(bindedThis(item, i, arr));
    } else result.length++
  }

  return result;
}
Array.prototype.map = map;
```
***
## Experience
* Code [rmdb-trainig](https://github.com/DartSter/rmdb-training), Site: [link](https://rmdb-project2.netlify.app/)
* ShareMe (based on JSM course on YouTube) - [link](https://shareme-jsx-project.netlify.app)

***
## Education

Language
* English - B1