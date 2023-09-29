---
content_type: page
description: ''
learning_resource_types: []
ocw_type: CourseSection
parent_title: SP.285
parent_type: CourseSection
parent_uid: 3ac1aa36-8b07-38f8-f202-a90f68c5443e
title: Control of a Plotter
uid: 57a2e970-39bf-2e69-1831-a4194ccc949e
video_metadata:
  youtube_id: null
---

{{% resource_link 3ac1aa36-8b07-38f8-f202-a90f68c5443e "SP.285" %}}

Chad Keever, {{% resource_link fbc62d3a-ff37-9c99-e4e2-4539d9bbd673 "Projectile Launcher" %}}  
Kendall McConnel, Control of a Plotter  
Jonah Elgart, {{% resource_link 71bf2a2a-5a80-abb9-6b63-accb8c525add "Guidance by IR Beacon" %}}  
Miki Havlickova, {{% resource_link 5a413b50-41e0-9e4d-b05a-f275e8a55fac "IR Remote Control" %}}  
Jessica Bowles-Martinez, {{% resource_link c11bc4ae-844d-f4cc-4b26-d80131ee8878 "Guidance by Light" %}}  
Matt Seegmiller, {{% resource_link 59180ea3-56a1-8194-eb69-1117c8fae4ea "Master/Slave IR Control" %}}  
Jitin Asnaani, {{% resource_link 2a995065-ab60-fabb-f9ef-0c9861286f50 "Invertible Robot" %}}

* * *

{{< resource 8c1052b0-903d-fd7b-f48a-68824e2bcaa7 >}}

Hello! My name is Kendall McConnel and this webpage is devoted to my final project for {{% resource_link 3ac1aa36-8b07-38f8-f202-a90f68c5443e "SP.285" %}}, a seminar on Robotics and Mechatronics.

First, a little bit about the class...

The Robotics and Mechatronics seminar is taught in ESG by two spiffy fellows by the names of Eric Smith and Max "Ben" Davis. The course involves tinkering with Legos, motors, sensors and programming to create robots that can pick up, run away from light, or even follow a line. For the first part, I learned about how to make a robot and what goes into making it work. Max and Eric ran lectures on topics related to the robots (sensors, electronics, etc) and also helped us work through and learn about what works best. For the latter part, I worked on a project (this one) which reflects my interest in programming specifically.

And now, a bit about my project!

I chose to work with a plotter (which came with two sensors and two motors) my plan was to get the plotter to go to a point as accurately as possible, and, if time allowed, to draw simple objects.

The main problem of this particular plotter was that because it was so smooth (barely any friction) it would overshoot and wouldn't be very accurate. So, part of my project was to learn a bit about control theory and apply and test different methods to see what worked best.

To sum up my experience with my plotter, I tinkered with different functions of distance to see what would get the plotter to the designated point as quickly and as accurately as possible. First, I wrote up readpt function that would give out the x coordinate on the plane. Then, I tried different gotox functions. Initially, I tried a simple distance function (but when the motor runs too slow, it doesn't move and sounds horrible so.) then I experimented with different sections where the motor would run at different speeds (i.e. at the distance for speed, and then, when it got close enough, (within a certain distance) it would run at a minimum speed.) I still had a decent degree of overshoot and some bugs, but after awhile I created a distance function that worked. To make the geometrical figures that my plotter eventually drew, I created a line function (that makes a diagonal line out of smaller lines) for a complete record of what I did on a day to day basis, check out my journals ({{% resource_link "e47a347f-5a44-89c9-5fea-0698038b2045" "TXT" %}}). And, if you're **really** curious, you can check out my program ({{% resource_link "9b8889e8-d59f-30ff-c93c-d599e7cbc6de" "C" %}}).

And now, some pictures of my monster (I mean, my... uh.. creation)

{{< resource 88bf8c15-4581-31b5-5f29-9ff044a7c2df >}} {{< resource 8914289a-8b10-6752-7d89-5cf25bf83ad1 >}} {{< resource 779a233f-a680-578f-97f1-fea72dbe4c61 >}}