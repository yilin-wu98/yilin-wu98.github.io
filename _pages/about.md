---
layout: about
title: About
permalink: /
subtitle: 

profile:
  align: right
  image: yilinwu.jpg
  image_circular: true # crops the image to make it circular
  more_info: >
    <p style="font-size: 16px; font-family: Roboto, sans-serif;">PhD student @ RI, SCS, CMU</p>
    <p style="font-size: 16px; font-family: Roboto, sans-serif;">yilinwu [at] andrew [dot] cmu [dot] edu</p>

news: true # includes a list of news items
talks: true # includes a list of talks from _data/talks.yml
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page
---


I am a final-year Ph.D. student at Intent Lab in CMU Robotics Institute, advised by <a href="https://www.cs.cmu.edu/~abajcsy/">Prof. Andrea Bajcsy</a>. I received my Master from Stanford CS, supervised by <a href="https://dorsa.fyi/">Prof. Dorsa Sadigh</a>. In my undergrad, I was also fortunate to work with <a href="https://www.lerrelpinto.com/">Prof. Lerrel Pinto</a> and <a href="https://people.eecs.berkeley.edu/~pabbeel/">Prof. Pieter Abbeel</a>.

<strong>I am on the industry job market this year.</strong> Feel free to contact me if you feel there might be a good fit.

For industry experiences, I have had great internships at Nvidia Seattle Robotics Lab and the Amazon Frontier AI &amp; Robotics Lab.

My research interest lies in helping generalist robot policies adapt to users and environments while preserving their broad capabilities and their ability for continual learning. I have been addressing this problem from several perspectives: using world models and VLMs for inference-time steering; using tactile information and learning to condition on memory to address partial observability; and uncertainty-driven, parameter-efficient policy finetuning to minimize the cost of human interaction during deployment.

<button class="btn btn-sm btn-outline-primary bio-toggle" type="button" data-text-collapsed="Show more about my background" data-text-expanded="Show less">Show more about my background</button>

<div class="bio-more bio-hidden" markdown="1">
Earlier at CMU, I was fortunate to work with <a href="https://davheld.github.io/">Prof. David Held</a> on generalizable methods for long-horizon contact-rich manipulation. During my Master at Stanford, I focused on assistive feeding and bimanual manipulation. I also worked with <a href="https://jxwuyi.weebly.com/">Prof. Yi Wu</a> from Tsinghua University at Shanghai Qi Zhi Institute on reinforcement learning and self-imitation, and in my undergrad worked on reinforcement learning for deformable object manipulation.

More broadly, my research centers around overcoming the fundamental <em>embodiment gap</em> that limits the application of foundation models to robotics. By grounding high-level semantic reasoning in the continuous dynamics of the physical world, I want to build robots that can learn, reason, and act capably in human-centered environments, enhancing their generalization and robustness through runtime alignment and continual learning.
</div>

<style>
  .bio-hidden {
    display: none;
  }
  .bio-toggle {
    margin: 0.5rem 0;
  }
</style>

<script>
  document.addEventListener("DOMContentLoaded", function () {
    document.querySelectorAll(".bio-toggle").forEach(function (btn) {
      btn.addEventListener("click", function () {
        const expand = btn.getAttribute("data-expanded") !== "true";
        document.querySelectorAll(".bio-more").forEach(function (el) {
          el.classList.toggle("bio-hidden", !expand);
        });
        btn.setAttribute("data-expanded", expand ? "true" : "false");
        btn.textContent = expand ? btn.dataset.textExpanded : btn.dataset.textCollapsed;
      });
    });
  });
</script>

