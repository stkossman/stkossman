<p align="center">
  <img src="nanami_wp.jpg" alt="nanami kento image" />
</p>

###

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
      "Backend": ["C#", "Node.js"],
      "Database": ["MySQL", "PostgreSQL", "MSSQL", "Firebase"],
      "Frontend": ["JavaScript", "TypeScript", "TailwindCSS", "React", "Astro"],
      "DevOps": ["Git"],
    };
    this.learning = ["Express.js", "Prisma ORM", "Next.js", "Vim"];
  }

  toString() {
    return `${this.name} | ${this.role}`;
  }
}

const me = new Developer();
console.log(me.toString());
```
