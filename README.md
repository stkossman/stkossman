<div align="center">
  <img src="nanami.gif" alt="nanami kento" />
</div>

---

<p align="center">
  <a href="https://readme-typing-svg.demolab.com">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=14&pause=2000&color=6E9FFF&center=true&width=435&lines=I+can+see+the+hand+of+a+master" alt="Typing SVG" />
  </a>
</p>

```ts
import type { Stack } from "./types";

interface Developer {
  name:     string;
  role:     string;
  stack:    Stack;
  learning: string[];
}

const kossman = {
  name: "Andrii Stavskyi",
  role: "Frontend Developer",

  stack: {
    frontend: ["React", "Astro", "TypeScript", "TailwindCSS"],
    backend:  ["Node.js", "C#", "Express.js"],
    database: ["PostgreSQL", "MySQL", "Firebase"],
    tooling:  ["Git", "Vim"],
  },

  learning: ["Next.js", "Prisma ORM"],
} satisfies Developer;

export default kossman;
```
