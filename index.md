---
layout: default
---

# About Me
I am a Master's student at the University of Illinois Urbana-Champaign studying Computer Science. I graduated with a degree in Computer Engineering with honors from UIUC.

I have interned at Intel and Northrup Grumman, with experience with High Performance Computing, scripting and automation, benchmarking, and networking.

In my free time, I love playing badminton and exploring the Pacific Northwest.

<h3 style="cursor: pointer; color: #0366d6;" onclick="toggleText(this)">
  ▶️ Project Title
</h3>
<div id="extraText" style="display: none; margin-left: 1rem; margin-top: 0.5rem;">
  <p>This is more info about the project — tools used, what you built, cool problems you solved, etc.</p>
</div>

<script>
  function toggleText(header) {
    var content = header.nextElementSibling;
    if (content.style.display === "none" || content.style.display === "") {
      content.style.display = "block";
      header.innerHTML = "🔽 Project Title";
    } else {
      content.style.display = "none";
      header.innerHTML = "▶️ Project Title";
    }
  }
</script>

## Courses Taken
[CS 374 Algorithms](https://siebelschool.illinois.edu/academics/courses/cs374) 

[ECE 391 Computer Systems Organizations/Operating Systems]

[ECE 385 Digital Systems (FPGA)]

[CS 446 Machine Learning]

[CS 425 Distributed Systems]

[ECE 434 Mobile Computing IOT]

[CS 447 NLP]

[ECE 310 Digital Signal Processing]

[ECE 342 Circuits]



## Projects
### Autonomous Soil Monitoring Rover


---
_Built with [Jekyll](https://jekyllrb.com/) and hosted on GitHub Pages._