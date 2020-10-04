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
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.accordion {
  box-shadow: 0 0px 0px;
  background-color: transparent;
  color: white;
  cursor: pointer;
  padding: 25px;
  width: 100%;
  border: none;
  text-align: left;
  outline: none;
  font-size: 20px;
  height: 20px;
  transition: 0.4s;
  line-height: 0px;
}
.active, .accordion:hover {
  box-shadow: 0 2px 3px;
  background-color: #242943;
  color: #FFF;
  z-index: 100;
}
@media screen and (min-width: 651px) {
  .accordion {
    font-size: 20px;
  }}
  @media screen and (max-width: 650px) {
  .accordion {
    font-size: 10px;
    height: 15px;
    line-height: 5px;
  }}
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
       <button class="accordion" >CTE<i class="accordion-dropdown fa fa-caret-down" style="float:right; line-height:5px;"></i></button>
             <div class="panel">
         <p><ul>
         <li><h3>Robotics: Control and Automation <a href="https://github.com/ERC-BPGC/cte-archive/tree/master/Sem2_19-20" target="blank"><i class="fa fa-link" aria-hidden="true" style="font-size:16px; padding-left:6px;" ></i></a></h3></li>
         <h5>Jan 2020 - May 2020</h5>
         This course provides detial insight into automation and control aspects involved in Robotics.The content of the course includes
         ROS basics, ROS Simulations, MoveIT, Autonomous navigation and OpenCV.<hr>
         <li><h3>Introduction to Robotics<a href="https://github.com/ERC-BPGC/cte-archive/tree/master/Sem1_19-20" target="blank"><i class="fa fa-link" aria-hidden="true" style="font-size:16px; padding-left:6px;" ></i></a></h3></li>
         <h5>September 2019 - December 2019</h5>
         This course is to provide a basic idea about the feild of Robotics and different areas involved in it. The content of the course includes Mechanical aspects in Robotics, Arduino programming and sensor, Python, Intro to ROS, etc.
         </ul> </p>
        </div><br><br>
        <button class="accordion" >QSTP (Quark SUmmer Term Project)<i class="accordion-dropdown fa fa-caret-down" style="float:right; line-height:5px;"></i></button>
             <div class="panel">
         <p><ul>
         <li><h3>Introducion to Mechatronics<a href="https://github.com/abhidxt299/QSTP-Introduction-to-Mechatronics" target="blank"><i class="fa fa-link" aria-hidden="true" style="font-size:16px; padding-left:6px;" ></i></a></h3></li>
         <h5>Summer 2020</h5>
         Mechatronics is a multidisciplinary field, encompassing Electronics, Robotics and Computer and Control Syetem engineering.This course is to familiarise people with fundamentals and concepts related to basic mechatronic devices. The content of the course includes Arduino programming and Sensors, CAD designing and Matlab and Simulink.<hr>
         <li><h3>Robotics Automation using ROS<a href="https://github.com/adbidwai/QSTP-Robotics_Automation_using_ROS" target="blank"><i class="fa fa-link" aria-hidden="true" style="font-size:16px; padding-left:6px;" ></i></a></h3></li>
         <h5>Summer 2020</h5>
         Automation and Control in Robotics is a fast growing field with exciting innovations coming out with a rapid pace. This course aims to familiarise you with the basic tools and techniques that are at the core of such developments. The content of the course includes basics of Python, ROS, Gazebo Simulatons, Path Planning and writing a Controller.<hr>
         <li><h3>Introduction to ROS<a href="https://github.com/hardesh/QSTP-Introduction_to_ROS"><i class="fa fa-link" aria-hidden="true" style="font-size:16px; padding-left:6px;" ></i></a></h3></li>
         <h5>Summer 2019</h5>
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
      this.getElementsByClassName('accordion-dropdown')[0].className = "accordion-dropdown fa fa-caret-down";
    } else {
      panel.style.display = "block";
      this.getElementsByClassName('accordion-dropdown')[0].className = "accordion-dropdown fa fa-caret-up";
    }
  });
}
</script>