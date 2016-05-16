# Initial Settings:
Frame 85, both logo and text over red background.  
100% 1920x1080.

![Initial Render Settings](./initial-settings.png)

## Bounces
Still logo and text  
Using absolute number of bounces (set max and min to the same number)

0 Lighting Bounces: **2:24**  
Nearly zero noise around logo or text.

4 Lighting Bounces: **2:28**  
Very Slight noise around logo and text, not noticeable at scale
No real change in performance.

12 Lighting Bounces: **2:31**  
Noise around logo and text is less noticeable

#### Result:
Very small render/performance impact.

## Reflective and Refractive Caustics

Both Enabled: **2:30**

Both Disabled: **2:26**

#### Result:
Barely any difference.
