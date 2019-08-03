# Tutorial 0 - Basic Knowledge

By NaiChit Fung 2019/08/03

#### 0. Objective of Hardware

<img align="right" height="200" src=".\assets\FLF0LQLHEBNH7UI.LARGE.jpg">To Design and make prototype of electronics circuit

- To choose electronics component
  - To debug a failing circuit



#### 1. The (How to) Basics

##### 1.0 Basic electronics

There's few type of electronics component.
<table border="0" width = "100%">
<tr>
    <td>Resistors</td>
    <td align="center"><img height="130" src=".\assets\2785-03-1564812167285.jpg"><img height="130" src=".\assets\smd-resistor-500x500.jpg"></td>
</tr>
<tr>
    <td>Capacitor</td>
    <td align="center"><img height="130" src=".\assets\407684326c404052734_grande.jpeg"><img align="centre" height="130" src=".\assets\51968eb0ce395f352c000000.jpg"></td>
</tr>
<tr>
    <td>Inductor</td>
    <td align="center"><img height="130" src=".\assets\spoler.jpg"><img align="centre" height="130" src=".\assets\smd-inductors-500x500.png"></td>
</tr>
</table>

##### 1.1 Voltage

<img align="right" width="100" height="130" src=".\assets\E3444-1564765376829.png">The first things we are going to talk about will be voltage. 

When talk about voltage, assuming you have no electronic or electrical background, the first thing you may think, might be a high voltage warning. However, such warning might make people misinterpret how voltage works.

In Physics, voltage is also called electric potential "difference". Which also suggested that it's some kind of subtraction. Take an example, look at the following picture.![bird power line](assets/Screenshot_20190204-082427_Gallery.jpg)

Don't worry, no birds were harmed. Anyway, this is a very good demonstration of the importance of a reference. The power line those birds stood on probably operating over thousands of volt. However, birds won't be killed as there's no voltage difference on where they are standing.<img align="right" width="240" height="260" src=".\assets\avoidshocks016.jpg">

However, if you are being electrical shocked unluckily. During the process, you are actually creating a reference by putting your feet onto the ground as the ground you stand on and the ground of the power plug are generally connected. As a result, 220V induced between where you touch and the ground; as a result, current will flow through your body.

Let's use gravity as another example. A ball on a table will fall to the ground if you push out of the edge. However, if you don't push it to the edge, assuming the table is flat, it will remain on the table, as at the point of view of the ball, the table is its "GROUND". Or say it in another way, the best way to prevent something from falling, is to put it on the ground. Nothing will fall if it's on the ground at the first place. Even if it's happening on 28th floor.

Therefore, for voltage exist, you need to create a reference. A.K.A. a closed circuit (which means make the circuit form a loop).

##### 1.2 Current

Current is a measurement of how much charge is moving per second.

##### 1.2 Ohm's Law

Ohm's Law is a simple yet very important law in electrical and electronic engineering.
$$
V = IR
$$
While V stands for Voltage, I stands for current and R stands for resistance.![ohm's law](assets/zi3yac7jkxj21.jpg)

And this picture explain it perfectly.

There's an idiom says, "High voltage will kill". This idiom is not accurate. From the picture, volt only pushes current through resistance; the current (amp) is what going to flow through your body and burn it down. So, good kids don't try it at home.

##### 1.3 Power Calculation

The simplest way of calculating power, or average power:
$$
P = I^2R=\frac{V^2}{R}=VI
$$
