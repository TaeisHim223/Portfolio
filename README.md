# My Portfolio
### Hi there 👋, my name is Sedtavian Robinson
#### My interests include coding, sports, and animation.
I graduated ComputerCoach , focusing on front-end web development. I was born in Ft. Myers on August 17th, 2006. I was raised in Kissimmee, and then my family moved to Lakeland.

Skills: Canva/ HTML / CSS / JS

html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sedtavian Robinson | Entry-Level Front-End Developer</title>

  <style>
    :root{
      --bg:#0b0b0f;
      --card:#14141c;
      --text:#f5f5f7;
      --muted:#b6b6c2;
      --line:#2a2a36;
      --accent:#f5a524;
      --accent2:#7dd3fc;
    }

    *{ box-sizing:border-box; margin:0; padding:0; font-family: Arial, Helvetica, sans-serif; }
    body{ background:var(--bg); color:var(--text); line-height:1.6; }

    /* Layout */
    .wrap{ max-width:1100px; margin:0 auto; padding:0 18px; }
    section{ padding:56px 0; }
    .grid{ display:grid; gap:18px; }
    @media(min-width:900px){
      .grid-2{ grid-template-columns: 1.1fr 0.9fr; }
      .grid-3{ grid-template-columns: repeat(3, 1fr); }
    }

    /* Hero */
    header{
      position:relative;
      padding:84px 0 58px;
      overflow:hidden;
      border-bottom:1px solid var(--line);
      background:
        radial-gradient(900px 320px at 15% 30%, rgba(245,165,36,.22), transparent 60%),
        radial-gradient(900px 320px at 85% 20%, rgba(125,211,252,.18), transparent 60%),
        linear-gradient(180deg, rgba(255,255,255,.04), transparent 70%);
    }
    .badge{
      display:inline-flex; gap:10px; align-items:center;
      padding:8px 12px; border:1px solid var(--line);
      background:rgba(255,255,255,.03); border-radius:999px;
      color:var(--muted); font-size:14px;
      margin-bottom:14px;
    }
    .badge span{ color:var(--accent); font-weight:700; }
    h1{ font-size:42px; line-height:1.15; letter-spacing:.2px; }
    .sub{ color:var(--muted); margin-top:10px; max-width:68ch; }
    .cta{ display:flex; flex-wrap:wrap; gap:10px; margin-top:18px; }
    .btn{
      display:inline-block; padding:11px 14px; border-radius:10px;
      border:1px solid var(--line); background:rgba(255,255,255,.03);
      color:var(--text); text-decoration:none; font-weight:700;
    }
    .btn.primary{
      border-color:rgba(245,165,36,.5);
      background:linear-gradient(135deg, rgba(245,165,36,.22), rgba(245,165,36,.08));
    }
    .btn:hover{ transform: translateY(-1px); transition:.15s ease; }

    /* Cards */
    .card{
      background:var(--card);
      border:1px solid var(--line);
      border-radius:14px;
      padding:18px;
    }
    .card h3{ margin-bottom:8px; font-size:18px; }
    .muted{ color:var(--muted); }
    .pill-row{ display:flex; flex-wrap:wrap; gap:8px; margin-top:12px; }
    .pill{
      border:1px solid var(--line);
      background:rgba(255,255,255,.03);
      padding:7px 10px;
      border-radius:999px;
      font-size:13px;
      color:var(--muted);
    }

    /* Section titles */
    .title{
      display:flex; align-items:center; justify-content:space-between; gap:14px;
      margin-bottom:16px;
    }
    .title h2{ font-size:22px; }
    .line{ height:1px; background:var(--line); flex:1; }

    /* Lists */
    ul{ margin-left:18px; }
    li{ margin:6px 0; color:var(--muted); }
    .strong{ color:var(--text); font-weight:700; }

    /* Footer */
    footer{
      border-top:1px solid var(--line);
      padding:30px 0;
      color:var(--muted);
      text-align:center;
      background:rgba(255,255,255,.02);
    }

    /* Tiny highlights */
    .accent{ color:var(--accent); font-weight:800; }
    .link{ color:var(--accent); text-decoration:none; font-weight:700; }
    .link:hover{ text-decoration:underline; }
  </style>
</head>

