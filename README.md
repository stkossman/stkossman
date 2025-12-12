<img src="blackwhite_sky.jpg" alt="sky" />

###

<h1 align="center">
  <span style="color: #A0A0A0">６１０</span>
</h1>

<h3 align="center">About Me</h3>

###

```ruby
class Developer
  def initialize
    @name = "kossman"
    @role = "Front-End Developer"
    @skills = {
      "Backend" => ["C#", "C++", "Python"],
      "Database" => ["MySQL", "PostgreSQL", "MSSQL", "Firebase"],
      "Frontend" => ["JavaScript", "TypeScript", "TailwindCSS", "React", "Astro"],
      "DevOps" => ["Docker", "Git"],
    }
    @learning = ["Node.js", "Express.js", "NestJS", "Prisma ORM"]
    @passion = "im dead inside"
  end

  def to_s
    "#{@name} | #{@role}"
  end
end

me = Developer.new
puts me
```

<!-- why? do not look there. no need anyways -->
