Skip to content
You said:
I want a basic academic website
ChatGPT said:

Thought for 8s
I made you a clean, single-file academic website template with sections for About, Research, Publications, Teaching, Service, and Contact (plus SEO + schema.org, accessibility, and a dark/light toggle). Open the canvas to preview it live.

Want me to tailor it? Tell me:

your name/title/affiliation

headshot (portrait.jpg), CV (cv.pdf), and any links (Scholar, ORCID, GitHub)

a few publications (title, authors, venue, year, links)

courses you teach and terms

I can also split this into a multi-page site, add a blog, or convert it to Jekyll/Hugo/React if you prefer.

You said:
---
layout: default
title: "Home"
---

<section id="home">
  <div class="container home-container">
    <div class="left">
      <img src="{{ '/assets/website_pic.jpg' | relative_url }}" alt="Profile Picture" style="max-width: 50%; height: auto">
      <h1>Gautam Chandrasekaran</h1>
      <p>gautamc at cs dot utexas dot edu</p>
      <div class="buttons">
        <a href="https://www.linkedin.com/in/gautam-chandrasekaran-5139a1188/" target="_self">LinkedIn</a>
        <a href="https://scholar.google.com/citations?user=-CNU0tAAAAAJ&hl=en" target="_self">Google Scholar</a>
        <!--<a href="https://scholar.google.com/citations?user=-CNU0tAAAAAJ&hl=en" target="_blank">CV</a>!-->
      </div>
    </div>
    <div class="right">
      <h2>About Me</h2>
      <p>I am a fourth-year Ph.D student in the <a href="https://www.cs.utexas.edu/research/theoretical-computer-science" class="highlight-link" target="_self">Computer Science Theory Group</a> at UT Austin. I am fortunate to be advised by <a href="https://www.cs.utexas.edu/~klivans/" class="highlight-link"  target="_self">Adam Klivans</a> and <a href="https://www.cs.utexas.edu/~diz/" target="_self" class="highlight-link" >David Zuckerman</a>. I am mainly interested in Learning Theory and Complexity Theory. </p>
      <p> I received a B.Tech+M.Tech in Computer Science from IIT Madras in 2022 where I was advised by <a href="http://www.cse.iitm.ac.in/~jayalal/" class="highlight-link"  target="_self"> Jayalal Sarma</a>.</p>
    </div>
  </div>
</section>

<section id="publications">
  <div class="container publications-container">
      <h2>Publications (authors in alphabetical order)</h2>
    <!--JUNTA MRF-->
         <div class="publication-card">
      <h3>Learning Juntas under Markov Random Fields</h3>
      <p><b>Gautam Chandrasekaran</b>, Adam Klivans</p>
      <p><em>NeurIPS 2025 (to appear)</em></p>
      <a href="https://www.arxiv.org/pdf/2506.00764" target="_self">arXiv</a>
         </div>
    <!--SK MODEL-->
         <div class="publication-card">
      <h3>Learning the Sherrington-Kirkpatrick Model
Even at Low Temperature</h3>
      <p><b>Gautam Chandrasekaran</b>, Adam Klivans</p>
      <p><em>STOC 2025</em></p>
      <a href="https://arxiv.org/abs/2411.11174" target="_self">arXiv</a>
         </div>
  <!--TDS_NN-->
         <div class="publication-card">
      <h3>Learning Neural Networks with Distribution Shift: Efficiently Certifiable Guarantees</h3>
      <p><b>Gautam Chandrasekaran</b>, Adam Klivans, Lin Lin Lee, Konstantinos Stavropoulos</p>
      <p><em>ICLR 2025 </em></p>
           <a href="https://arxiv.org/abs/2502.16021" target="_self">arXiv</a>
         </div>
      <!-- MARGIN HALFSPACES-->
     <div class="publication-card">
      <h3>Learning Noisy Halfspaces with a Margin: Massart is No Harder than Random</h3>
      <p><b>Gautam Chandrasekaran</b>, Vasilis Kontonis, Konstantinos Stavropoulos, Kevin Tian</p>
      <p><em>NeurIPS 2024 (Spotlight)</em></p>
       <a href="https://arxiv.org/abs/2501.09851" target="_self">arXiv</a>
      </div>
    <!-- TDS LEARNING!-->
    <div class="publication-card">
      <h3>Efficient Discrepancy Testing for Learning with Distribution Shift</h3>
      <p><b>Gautam Chandrasekaran</b>, Adam Klivans, Vasilis Kontonis, Konstantinos Stavropoulos, Arsen Vasilyan</p>
      <p><em>NeurIPS 2024</em></p>
      <a href="https://arxiv.org/abs/2406.09373" target="_self">arXiv</a>
    </div>
    <!-- SMOOTH OPT -->
    <div class="publication-card">
      <h3>Smoothed Analysis for Learning Concepts with Low Intrinsic Dimension</h3>
      <p><b>Gautam Chandrasekaran</b>, Adam Klivans, Vasilis Kontonis, Raghu Meka, Konstantinos Stavropoulos</p>
      <p><em>COLT 2024</em></p>
      <p><b>Best Paper Award</b></p>
      <a href="http://arxiv.org/abs/2407.00966" target="_blank">arXiv</a>  
    </div>
    <!-- ONLINE MDP!-->
    <div class="publication-card">
      <h3>Learning in online MDPs: is there a price for handling the communicating case?</h3>
      <p><b>Gautam Chandrasekaran</b>, Ambuj Tewari</p>
      <p><em>UAI 2023</em></p>
      <a href="https://arxiv.org/abs/2111.02024" target="_self">arXiv</a>  
    </div>
  </div>
