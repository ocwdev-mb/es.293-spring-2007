---
content_type: page
description: ''
learning_resource_types: []
ocw_type: CourseSection
parent_title: SP.285
parent_type: CourseSection
parent_uid: 3ac1aa36-8b07-38f8-f202-a90f68c5443e
title: Master/Slave IR Control
uid: 59180ea3-56a1-8194-eb69-1117c8fae4ea
video_metadata:
  youtube_id: null
---

{{% resource_link 3ac1aa36-8b07-38f8-f202-a90f68c5443e "SP.285" %}}

Chad Keever, {{% resource_link fbc62d3a-ff37-9c99-e4e2-4539d9bbd673 "Projectile Launcher" %}}  
Kendall McConnel, {{% resource_link 57a2e970-39bf-2e69-1831-a4194ccc949e "Control of a Plotter" %}}  
Jonah Elgart, {{% resource_link 71bf2a2a-5a80-abb9-6b63-accb8c525add "Guidance by IR Beacon" %}}  
Miki Havlickova, {{% resource_link 5a413b50-41e0-9e4d-b05a-f275e8a55fac "IR Remote Control" %}}  
Jessica Bowles-Martinez, {{% resource_link c11bc4ae-844d-f4cc-4b26-d80131ee8878 "Guidance by Light" %}}  
Matt Seegmiller, Master/Slave IR Control  
Jitin Asnaani, {{% resource_link 2a995065-ab60-fabb-f9ef-0c9861286f50 "Invertible Robot" %}}

* * *

**Matt's IR Controlled Tank**

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}


{{< resource 21b3b479-653d-272b-6e45-bc968e7b8438 >}}

This is a side view of the tank.


{{< tdclose >}}
{{< tdopen >}}
For my final project in {{% resource_link 3ac1aa36-8b07-38f8-f202-a90f68c5443e "SP.285" %}}, I built an infrared controlled tank out of Legos. The basic idea is that one board acts as a slave and takes commands from another board, which acts as master, through IR signals. These signals are sent in 32 bit bursts along some carrier frequency from the master board to the slave board.
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}


{{< resource 23aa6334-f495-cc1f-3afb-482c2892b653 >}}

The differentials of the tank as seen from below.


{{< tdclose >}}
{{< tdopen >}}
This tank is driven by two motors, one to control forward and reverse motion and the other to control turning. This is accomplished by connecting two differentials so that on one side, the outputs go in the same direction and on the other they go in opposite directions. This is a little hard to understand, unless you know something about differentials already. To help illustrate what is meant by this, there is a picture of the two differentials on my tank below.
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}


{{< resource 99b14c3d-e3e7-4259-3eb2-e1d92bd12760 >}}

This is the remote.


{{< tdclose >}}
{{< tdopen >}}
The other component of this project is the remote. It is basically an old remote from an RC car that has been taken apart and wired so that its sensors can be plugged into a board. The program that runs on this board checks the values of the sensors corresponding to the forward/backward and side-to-side motors. Based on these values, it sends signals to the board on the tank instructing it as to how fast to drive the motors at.
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}