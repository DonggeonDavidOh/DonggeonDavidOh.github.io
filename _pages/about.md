---
layout: about
title: about
permalink: /
subtitle: "<strong>PhD student</strong> in <a href='https://saferobotics.princeton.edu/'>Safe Robotics Lab</a>, <strong>Princeton University</strong>"

profile:
  align: right
  image: Donggeon_Oh.jpg
  image_circular: false
  more_info: >
    <p style="margin:0 0 .75rem 0;">
      <strong>Email:</strong>
      <span id="email-slot">
        <button id="reveal-email"
                class="btn btn-sm z-depth-0"
                type="button"
                data-e="ZG85OTQ4QHByaW5jZXRvbi5lZHU=">Click to reveal</button>
      </span>
      <noscript>do9948 [at] princeton [dot] edu</noscript>
    </p>

    <script>
    (function () {
      var btn  = document.getElementById('reveal-email');
      var slot = document.getElementById('email-slot');
      if (!btn || !slot) return;

      function d64(s){ try { return atob(s); } catch(e){ return ""; } }

      btn.addEventListener('click', function () {
        var addr = d64(btn.getAttribute('data-e')); // "do9948@princeton.edu"
        if (!addr) return;

        // Replace the entire button with a clickable mail link
        var a = document.createElement('a');
        a.href = 'mailto:' + addr;
        a.textContent = addr;

        slot.innerHTML = '';        // remove the button
        slot.appendChild(a);        // show the email in its place
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
