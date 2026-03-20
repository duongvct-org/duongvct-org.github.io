:::layout

```{=html}
<div style="grid-column: 1 / -1;" class="hero panel">
  <div class="description">
    <div class="name">
      <h1 class="title">Duong Vu Cong Tuan</h1>
    </div>
    <div class="salute">
    <span>
      Hello! I'm Duong Vu Cong Tuan, a software developer. I am currently a senior at PTIT, Hanoi, Vietnam and a software developer intern. Welcome to my blog about programming, software development, my life, my point of view and everything in between.
    </span>
    </div>
  </div>
</div>
```


:::{.panel id="posts"}
```{=html}
<h2 class="section-title">Recent Posts</h2>
<a href="https://vucongtuanduong.github.io/posts/index-file/">
          Index file of the blog
        </a>
<a href="https://vucongtuanduong.github.io/school/school-post-index/">
          Index file of the school posts
        </a>
```

{{ recent-list 7 }}

[View all...](/posts)
:::



```{=html}
<section id="experience" class="panel">
  <h2 class="section-title">Experience</h2>

  <ul class="lib-list">
    <li>
      <div style="width: 100%;">
        <div class="header">
          <h3 class="title">Software Development Intern</h3>
          <span class="date">July 2025 — Present</span>
        </div>
        
        <div class="company">
          Viettel IDC
        </div>

        <ul class="description bullet">
          <li>Took part in migrating some APIs from old monolithic service to new Database service</li>
          <li>Developed backend for database admin portal service</li>
          <li>Took part in developing monitoring and configuration feature for proxy agent</li>
        </ul>
        <div class="skill-list">
          <span class="skill">Spring Boot</span>
          <span class="skill">MariaDB</span>
          <span class="skill">Docker</span>
          <span class="skill">Microservices</span>
        </div>
      </div>
    </li>

    <li>
      <div style="width: 100%;">
        <div class="header">
          <h3 class="title">Software Engineer Intern</h3>
          <span class="date">April 2025 — June 2025</span>
        </div>
        
        <div class="company">
          Viettel Digital Talent
        </div>
        Specialized training with:
        <ul class="description bullet">
          <li> Version Control System, Linux Operating System, Docker, SQL, Agile</li>
          <li>Web architecture, security and database in web development, web deployment and optimization</li>
          <li>Mini-project about load-testing system using Spring Boot</li>
        </ul>
        <div class="skill-list">
          <span class="skill">Git</span>
          <span class="skill">Linux</span>
          <span class="skill">Docker</span>
          <span class="skill">SQL</span>
          <span class="skill">Spring Boot</span>
        </div>
      </div>
    </li>
  </ul>
</section>
<!-- Projects panel -->
<section id="projects" class="panel" style="grid-column: 1 / -1;">
  <h2 class="section-title">Projects</h2>

  <ol class="project-list" aria-label="Projects">
    <li>
      <div class="title">
        <span class="date">January 2026 - January 2026</span>
        <a href="https://github.com/vucongtuanduong/codecrafters-shell-go1">
          Shell implementation from scratch in Go
        </a>
      </div>
      <div class="meta">
        <span class="authors">Author: Duong Vu Cong Tuan</span>
        <p class="description">
          A shell written from scratch in Go, supporting builtin commands (exit, echo, type, pwd, cd), executing external programs, navigation, quoting, redirection, autocompletion, pipelines and history with the help of Codecrafter platform
        </p>
        <div class="meta">
          <a class="skill">Go</a>
          <a class="skill">Bash</a>
        </div>
      </div>
    </li>


    <li>
      <div class="title">
        <span class="date">April 2025 - June 2025</span>
        <a href="https://github.com/Duong-Vu-Personal-Projects/load-testing-system">
          Load testing system
        </a>
      </div>
      <div class="meta">
        <span class="authors">Author: Duong Vu Cong Tuan</span>
        <p class="description">
          A fully dockerized system built with ReactJS and Spring Boot which allows user to create JMeter-like load test scenario in web, schedule, run, and view the visualization result of the test
        </p>
        <div class="meta">
          <a class="skill">Java</a>
          <a class="skill">Spring Boot</a>
          <a class="skill">ELK Stack</a>
          <a class="skill">MongoDB</a>
          <a class="skill">Prometheus</a>
          <a class="skill">Grafana</a>
          <a class="skill">JMeter</a>
          <a class="skill">Docker</a>
        </div>
      </div>
    </li>
  </ol>
</section>
```
:::