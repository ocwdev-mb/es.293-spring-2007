---
content_type: page
description: ''
learning_resource_types: []
ocw_type: CourseSection
parent_title: SP.285
parent_type: CourseSection
parent_uid: 3ac1aa36-8b07-38f8-f202-a90f68c5443e
title: Guidance by IR Beacon
uid: 71bf2a2a-5a80-abb9-6b63-accb8c525add
video_metadata:
  youtube_id: null
---

{{% resource_link 3ac1aa36-8b07-38f8-f202-a90f68c5443e "SP.285" %}}

Chad Keever, {{% resource_link fbc62d3a-ff37-9c99-e4e2-4539d9bbd673 "Projectile Launcher" %}}  
Kendall McConnel, {{% resource_link 57a2e970-39bf-2e69-1831-a4194ccc949e "Control of a Plotter" %}}  
Jonah Elgart, Guidance by IR Beacon  
Miki Havlickova, {{% resource_link 5a413b50-41e0-9e4d-b05a-f275e8a55fac "IR Remote Control" %}}  
Jessica Bowles-Martinez, {{% resource_link c11bc4ae-844d-f4cc-4b26-d80131ee8878 "Guidance by Light" %}}  
Matt Seegmiller, {{% resource_link 59180ea3-56a1-8194-eb69-1117c8fae4ea "Master/Slave IR Control" %}}  
Jitin Asnaani, {{% resource_link 2a995065-ab60-fabb-f9ef-0c9861286f50 "Invertible Robot" %}}

* * *

Hi, I'm Jonah Elgart and for my final project in {{% resource_link 3ac1aa36-8b07-38f8-f202-a90f68c5443e "SP.285" %}}, a robotics and mechatronics class taught in [ESG](http://esg.mit.edu/) (Experimental Study Group), I created a Lego robot that chases or flees an infrared beacon.

My robot car is very simple. It has two wheels, each connected to its own motor. The two motors are driven at different speeds to steer the car. The back wheel is mounted on a really cool caster that I built with Eric (one of the instructor dudes).

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}


{{< resource 509414d7-3f51-a549-2ca7-1d004033ae32 >}}

My robot.


{{< tdclose >}}
{{< tdopen >}}


{{< resource eeb16f95-2249-7425-247a-4c719c3e8e01 >}}

The car.


{{< tdclose >}}
{{< tdopen >}}


{{< resource 6486d339-3749-f245-1fac-559c8233334d >}}

The car's rear side.


{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}


{{< resource ea38ec08-f85f-9d7f-fe75-47077661707c >}}

Infrared transmitter.


{{< tdclose >}}
{{< tdopen >}}
An infrared signal is broadcasted from a transmitter hooked up to a handyboard (one of those circuity things which is a minicomputer).
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}


{{< resource 131a2a83-629e-8edb-0af8-719b986fdfac >}}

Infrared receiver.


{{< tdclose >}}
{{< tdopen >}}
The signal is detected by the tower, which consists of three directional infrared receiver doohickeys, oriented in three quadrants.
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Click "code" ({{% resource_link "a5282be5-0ae5-c190-eb88-b1d978c7bf9d" "C" %}}) to see the IC code I wrote to make the robot flee or chase the signal. To change from flee to chase you simply reverse the polarity of the motors.