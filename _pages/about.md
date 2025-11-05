---
layout: about
title: about
permalink: /
subtitle: "<strong>PhD student</strong> in <a href='https://saferobotics.princeton.edu/'>Safe Robotics Lab</a>, <strong>Princeton University</strong>"

profile:
  align: right
  image: Donggeon_Oh.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p><strong>Email:</strong>
      <button id="mail" data-e="ZG85OTQ4QHByaW5jZXRvbi5lZHU=" class="btn btn-sm z-depth-0" type="button">
        Click to email
      </button>
      <noscript>do9948 [at] princeton [dot] edu</noscript>
    </p>
    <script>
      (function () {
        var b = document.getElementById('mail');
        if (!b) return;
        // decode base64 on click; no mailto in DOM before interaction
        function d64(s){try{return atob(s);}catch(e){return "";}}
        b.addEventListener('click', function () {
          var addr = d64(b.dataset.e);           // "do9948@princeton.edu"
          if (!addr) return;
          window.location = 'mailto:' + addr;    // only created at click time
        });
      })();
    </script>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<!-- **Keywords:** **Safety-Critical Learning and Control**, **Human–Robot Interaction**, **Decision-Making under Uncertainty**. -->

---

Hi there :) I’m a PhD student in [Princeton ECE](https://ece.princeton.edu/), working with [Prof. Jaime F. Fisac](https://saferobotics.princeton.edu/jaime).

I push the boundaries of **safety assurance for intelligent systems**. In doing so,

- [ **Safety RL** ] I integrate insights from control theory, reinforcement learning (RL), and dynamic game theory to certify and enforce safety of high-dimensional, black-box systems under uncertainty.
- [ **Human–Robot Interaction** ] I investigate the interplay between humans and robots in safety-critical scenarios and how to foster safe, smooth, and trustworthy collaboration.

Ultimately, I envision a world where robots operate safely amidst other agents, including humans, in **unstructured, open-world environments**.

---

Previously, I earned a B.S. in Aerospace Engineering and a B.S. in Artificial Intelligence at Seoul National University, Republic of Korea.