<body>

  <!-- HERO -->
  <header>
    <div class="wrap">
      <div class="badge">
        <span>Entry-Level</span> Front-End Web Developer • Lakeland, FL • Authorized to work in the U.S.
      </div>

      <h1>Sedtavian Robinson</h1>
      <p class="sub">
        Teachable and aspiring Jr. Front-End Developer with training in
        <span class="accent">HTML, CSS, JavaScript, and WordPress</span>.
        Strong teamwork + customer service background, looking to grow on a supportive dev team.
      </p>

      <div class="cta">
        <a class="btn primary" href="#projects">View Projects</a>
        <a class="btn" href="#credentials">Credentials</a>
        <a class="btn" href="#contact">Contact</a>
      </div>

      <p class="sub" style="margin-top:14px;">
        Email: <a class="link" href="mailto:tyktaysed@gmail.com">tyktaysed@gmail.com</a>
        <br/>
        Phone: <span class="strong">+1 (863) 267-6387</span>
      </p>
    </div>
  </header>

  <!-- ABOUT + SKILLS -->
  <section>
    <div class="wrap">
      <div class="title">
        <h2>About</h2><div class="line"></div>
      </div>

      <div class="grid grid-2">
        <div class="card">
          <h3>Summary</h3>
          <p class="muted">
            I completed a front-end training program where I learned JavaScript, CSS, HTML, and WordPress.
            I’m focused on building clean, responsive websites and improving daily through projects.
            I’m looking for an entry-level role or internship where I can learn fast and contribute.
          </p>

          <div class="pill-row">
            <span class="pill">Responsive Design</span>
            <span class="pill">Clean UI</span>
            <span class="pill">Teamwork</span>
            <span class="pill">Customer Service</span>
            <span class="pill">Problem Solving</span>
          </div>
        </div>

        <div class="card">
          <h3>Relevant Skills</h3>
          <div class="pill-row">
            <span class="pill">HTML</span>
            <span class="pill">CSS</span>
            <span class="pill">JavaScript</span>
            <span class="pill">WordPress</span>
            <span class="pill">Canva</span>
            <span class="pill">Communication</span>
            <span class="pill">Flexible</span>
          </div>

          <p class="muted" style="margin-top:12px;">
            Want this to look even more “dev-ready”? Add:
            <span class="strong">GitHub</span>, <span class="strong">Projects</span>, and a <span class="strong">Live Demo</span> link for each project.
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- CREDENTIALS -->
  <section id="credentials">
    <div class="wrap">
      <div class="title">
        <h2>Digital Credentials</h2><div class="line"></div>
      </div>

      <div class="grid grid-3">
        <div class="card">
          <h3>Front-End Web Development</h3>
          <p class="muted">Credential from Computer Coach Training Center.</p>
          <p class="muted" style="margin-top:8px;">
            <span class="strong">Add your credential link here:</span><br/>
            <a class="link" href="#" target="_blank" rel="noreferrer">View Credential</a>
          </p>
        </div>

        <div class="card">
          <h3>JavaScript</h3>
          <p class="muted">Credential from Computer Coach Training Center.</p>
          <p class="muted" style="margin-top:8px;">
            <span class="strong">Add your credential link here:</span><br/>
            <a class="link" href="#" target="_blank" rel="noreferrer">View Credential</a>
          </p>
        </div>

        <div class="card">
          <h3>HTML & CSS</h3>
          <p class="muted">Credential from Computer Coach Training Center.</p>
          <p class="muted" style="margin-top:8px;">
            <span class="strong">Add your credential link here:</span><br/>
            <a class="link" href="#" target="_blank" rel="noreferrer">View Credential</a>
          </p>
        </div>

        <div class="card">
          <h3>WordPress</h3>
          <p class="muted">Credential from Computer Coach Training Center.</p>
          <p class="muted" style="margin-top:8px;">
            <span class="strong">Add your credential link here:</span><br/>
            <a class="link" href="#" target="_blank" rel="noreferrer">View Credential</a>
          </p>
        </div>
      </div>

      <p class="muted" style="margin-top:14px;">
        Tip: When you click “View your credential” in those emails, copy the URL and paste it into the links above.
      </p>
    </div>
  </section>

  <!-- PROJECTS -->
  <section id="projects">
    <div class="wrap">
      <div class="title">
        <h2>Projects</h2><div class="line"></div>
      </div>

      <div class="grid grid-3">
        <div class="card">
          <h3>Project 1 (Starter)</h3>
          <p class="muted">A responsive landing page using HTML & CSS.</p>
          <p class="muted" style="margin-top:10px;">
            <a class="link" href="#" target="_blank" rel="noreferrer">Live Demo</a> •
            <a class="link" href="#" target="_blank" rel="noreferrer">Code</a>
          </p>
        </div>

        <div class="card">
          <h3>Project 2 (JavaScript)</h3>
          <p class="muted">A small app like a calculator, to-do list, or weather UI.</p>
          <p class="muted" style="margin-top:10px;">
            <a class="link" href="#" target="_blank" rel="noreferrer">Live Demo</a> •
            <a class="link" href="#" target="_blank" rel="noreferrer">Code</a>
          </p>
        </div>

        <div class="card">
          <h3>Project 3 (WordPress)</h3>
          <p class="muted">A clean WordPress site with a custom theme layout.</p>
          <p class="muted" style="margin-top:10px;">
            <a class="link" href="#" target="_blank" rel="noreferrer">Live Demo</a> •
            <a class="link" href="#" target="_blank" rel="noreferrer">Details</a>
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- EXPERIENCE -->
  <section>
    <div class="wrap">
      <div class="title">
        <h2>Experience</h2><div class="line"></div>
      </div>

      <div class="grid grid-2">
        <div class="card">
          <h3>Student — Computer Coach IT Training (Remote)</h3>
          <p class="muted">Oct 2024 – Dec 2024</p>
          <ul>
            <li>Learned core concepts of the internet and web applications.</li>
            <li>Built websites using <span class="strong">HTML, CSS, WordPress, and JavaScript</span>.</li>
            <li>Completed hands-on projects and created an early portfolio.</li>
          </ul>
        </div>

        <div class="card">
          <h3>Recreation Assistant Intern — Simpson Park Community Center (Lakeland, FL)</h3>
          <p class="muted">Jul 2024 – Jan 2025</p>
          <ul>
            <li>Prepared rooms for youth league basketball + events.</li>
            <li>Helped coordinate events with 20–50 visitors.</li>
            <li>Maintained clean indoor/outdoor facilities for a great experience.</li>
            <li>Restocked supplies and promoted upcoming events.</li>
            <li>Provided strong customer service by greeting and directing visitors.</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <!-- EDUCATION -->
  <section>
    <div class="wrap">
      <div class="title">
        <h2>Education</h2><div class="line"></div>
      </div>
      <div class="card">
        <h3>Lake Gibson Senior High School — Lakeland, FL</h3>
        <p class="muted">Graduated: May 2024</p>
      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact">
    <div class="wrap">
      <div class="title">
        <h2>Contact</h2><div class="line"></div>
      </div>

      <div class="grid grid-2">
        <div class="card">
          <h3>Let’s connect</h3>
          <p class="muted">
            If you’re hiring for an entry-level front-end role, internship, or junior position,
            I’d love to talk.
          </p>
          <p class="muted" style="margin-top:12px;">
            Email: <a class="link" href="mailto:tyktaysed@gmail.com">tyktaysed@gmail.com</a><br/>
            Phone: <span class="strong">+1 (863) 267-6387</span><br/>
            Location: <span class="strong">Lakeland, FL</span>
          </p>
        </div>

        <div class="card">
          <h3>Links</h3>
          <p class="muted">Add these when you’re ready:</p>
          <ul>
            <li>GitHub: <a class="link" href="#" target="_blank" rel="noreferrer">github.com/yourname</a></li>
            <li>LinkedIn: <a class="link" href="#" target="_blank" rel="noreferrer">linkedin.com/in/yourname</a></li>
            <li>Resume PDF: <a class="link" href="#" target="_blank" rel="noreferrer">Download</a></li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <footer>
    <div class="wrap">
      © <span id="year"></span> Sedtavian Robinson • Entry-Level Front-End Developer
    </div>
  </footer>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>

</body>
</html>

[<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg' alt='github' height='40'>](https://github.com/TaeisHim223)  [<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/codesandbox.svg' alt='codesandbox' height='40'>](https://codesandbox.io/u/TaeisHim223)  

https://codepen.io/ITWOSWIFT/pen/vYoodZE

https://codepen.io/ITWOSWIFT/pen/OJKKQom

https://codepen.io/ITWOSWIFT/pen/JjgVGEV

https://www.canva.com/design/DAGVhtrh3GE/tX81jzvtXY70MVo4_TYUvw/edit?utm_content=DAGVhtrh3GE&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton

https://www.canva.com/design/DAGVh8aLeQY/shH6mGN-cImrdQ16Dru67A/edit?utm_content=DAGVh8aLeQY&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton


