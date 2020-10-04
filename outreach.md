---
layout: page
title: Outreach
description: 'Past community programs and resources'
nav-menu: true
image: "img/misc/breadboard.jpg"
weight: 3
---

<section id="one">
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.accordion {
  background-color: transparent;
  color: white;
  cursor: pointer;
  padding: 25px;
  width: 100%;
  border: none;
  text-align: left;
  outline: none;
  font-size: 20px
  height: 15px;
  display: flex;
  transition: 0.4s;
  white-space: normal;
  line-height: 20px;
}
.active, .accordion:hover {
  background-color: white;
  color: #242943;
}
@media screen and (min-width: 651px) {
  .accordion {
    font-size: 20px;
  }}
  @media screen and (max-width: 650px) {
  .accordion {
    font-size: 10px;
  }
.panel {
  padding: 0 18px;
  display: none;
  background-color: transparent;
  color: white;
  overflow: hidden;
}
</style>
</head>
<div class="inner">
        <header class="major">
            <h1>Outreach</h1>
        </header>
       <button class="accordion" >CTE</button>
             <div class="panel">
         <p><ul>
         <li><a href="https://github.com/ERC-BPGC/cte-archive/tree/master/Sem2_19-20"><h3>Robotics: Control and Automation</h3></a></li>
         <b>Duration: SEMESTER 2</b><br>
         This course provides detial insight into automation and control aspects involved in Robotics.The content of the course includes
         ROS basics, ROS Simulations, MoveIT, Autonomous navigation and OpenCV.<hr>
         <li><a href="https://github.com/ERC-BPGC/cte-archive/tree/master/Sem1_19-20"><h3>Introduction to Robotics</h3></a></li>
         <b>Duration: SEMESTER 1</b><br>
         This course is to provide a basic idea about the feild of Robotics and different areas involved in it. The content of the course includes Mechanical aspects in Robotics, Arduino programming and sensor, Python, Intro to ROS, etc.
         </ul> </p>
        </div><br><br>
        <button class="accordion" >QSTP (Quark SUmmer Term Project)</button>
             <div class="panel">
         <p><ul>
         <li><a href="https://github.com/abhidxt299/QSTP-Introduction-to-Mechatronics"><h3>Introducion to Mechatronics</h3></a></li>
         <b>Duration: SUMMER 2020</b><br>
         Mechatronics is a multidisciplinary field, encompassing Electronics, Robotics and Computer and Control Syetem engineering.This course is to familiarise people with fundamentals and concepts related to basic mechatronic devices. The content of the course includes Arduino programming and Sensors, CAD designing and Matlab and Simulink.<hr>
         <li><a href="https://github.com/adbidwai/QSTP-Robotics_Automation_using_ROS"><h3>Robotics Automation using ROS</h3></a></li>
         <b>Duration: SUMMER 2020</b><br>
         Automation and Control in Robotics is a fast growing field with exciting innovations coming out with a rapid pace. This course aims to familiarise you with the basic tools and techniques that are at the core of such developments. The content of the course includes basics of Python, ROS, Gazebo Simulatons, Path Planning and writing a Controller.<hr>
         <li><a href="https://github.com/hardesh/QSTP-Introduction_to_ROS"><h3>Introduction to ROS</h3></a></li>
         <b>Duration: SUMMER 2019</b><br>
         This project based course was aimed at teaching basic usage and application of ROS
         </ul> </p>
        </div>

        

</div>
</section>
<script>
var acc = document.getElementsByClassName("accordion");
var i;

for (i = 0; i < acc.length; i++) {
  acc[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var panel = this.nextElementSibling;
    if (panel.style.display === "block") {
      panel.style.display = "none";
    } else {
      panel.style.display = "block";
    }
  });
}
</script>