---
layout: essay
type: essay
title: Design Patterns
date: 2022-04-28
labels:
  - Design Patterns
  - Software Engineering
---

## “What are design patterns?”

<img src="https://res.cloudinary.com/practicaldev/image/fetch/s--xGPUOCiI--/c_imagga_scale,f_auto,fl_progressive,h_900,q_auto,w_1600/https://dev-to-uploads.s3.amazonaws.com/uploads/articles/ebdnqnmv3qqc16jzlkzs.jpg" width="700" height="500">

Design patterns is an often used term in the realm of software engineering, referencing the reuse of code that is used to solve a known issue in the development of a project. This makes the process more smooth and makes writing code with similar functionality a lot simpler, almost like a template. Having a template for a general idea comes with it's pros and cons, an example of this is using a large, complex template for a program that will only use a fraction of it's capabilities. And on the flip side, having no template at all and building similar components from scratch every single time is quite time consuming. However the use of a template does not mean that the program is reliable 100% of the time, or is able to be used in each and every scenario.

## “What design patterns have you used in your own code?”

In a recent development I assisted in developing, my group had a sit down to discuss the functionality of certain components that would be reused over and over again in our program. For this project we needed to create a system that would allow users to create accounts and add details to their profile that would put them out on the job market for companies to recruit. We generally laid out the components needed for the database, which was: personal information, education, job experience, and projects. For each of these we separate databases that held the data and assigned it to a single user. As well as different files to add the information and insert it into it's prospective database.
