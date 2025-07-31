---
layout: project
type: project
image: img/tutelage/tutelage-square.png
title: "Tutelage"
date: 2025
published: true
labels:
  - Java
  - FTLH
  - HTML
  - GitHub
summary: "A half of a semester long project worked on by myself and two other Computer Science students for CSC 330: Software Engineering.  I worked on all functions and interactions related to the tutors."
---

<img src="https://github.com/user-attachments/assets/b5a603ba-0ca0-4fc9-8754-d047e628b952" alt="Tutelege" width="655" height="195" />

<br>

Tutelage is a Craigslist-style website with the sole intention of allowing aspiring tutors to connect with students, either for a commission or for free, using whatever method they prefer—such as Discord, phone calls, Zoom, or in-person sessions.

This project was developed by myself and two other Computer Science students for CSC 340: Software Engineering.  Our initial goal was to build a full-stack application that could interact with a database and had functionality for three user types: providers (tutors), customers (students), and administrators.

I proposed the concept and then took responsibility for building the tutor-facing features and pages drawing from experience in a previous class where I had developed a database-integrated system for a bookstore.  I focused on implementing database interactions and user functionality using Spring Boot, Java, FTLH,
and HTML.

Once the tutor section was complete, I then closely collaborated with the teammate working on the student-facing portion.  We would integrate our systems by linking shared database tables and refining core functionality for transactions between the providers and customers.  This collaboration was invaluable as a learning experience—we worked through integration challenges, sharing and explaining code to one another, and managed real-time problem solving under tight deadlines and frequent updates to the professor and class.

After completing our respective sections, we worked with our teammate assigned to the admin interface and extended shared functionality and knowledge to work alongside his portion of the project.  In the final phase, we polished the web design and presented the finished project to the class.

While not the most technically complex project I've completed, Tutelage stands out to be one that I'm most proud of.  It solidified both my technical foundation and my ability to collaborate effectively within a development team - skills that are essential in real-world software engineering.

Below this I will put an excerpt from our ReadMe file that includes the functions applicable for the Student, Tutor, and Admin that were successfully added:


<hr>

<pre>
## App Functions:
Student (Customer)
- Can create/modify their student profile through user settings for personlization
- The user can join public scheduled tutoring classes
- Can lookup for any available subjects
- Can pick from a list of available tutors
- Give tutors a review
- The customer can subscribe for a one-on-one scheduled tutoring session

Tutor (Provider)
- Can create/modify their tutor profile
- Can create listings for their tutor services
- Can update their listing schedule and/or rates
- Can delete posted listings
- Can message customers 

SysAdmin
- Can approve/ban tutors and students
- Can view and delete listings
- Can view and delete comments/reviews
- Can view usage statistics
- Can view commerce related information for an effective paper trail
</pre>

<hr>

Source: <a href="https://github.com/anglopp/CSC-340-Group-Project"><i class="large github icon "></i>anglopp/CSC-340-Group-Project</a>
