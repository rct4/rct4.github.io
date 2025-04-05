---
layout: default
---

# About Me
I am a Master's student at the University of Illinois Urbana-Champaign studying Computer Science. I graduated with a degree in Computer Engineering with honors from UIUC.

I have interned at Intel and Northrup Grumman, with experience with High Performance Computing, scripting and automation, benchmarking, and networking.

In my free time, I love playing badminton and exploring the Pacific Northwest.

<button onclick="toggleText()" style="margin-top: 10px;">Show More</button>

<div id="extraText" style="display: none; margin-top: 10px;">
  <p>This is the extra content that shows up when you click the button! You can write about your project details, responsibilities, challenges, or anything else you want.</p>
</div>

<script>
  function toggleText() {
    var text = document.getElementById("extraText");
    var btn = event.target;
    if (text.style.display === "none") {
      text.style.display = "block";
      btn.textContent = "Show Less";
    } else {
      text.style.display = "none";
      btn.textContent = "Show More";
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