</section>


This was my old website contents. I want the same contents
ChatGPT said:

Thought for 22s
All set — I’ve swapped in your exact content (name, bio, links, and publications) and wired it into the template on the canvas. Take a look!

If you want this to be Jekyll-ready (with the --- front matter you showed), I can also output an index.md (or index.html) with the same styling and a _config.yml + assets/ structure. Just say “make it Jekyll,” and I’ll generate the files.

You said:
Academic Website – Single‑file Template (index
don't add any new content. Only what I uploaded. I want a basic HTML website, no fancy stuff
ChatGPT said:
Done — the file now contains exactly the simple HTML you provided, without any extra styling or additions.

You said:
Academic Website – Single‑file Template (index
even more basic
ChatGPT said:
It’s now reduced to the simplest possible HTML — just headings, text, and links with no styling or extra structure.

You said:
Academic Website – Single‑file Template (index
I want more spacing between pucblications
ChatGPT said:
I added simple spacing between each publication — they’ll now appear more separated for easier reading.

You said:
Academic Website – Single‑file Template (index
have new line for author list, venue, link etc
ChatGPT said:
Each publication now shows the title, author list, venue, and link on separate lines for a cleaner and more readable layout.

You said:
Academic Website – Single‑file Template (index
is the link to the picture there?
ChatGPT said:
I noted that your HTML file doesn’t include a link or tag for your profile picture — I suggested where and how to add one if you’d like it displayed.

You said:
Academic Website – Single‑file Template (index
the one i pasted had a lnk no?
ChatGPT said:
You're right — your original content did include a picture link (/assets/website_pic.jpg), but it was dropped when simplifying. I’ve added a note showing exactly how to restore it at the top of your HTML.

You said:
Academic Website – Single‑file Template (index
can you add it to the html
ChatGPT said:
I added your profile picture link (/assets/website_pic.jpg) near the top of the page so it appears before your name.

You said:
can you have some split screen thing, where the publications are on the right and scrollable whereas picture and contanct is fixed on the left
ChatGPT said:
I’ve created a split-screen layout: your picture and contact info stay fixed on the left, while the publications on the right scroll independently.

You said:
Academic Website – Single‑file Template (index
no have the about me also on the right
ChatGPT said:
The “About Me” section is now on the right side with your publications, while the left panel only shows your photo and contact details.

You said:
Academic Website – Single‑file Template (index
can you use a different font
ChatGPT said:
I updated the site to use the clean, modern Inter font from Google Fonts — it’ll look smoother and more professional while keeping everything simple.

You said:
Academic Website – Single‑file Template (index
make the picture smaller
ChatGPT said:
The profile picture is now smaller (60% width) and centered neatly with rounded corners for a more balanced look.



No file chosenNo file chosen
ChatGPT can make mistakes. Check important info.


Academic Website – Single‑file Template (index
1
2
3
4
5
6
7
8
9
10
11
12
13
14
15
16
17
18
19
20
21
22
23
24
25
26
27
28
29
30
31
32
33
34
35
36
37
38
39
40
41
42
43
44
45
46
47
48
49
50
51
52
53
54
55
56
57
58
59
60
61
62
63
64
65
66
67
68
69
70
71
72
73
74
75
76
77
78
79
80
81
82
83
84
85
86
87
88
89
90
91
92
93
94
95
96
97
98
99
100
101
102
103
104
105
106
107
108
109
110
111
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>Gautam Chandrasekaran</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap');
    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      display: flex;
      height: 100vh;
    }
    .left {
      width: 35%;
      background-color: #f5f5f5;
      padding: 20px;
      box-sizing: border-box;
      position: fixed;
      height: 100vh;
      overflow-y: auto;
    }
    .right {
      margin-left: 35%;
      padding: 20px;
      width: 65%;
      height: 100vh;
      overflow-y: scroll;
      box-sizing: border-box;
    }
    .profile-pic {
      max-width: 60%;
      height: auto;
      border-radius: 8px;
      display: block;
      margin: 0 auto 10px auto;
    }
    ul li {
      margin-bottom: 1.5em;
      line-height: 1.6;
    }
  </style>
</head>
<body>
  <div class="left">
    <img src="/assets/website_pic.jpg" alt="Profile Picture" class="profile-pic"><br>
    <h1>Gautam Chandrasekaran</h1>
    <p>Email: gautamc at cs dot utexas dot edu</p>
    <p><a href="https://www.linkedin.com/in/gautam-chandrasekaran-5139a1188/">LinkedIn</a> | <a href="https://scholar.google.com/citations?user=-CNU0tAAAAAJ&hl=en">Google Scholar</a></p>
  </div>

  <div class="right">
    <h2>About Me</h2>
    <p>I am a fourth-year Ph.D student in the <a href="https://www.cs.utexas.edu/research/theoretical-computer-science">Computer Science Theory Group</a> at UT Austin. I am fortunate to be advised by <a href="https://www.cs.utexas.edu/~klivans/">Adam Klivans</a> and <a href="https://www.cs.utexas.edu/~diz/">David Zuckerman</a>. I am mainly interested in Learning Theory and Complexity Theory.</p>
    <p>I received a B.Tech+M.Tech in Computer Science from IIT Madras in 2022 where I was advised by <a href="http://www.cse.iitm.ac.in/~jayalal/">Jayalal Sarma</a>.</p>

    <h2>Publications (authors in alphabetical order)</h2>
    <ul>
      <li>
        <b>Learning Juntas under Markov Random Fields</b><br>
        Gautam Chandrasekaran, Adam Klivans<br>
        <em>NeurIPS 2025 (to appear)</em><br>
        <a href="https://www.arxiv.org/pdf/2506.00764">arXiv</a>
      </li>

      <li>
        <b>Learning the Sherrington-Kirkpatrick Model Even at Low Temperature</b><br>
        Gautam Chandrasekaran, Adam Klivans<br>
        <em>STOC 2025</em><br>
        <a href="https://arxiv.org/abs/2411.11174">arXiv</a>
      </li>

      <li>
        <b>Learning Neural Networks with Distribution Shift: Efficiently Certifiable Guarantees</b><br>
        Gautam Chandrasekaran, Adam Klivans, Lin Lin Lee, Konstantinos Stavropoulos<br>
        <em>ICLR 2025</em><br>
        <a href="https://arxiv.org/abs/2502.16021">arXiv</a>
      </li>

      <li>
        <b>Learning Noisy Halfspaces with a Margin: Massart is No Harder than Random</b><br>
        Gautam Chandrasekaran, Vasilis Kontonis, Konstantinos Stavropoulos, Kevin Tian<br>
        <em>NeurIPS 2024 (Spotlight)</em><br>
        <a href="https://arxiv.org/abs/2501.09851">arXiv</a>
      </li>

      <li>
        <b>Efficient Discrepancy Testing for Learning with Distribution Shift</b><br>
        Gautam Chandrasekaran, Adam Klivans, Vasilis Kontonis, Konstantinos Stavropoulos, Arsen Vasilyan<br>
        <em>NeurIPS 2024</em><br>
        <a href="https://arxiv.org/abs/2406.09373">arXiv</a>
      </li>

      <li>
        <b>Smoothed Analysis for Learning Concepts with Low Intrinsic Dimension</b><br>
        Gautam Chandrasekaran, Adam Klivans, Vasilis Kontonis, Raghu Meka, Konstantinos Stavropoulos<br>
        <em>COLT 2024</em><br>
        <b>Best Paper Award</b><br>
        <a href="http://arxiv.org/abs/2407.00966">arXiv</a>
      </li>

      <li>
        <b>Learning in online MDPs: is there a price for handling the communicating case?</b><br>
        Gautam Chandrasekaran, Ambuj Tewari<br>
        <em>UAI 2023</em><br>
        <a href="https://arxiv.org/abs/2111.02024">arXiv</a>
      </li>
    </ul>
  </div>
</body>
</html>
