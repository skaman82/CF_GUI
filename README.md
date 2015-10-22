# Cleanflight-Configurator-GUI-redesign
New GUI Elements for Cleanflight Configurator


ABOUT:
Hi there! I' using cleanflight almost 6 months now (since I am in RC) and I love what you guys put together here but I'm seeing some things that could be improved. I am a graphic designer and work in a advertising agency. In last 10 years I've worked on a bunch of different web-projects an learned a lot about UI & UX Design.

From my point of view CF is great but is becoming more and more complicated to use as new features coming in. Some things are even just in the wrong place or not have correct labeling that a normal user understands without going through docs. It just looks like it was made by developers for developers but not for a normal folks like me. The lack of documentation is another problem.

I have no clue about programming and need some help. From my work I also know that you can't make everybody happy and some of the community will most likely don't like my approach. But we can discuss things of course :)

My goal is not just make the GUI nice and shiny but also complete rethink its structure and functionality. The are talks about removing the CLI. I think this is a good thing, but the GUI needs some more fields for configuration that are not there yet (where can I put in a mag_align value when the CLI is gone?)

Here some examples of my thoughts on improving things:
• There should be just one way to backup the full configuration and all profiles with the backup button - not using CLI
• Profile select field seems out of place. It affects way more just the PIDs so why is this in the PID tab?
• PID Setup is very messy. Each controller uses different variables for different things but the fields are labeled the same on each controller. Good example for that are the LEVEL PIDs which are not realy PIDs. 
• There should be a kind of tooltip for each field with a short description what this value does and the used variable name (if CLI is still there). 
• There should be only hardware specific fields - so if no baro and mag are present there should be no ALT and MAG PID fields in the PID tab to make the interface cleaner.

I can't put a time frame on this yet but I'm guessing this will take some months to accomplish. So if someone is interested to take the configurator one step further please let me now. I can provide PSD files, general CSS and all icons as SVG files to work with for final implementing.


