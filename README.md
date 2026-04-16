<div align="center">
  <img src="nanami.gif" alt="nanami kento" width="800" />
</div>

---

<div align="center">
  <sub><i>「I can see the hand of a master.」</i></sub>
</div>

<br>

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
