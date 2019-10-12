---
layout: post
title:  "Campusboard-App"
categories: jekyll update
github: "https://github.com/Informatik-HS-KL/Campusboard-App"
confidential: true
---

In this project I contributed to the further development of the official mobile application of the University of Applied Sciences Kaiserslautern - as a member of a group of 4 people.<br>

The group was split in 2 teams of 2 people respectively, each working on a different task.
My team was responsible for implementing the functionality of capturing present students in exams by scanning their student license with nfc or it's barcode with the smartphone camera.
This view is the result of our efforts:

![overview](/assets/images/cambusboard-app2.PNG){:height="784px" width="427px"}<br>

It displays all students that have applied online for the exam <span style="color: red">3-5)</span>. The application fetches this information from an internal database.
Furthermore, it indicates if an applied student is already saved in the database as present <span style="color: red">3)</span>, saved as present in the mobile application (but not in the database) <span style="color: red">4)</span> or neither of both <span style="color: red">5)</span><br>

<span style="color: red">6)</span> and <span style="color: red">8)</span> are the tools with which present students can be recorded. <span style="color: red">6)</span> opens a barcode scanner while <span style="color: red">8)</span> activates near field communication both of which allow to record a student as present using only his student license.
<br>
In the case of an unexpected error - such as a student license not being recognized as such by the application - the status of a single student can also edited manually by tapping the respective name in the list view. For this to be more efficient - especially in exams with a lot of students - students can be searched by name, student number or field of study (which are all being displayed in the list as well).
<br>
<span style="color: red">1)</span> lets the user manage the list view. He can configure the list to show only uploaded, scanned, unscanned or any combination of the aforementioned.
<br>
<span style="color: red">9)</span> represents the ratio of scanned to applied students as well as uploaded to applied students. This allows the professor or his/her assistant to gain an overview in one glance.
<br>
In order to push the current status of all students to the database, the user has to press button <span style="color: red">7)</span>.
<br>
Finally, since this is a new functional introduction to an exisiting application, which is already being used by a broad spectrum of students and professors alike, a tutorial has been embedded, which can be started by pressing button <span style="color: red">2)</span>. It displays a slideshow of all essential functionalities - basically enclosing the information that is presented here. 



