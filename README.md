dynamation
==========

JS animations with a simple HTML integration

#### How to apply

Normal HTML would be like this:

```
<input type="button" class="button-primary" value="Estimate" />
```

Add class `animated` and data-animation for animation type.

Becomes:

```
<input type="button" class="button-primary animated" data-animation="fadeInDown" value="Estimate" />
```

or

```
<input type="button" class="button-primary animated" data-animation="fadeInDown" data-duration="2" data-delay="200" value="Estimate" />
```



**Attributes:**

**data-animation**: animation type

**data-animation-delay**: delay before animation started (in milliseconds), default 0

**data-animation-duration**: duration for animation (in seconds), default 1

**List of animation type:**

* fadeIn
* fadeInUp
* fadeInDown
* fadeInLeft
* fadeInRight
* fadeInUpBig
* fadeInDownBig
* fadeInLeftBig
* fadeInRightBig
* fadeOut
* fadeOutUp
* fadeOutDown
* fadeOutLeft
* fadeOutRight
* fadeOutUpBig
* fadeOutDownBig
* fadeOutLeftBig
* fadeOutRightBig
* slideInDown
* slideInLeft
* slideInRight  
* slideOutUp
* slideOutLeft
* slideOutRight
* elasticIn
* elasticInUp
* elasticInDown
* elasticInLeft
* elasticInRight
* elasticOut
* elasticOutUp
* elasticOutDown
* elasticOutLeft
* elasticOutRight
* bounceIn
* bounceInUp
* bounceInDown
* bounceInLeft
* bounceInRight
* lightSpeedIn
* lightSpeedOut
* flash
* shake
* bounce