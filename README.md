# Mellow VzBot 330 Kit Information

This is a repository for VZbot mods and info as I went through my build, in July of 2023. I am optimistic the kit will continue to improve. 

Check out my videos here to learn more about this build, including printed part options, first impressions, and a compelte build series. 

https://www.youtube.com/watch?v=h90rvTm2mc8&list=PLpQnpsv1trbRPkbdpc53gmuK3JUCKimgY

Based in the US? Buy your VzBot from Provok3d, who sponsored my build.

https://provok3d.com/product/mellow-vz330-awd/?v=0a10a0b3e53b

# Detailed Info

This content is intended to augment my videos and has more detail that may be helpful for you. This document also includes links to additional components and recommendations for tools that you may need for your build. 

https://github.com/techyg/VzBot/blob/main/Mellow%20VZ%20Bot%20330%20Initial%20impressions.pdf

*** The kit also has several missing fasteners and room for improvement. ** This is not a comprehensive list, but will give you an idea of what additional components you may need to purchase for your kit. I list the missing fastners here as well as some other suggestions for improving the kit.

https://github.com/techyg/VzBot/blob/main/Mellow%20Fly%20Kit%20Suggestions%20VzBot%20330%20Kit.pdf

# Printed Parts

2020 Endscap - Mellow Fly 330 Remix.stl: The stock parts for the 2020 covers are too long and hit the bolt. I created the remix that will work with the Mellow Fly extrusion. You will need to print 8 of these.

VzHextrudort_Motor_Spacer_v1.stl: This helps insulate the motor the heat. I ran into an issue where my motor was causing lower temp filament (PETG) to deform/clog in the extruder due to excessive heat. This is only .5mm thick- print this at a low layer height (.1mm is what I used). I remixed this, original part is from Thingiverse. https://www.thingiverse.com/thing:5777803

If you plan to print PLA or PETG, I definitely recommend using the motor spacer / heat shield. In my testing, I noticed a significant difference in the temp of the extruder vs. the motor, compared to NOT using it. This is because the motor will transfer heat to the extruder much more easily without the motor shield. While it was a little challenging to get exact temps of the motor, using an IR gun I never exceed 60C temps on the extruder and I believe the motor was around 80C. Note that I also did not have the top hat on when printing (but doors were closed), and I also lowered my motor current to .6. 

# Config & Slicer Files

This folder includes all of the printer.cfg and related files that I use. Files are all based on the "stock" VzBot configuration. 

   
