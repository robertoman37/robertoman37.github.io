<div style="text-align: right">Robert Hoeh<br>
Rotating Rolls Unrolling Lab Report<br>
Ms. Li<br>
11/29/22</div>

## Procedure
First calculate the time required for the dropped roll to fall given height as H, and dropped from rest:
$$v_0 = 0$$
$$a = g$$
$$\Delta x = H$$
$$\therefore H = v_0t+\frac{1}{2}gt_{dropped}\ ^2$$
$$H = \frac{1}{2}gt_{dropped}\ ^2$$
$$t_{dropped}=\sqrt{\frac{2H}{g}}$$
This derivation can also be used similarly to find the time required for the unwravelled roll to fall, however we must use different variables because the height and acceleration are different values. Instead we use h to represent the height and a instead of g because the acceleration is different:
$$t_{unwravelled}=\sqrt{\frac{2h}{a}}$$
Next, because we are solving for when the times are the same, we set the two different times equal to each other.
$$\sqrt{\frac{2H}{g}}=\sqrt{\frac{2h}{a}}$$
$$\frac{2H}{g}=\frac{2h}{a}$$
$$\frac{2H}{2h}=\frac{g}{a}$$
$$\frac{H}{h}=\frac{g}{a}$$
Next we need to find the linear acceleration of the of the unrolling roll. We can do this by using the parallel-axis theorem and finding the moment of inertia. We use r for the inner radius, R for the outer radius, and M for the mass of the toilet paper roll.
$$I = \frac{1}{2}M(r^2+R^2)$$
$$I = \frac{1}{2}M(r^2+R^2) + MR^2=\frac{1}{2}M(r^2+3R^2)$$
Next, we use newton's third law for rotational motion so that later we can find the angular acceleration. We can identify the net torque as MgR as well.
$$\tau_{net}=I\alpha$$
$$\alpha = \frac{\tau_{net}}{I}$$
$$\alpha = \frac{MgR}{\frac{1}{2}*M(r^2+3R^2)}$$
$$\alpha = \frac{2gR}{r^2+3R^2}$$
Then we can find the linear acceleration by using the equation $a=\alpha R$
$$a = \alpha R$$
$$ \ = \frac{2gR^2}{r^2+3R^2}$$
lastly we can use the equation we defined above, $\frac{H}{h}=\frac{g}{a}$ to finally find the ratio of the heights.
$$\frac{H}{h}=\frac{g}{a}$$
$$ = \frac{g}{\frac{2gR^2}{r^2+3R^2}}$$
$$ = \frac{r^2+3R^2}{2R^2}$$
$$ = \frac{r^2}{2R^2}+\frac{3}{2}$$
Then, we use the radii of the toilet paper rolls to find the final ratio
$$\frac{H}{h} = \frac{0.02^2}{2*0.06^2}+\frac{3}{2}$$
$$ = \frac{0.0004}{2*0.0036}+\frac{3}{2}$$
$$ = \frac{0.0004}{0.0072}+\frac{3}{2}$$
$$ = \frac{4}{72}+\frac{3}{2}$$
$$ = \frac{14}{9}$$

## Data table
|Height of Dropped Roll|Height of Unravelled Roll|Hit the Ground at the Same Time? (Within Error)|
|:---:|:---:|:--:|
|1.4 meters|0.9 meters|too close to call|
|1.5 meters|1 meter|yes|
|2.1 meters|1.35 meters|yes|

## Conclusion
The ratio between the heights of the dropped toilet paper roll and the unwravelled toilet paper roll is 14 to 9 or approximately 1.56 based on the rolls we used during the experiment. In general, the ratio of a dropped object compared to an unravelled object of similar mass and radius is roughly 3/2 plus the inner radius squared divided by two times the outer radius squared. 

## Analysis
1. Parallel Axis Theorem<br>
The parallel axis theorem is a formula that allows you to calculate the moment of inertia at any point on a rigid body by comparing it to a parallel axis through the center of mass. The equation is stated as $I=I_{cm}+md^2$, where $I$ is the moment of inertia for the new axis of rotation, $I_{cm}$ is the moment of intertia for the center of mass, $m$ is the mass of the object, and $d$ is the perpendicular distance from the initial axis of rotation.
2. The parallel axis theorem applies to the unraveling roll because the axis of rotation (in this case) is not through the center of mass, rather the edge of the toilet paper roll touching the wall. Therefore we used the parallel axis theorem to calculate the moment of inertia at the edge of the roll, not the center.
3. The moment of inertia is different for a hollow cylinder with thin walls vs. thick walls with the same mass because the mass is distributed differntly throughout it. In the hollow cylinder with thin walls, the mass is very closely the same 