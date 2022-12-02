---
layout: default
title: Heron's Formula
nav_order: 3
parent: Unit 3
grand_parent: math
---
# Heron's Formula
Heron's Formula is a formula that can be used to find the area of a general triangle if you only know the sides of the triangle.
## Heron's Formula derivation
First, we start with the general area formula.
$$Area=\frac{1}{2}ab\sin{C}$$
Then, we manipulate this in an attempt to get rid of the $\sin$
$$Area^2=(\frac{1}{2})^2a^2b^2\sin^2{C}\\
Area^2=(\frac{1}{2})^2a^2b^2(1-cos^2{C})\\
Area^2=(\frac{1}{2})^2a^2b^2(1+cos{C})(1-cos{C})\\
Area^2=\frac{1}{2}ab(1+\cos{C})\frac{1}{2}ab(1-\cos{C})\\$$
We can simplify this further using the law of cosines ($\cos{C}=\frac{c^2-b^2-a^2}{-2bc}$)
$$Area^2=\Bigg(\frac{1}{2}ab\bigg(1+\frac{c^2-b^2-a^2}{-2ab}\bigg)\Bigg)\Bigg(\frac{1}{2}ab\bigg(1-\frac{c^2-b^2-a^2}{-2ab}\bigg)\Bigg)\\
Area^2=\Bigg(\frac{ab}{2}+\frac{ab}{2}*\frac{c^2-b^2-a^2}{-2ab}\Bigg)\Bigg(\frac{ab}{2}-\frac{ab}{2}*\frac{c^2-b^2-a^2}{-2ab}\Bigg)\\
Area^2=\bigg(\frac{ab}{2}+\frac{-c^2+b^2+a^2}{4}\bigg)\bigg(\frac{ab}{2}-\frac{-c^2+b^2+a^2}{4}\bigg)\\
Area^2=\bigg(\frac{2ab}{4}+\frac{-c^2+b^2+a^2}{4}\bigg)\bigg(\frac{2ab}{4}-\frac{-c^2+b^2+a^2}{4}\bigg)\\
Area^2=\frac{-c^2+a^2+2ab+b^2}{4}*-\frac{-c^2+a^2+2ab+b^2}{4}\\
Area^2=\frac{(a+b)^2-c^2}{4}*-\frac{(a+b)^2-c^2}{4}\\
Area^2=\frac{a+b+c}{2}*\frac{a+b-c}{2}*\frac{a-b+c}{2}*\frac{-a+b+c}{2}$$
Now we will put all of this under a square root and continue the derivation. Keep in mind that we will be using the half perimeter in this derivation. The formula for the half perimeter is $s=\frac{a+b+c}{2}$
$$Area=\sqrt{\frac{a+b+c}{2}*\frac{a+b-c}{2}*\frac{a-b+c}{2}*\frac{-a+b+c}{2}}\\
Area=\sqrt{s*\frac{-a+b+c}{2}*\frac{a-b+c}{2}*\frac{a+b-c}{2}}\\
Area=\sqrt{s*\frac{-a+b+c+2a-2a}{2}*\frac{a-b+c+2b-2b}{2}*\frac{a+b-c+2c-2c}{2}}\\
Area=\sqrt{s*\bigg(\frac{2a-a+b+c}{2}-\frac{2a}{2}\bigg)*\bigg(\frac{a+2b-b+c}{2}-\frac{2b}{2}\bigg)*\bigg(\frac{a+b+2c-c}{2}-\frac{2c}{2}\bigg)}\\
Area=\sqrt{s*\bigg(\frac{a+b+c}{2}-a\bigg)*\bigg(\frac{a+b+c}{2}-b\bigg)*\bigg(\frac{a+b+c}{2}-c\bigg)}\\
Area=\sqrt{s(s-a)(s-b)(s-c)}$$
## Using heron's formula
From this derivation, we have discovered that $Area=\sqrt{s(s-a)(s-b)(s-c)}$, where a, b, and c are separate sides of a triangle and s is the half perimeter of the triangle. We can use this in any case where we have all sides of the triangle and/ or we don't know any of the measures of the angles in the triangle.