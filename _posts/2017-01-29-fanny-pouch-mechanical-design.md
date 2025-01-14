---
layout: post
title: "Mechanical Design - the 'Fanny Pouch'"
subtitle: "An overview of the design of our component casing"
date: 2017-01-29
poster: "Robert Sosiak"
header_content: |
    <header class="intro-header" style="background-image: url('/images/background/bg_21.jpg')">
        <div class="container">
            <div class="row">
                <div class="col-lg-12 col-lg-offset-0 col-md-10 col-md-offset-1">
                    <div class="post-heading">
                        <h1 class="post-title-font">Mechanical Design - the 'Fanny Pouch'</h1>
                        <h2 class="subheading">An overview of the design of our component casing</h2>
                        <p class="post-meta">Posted by Robert Sosiak on January 29, 2017</p>
                    </div>
                </div>
            </div>
        </div>
    </header>
---

This week we finished up most of the mechanical design for the inner pouch of the belt.  The original plan was to split the electrical components into two pouches; however, this creates issues with increased cable length, transmission quality and susceptibility to RF noise.  The new design incorporates all electrical breakout boards into a compact 8 by 10 centimeter pouch that will be located at the back of the belt.

As shown in the pictures below, the pouch contains small wire channels to connect the devices, and holes that allow the motor power lines to feed out through narrow plastic tubes.  The motors themselves are firmly secured to plastic casings that will increase the area of vibration and protect the motors themselves.  One of these pouches will fit directly into the back of the component pouch, to ensure that the IMU is centered with respect to the user.

<div style="display: flex; justify-content: center;">
	<img src="/images/blog/2017-01-29/TheFannyPouch.PNG" alt="" width="75%" height="50%" style="padding:20px" />
</div>

<div style="display: flex; justify-content: center;">
	<img src="/images/blog/2017-01-29/TheFannyPouch_orthographic.PNG" alt="" width="75%" height="50%" style="padding:20px" />
</div>

<br>

All in all, the pouch is nearly ready to be printed (some dimensional verification is still needed on the wire channels), and the belt will be under construction in the following week.