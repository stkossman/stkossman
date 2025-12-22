<img src="blackwhite_sky.jpg" alt="sky" />

###

<h1 align="center">
  <span style="color: #A0A0A0">６１０</span>
</h1>

<p align="center">
  <i>I can see the hand of a master</i>
</p>

###

```js
class Developer {
  constructor() {
    this.name = "kossman";
    this.role = "Front-End Developer";
    this.skills = {
      "Backend": ["C#", "C++", "Python"],
      "Database": ["MySQL", "PostgreSQL", "MSSQL", "Firebase"],
      "Frontend": ["JavaScript", "TypeScript", "TailwindCSS", "React", "Astro"],
      "DevOps": ["Docker", "Git"],
    };
    this.learning = ["Node.js", "Express.js", "NestJS", "Prisma ORM"];
  }

  toString() {
    return `${this.name} | ${this.role}`;
  }
}

const me = new Developer();
console.log(me.toString());
```
