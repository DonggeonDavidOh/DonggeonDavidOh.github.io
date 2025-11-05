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
    <p style="margin:0 0 .75rem 0;">
      <strong>Email:</strong>
      <button id="reveal-email"
              class="btn btn-sm z-depth-0"
              type="button"
              data-e="ZG85OTQ4QHByaW5jZXRvbi5lZHU="  <!-- base64 of do9948@princeton.edu -->
              aria-expanded="false">
        Click to reveal
      </button>
      <span id="email-text" style="margin-left:.5rem;"></span>
      <span id="email-status" style="margin-left:.5rem; opacity:.8;"></span>
      <noscript>do9948 [at] princeton [dot] edu</noscript>
    </p>

    <script>
    (function () {
      var btn = document.getElementById('reveal-email');
      var out = document.getElementById('email-text');
      var status = document.getElementById('email-status');
      if (!btn || !out) return;

      var revealed = false;
      function d64(s){ try { return atob(s); } catch(e){ return ""; } }
      function setStatus(msg){ if (status) { status.textContent = msg; setTimeout(function(){ status.textContent=""; }, 1500); } }

      async function copyText(text){
        try {
          if (navigator.clipboard && navigator.clipboard.writeText) {
            await navigator.clipboard.writeText(text);
          } else {
            // Fallback for older browsers
            var ta = document.createElement('textarea');
            ta.value = text;
            ta.style.position = 'fixed';
            ta.style.left = '-9999px';
            document.body.appendChild(ta);
            ta.select();
            document.execCommand('copy');
            document.body.removeChild(ta);
          }
          return true;
        } catch (e) { return false; }
      }

      btn.addEventListener('click', async function () {
        var addr = d64(btn.getAttribute('data-e')); // "do9948@princeton.edu"
        if (!addr) return;

        if (!revealed) {
          // First click: show the address text only
          out.textContent = addr;
          btn.textContent = 'Copy email';
          btn.setAttribute('aria-expanded', 'true');
          revealed = true;
          setStatus('Revealed');
        } else {
          // Second (and subsequent) clicks: copy to clipboard
          var ok = await copyText(addr);
          setStatus(ok ? 'Copied!' : 'Copy failed');
          if (ok) btn.textContent = 'Copied ✓';
          setTimeout(function(){ btn.textContent = 'Copy again'; }, 1200);
        }
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
