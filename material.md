---
layout: default
title: "Course Material"
category: "material"
---

<!--
IMPORTANT: please don't edit material.md directly.
Instead, edit material.csv, adding a new row for each item you
want to add, and then regenerate materials.md by running
the command

  ./gen_materials_page.rb > material.md

Then add, commit, and push both material.csv and material.md.
-->

You can click on the header for a specific week to expand or collapse
the materials for that week.

<button type="button" id="week_1_toggle" class="week_control_button">Week 1 (5-Jun to 9-Jun)</button>
<div id="week_1" class="collapsible">
<table>
  <thead>
    <tr>
      <th></th>
      <th>Day 1 (5-Jun)</th>
      <th>Day 2 (7-Jun)</th>
      <th>Day 3 (9-Jun)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Videos</td>
      <td><a class='external' target='_blank' href='https://jh.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=82661007-f96c-473e-8377-af8e015e24f0'>Course intro</a><br><a class='external' target='_blank' href='https://jh.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=1273cccc-b312-47d4-802a-ae2200fefc22'>Linux, ugrad accounts</a><br><a class='external' target='_blank' href='https://jh.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=1a42038f-6e6e-43cb-958a-ae230027ad23'>Hello world program in C</a><br><a class='external' target='_blank' href='https://jh.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=c7fc4118-f301-40bb-8693-ae230027ac09'>C basics</a></td>
      <td><a class='external' target='_blank' href='https://jh.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=d7af51c6-fffc-4c79-9e8e-ae230027adb4'>Editors (emacs)</a><br><a class='external' target='_blank' href='https://jh.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=7f332c5e-6ad8-4ff8-a702-ae23002793cf'>Git</a><br><a class='external' target='_blank' href='https://jh.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=4c4f67dd-677c-40d9-8bbc-ae230027ac60'>Submission workflow</a><br><a class='external' target='_blank' href='https://jh.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=45b14d44-3d4e-4fd7-b0c0-ae230027aef2'>Logical operators, control flow</a></td>
      <td><a class='external' target='_blank' href='https://jh.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=58f4d402-fd0d-4868-b805-ae230027ab93'>Arrays, ASCII</a><br><a class='external' target='_blank' href='https://jh.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=06a4f1da-f6a1-4212-b686-ae230027ab33'>C strings</a><br><a class='external' target='_blank' href='https://jh.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=ae149930-15ce-460c-a2df-ae230027aac0'>File I/O, assert, math functions</a><br><a class='external' target='_blank' href='https://jh.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=1de2958b-f8b8-4fae-ac47-ae230027aa77'>Writing functions, command line arguments</a></td>
    </tr>
    <tr>
      <td>Slides</td>
      <td><a href='slides/day01_intro.pdf'>Course intro</a><br><a href='slides/day01_linux_basics.pdf'>Linux, ugrad accounts</a><br><a href='slides/day02_hello_world_c.pdf'>Hello world program in C</a><br><a href='slides/day02_c_basics.pdf'>C basics</a></td>
      <td><a href='slides/day03_editors.pdf'>Editors (emacs)</a><br><a href='slides/day03_git.pdf'>Git</a><br><a href='slides/day03_submission_workflow.pdf'>Submission workflow</a><br><a href='slides/day04_control_flow.pdf'>Logical operators, control flow</a></td>
      <td><a href='slides/day05_arrays.pdf'>Arrays</a><br><a href='slides/day05_c_strings.pdf'>C strings</a><br><a href='slides/day06_fileio_assertion_math.pdf'>File I/O, assert, math functions</a><br><a href='slides/day06_functions_command_line_arguments.pdf'>Writing functions, command line arguments</a></td>
    </tr>
    <tr>
      <td>Recap<br>Questions</td>
      <td><a href='questions/day01.html'>Day 1</a><br><a href='questions/day02.html'>Day 2</a></td>
      <td><a href='questions/day03.html'>Day 3</a><br><a href='questions/day04.html'>Day 4</a></td>
      <td><a href='questions/day05.html'>Day 5</a><br><a href='questions/day06.html'>Day 6</a></td>
    </tr>
    <tr>
      <td>Exercise</td>
      <td><a href='exercise/ex01.html'>Exercise 1</a><br><a href='exercise/ex02.html'>Exercise 2</a></td>
      <td><a href='exercise/ex03a.html'>Exercise 3-A</a><br><a href='exercise/ex03b.html'>Exercise 3-B</a><br><a href='exercise/ex04.html'>Exercise 4</a></td>
      <td><a href='exercise/ex05.html'>Exercise 5</a><br><a href='exercise/ex06.html'>Exercise 6</a></td>
    </tr>
    <tr>
      <td>Additional<br>Resources</td>
      <td><a class='external' target='_blank' href='https://cs.jhu.edu/~joanne/unix.html'>Unix/Linux Tutorial</a><br><a class='external' target='_blank' href='https://cs.jhu.edu/~joanne/unixRC.pdf'>Unix/Linux Reference Card</a><br><a href='resources/github-ssh.html'>Github SSH key setup</a><br><a class='external' target='_blank' href='https://www.onlinegdb.com/online_c_compiler'>Online C compiler</a></td>
      <td><a class='external' target='_blank' href='https://www.gnu.org/software/emacs/refcards/pdf/refcard.pdf'>Emacs reference card</a><br><a class='external' target='_blank' href='https://www.openvim.com/'>Interactive Vim tutorial</a><br><a class='external' target='_blank' href='https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf'>Git cheatsheet</a></td>
      <td></td>
    </tr>
    <tr>
      <td>Lecture<br>Slides</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Recorded<br>Sessions</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>
</div>
<script type="text/javascript">
  // Create and register a click handler for button clicks to expand/contract
  // specified content div
  function registerClickHandler(content, is_active) {
    //console.log("Registering click handler for " + content.id);

    content.style.display = is_active ? "block" : "none";

    var button_id = content.id + "_toggle";
    //console.log("button_id=" + button_id);

    var button = document.getElementById(button_id);

    button.addEventListener("click", function() {
      button.classList.toggle('active');
      //console.log("content.style.display="+content.style.display);
      if (content.style.display == 'block') {
        content.style.display = 'none';
      } else {
        content.style.display = 'block';
      }
    });

    if (is_active) {
      button.classList.add('active');
    }
  }

  document.addEventListener('DOMContentLoaded', function() {
    var active_week_id = 'week_1';

    var content_divs = document.getElementsByClassName("collapsible");
    for (i = 0; i < content_divs.length; i++) {
      var content = content_divs[i];

      var is_active = (content.id == active_week_id);
      registerClickHandler(content, is_active);
    }
  });
</script>
