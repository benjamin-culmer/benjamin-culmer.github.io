---
layout: project
title:  UPenn PET Explorer
date:   2019-08-14 12:00:00
logo: /assets/img/me with scanner.JPG
logo_options: width="400px"
tags: [research_assistant]
published: true
---

## Highlights
- Assembled and wired an entire PET scanner from the ground up to learn about the system and build the product
- Dagnosed and repaired unknown defects in compontents through toruble shooting and testing using Linux
- Developed procedures and produced documentation for manufacturing and testing the Explorer
- Instructed others on manufacturing procedures, defined tasks, and delegated work
- Engineered and manufactured a method for safely mixing radioactive materials in a phantom using SolidWorks

## Overview
I worked as an engineer at the University of Pennsylvania Perelman School of Medicine seven months last year. I worked in the radiology department under the only other engineer in the lab, who became my mentor. The group is building a new Positron Emission Tomography (PET) scanner, which will allow for a patient’s entire body to be scanned as well as increase the sensitivity of the scans. They are accomplishing this by utilizing seven concentric water cooled scanners lined up in a row. I was also tasked with designing a new method to mix radioactive isotopes into an artificial body to make testing of the scanner safer. 
    
One complete ring of the Explorer
{: style="text-align: center;"}
![Chassis cad](/assets/img/Penn Scanner_rotated.JPG){:height="50%" width="50%"}
{: style="text-align: center;"}
    
## Testing
Unfortunately, not all parts of the modules would always work. When a module failed, I had to determine if it was an individual tile that was defective, or the PCB stack on the module. I began by testing the status of entire modules. When there was a malfunction, I would take the module apart and test for where the malfunction had occurred. For both the tile and PCB stack, only one other person in the lab knew how to run that test. They both taught me the testing procedures using Linux, so I could troubleshoot the modules. Testing a single tile took 20 minutes, while testing a module, with 28 tiles, took only 30 minutes. As a result, it was more efficient to test the modules and replace faulty tiles. When a tile failed in a module, I would first swap the cables of two adjacent tiles, because removing a tile required almost 20 minutes. If the failure moved, I could replace the tile with one I had already tested to be good. If the failure stayed in the same location, I knew the PCB was faulty.
Before my arrival, there was a preliminary test to check the function of a PCB. After a new shipment of boards arrived, I discovered that over 50 percent were faulty. We stored these with the boards that had also been deemed faulty. After explaining the situation I discovered to the lead electrical engineer, he gave me a program that allowed me to rewrite the firmware on the PCBs. I was then able to fix 26 out of 28 PCBs, each of which cost five thousand dollars. 

## Writing and Teaching
As the only person building and testing the parts of the scanner, I developed a knowledge of the system that no one else had. As a result, it was crucial that I wrote down all of the knowledge I had acquired before I returned to school. The knowledge I had gained was the entirety of the test procedures, as I was the only person to run these tests at a full scale of production, and small tricks that sped up the manufacturing process. I rewrote a majority of the procedures and wrote brand new procedures on the testing of tiles, modules, and PCBs. I also trained my replacements and learned from their interpretations of my instructions on how to describe processes more clearly. 

## Eye for Perfection
I was commended on my attention to detail as I was able to catch multiple defective parts, saving the group $15,000. When building modules from brand new tiles, I noticed that one of the circuit boards in one of the tiles was damaged. From then on, I kept my eye out for any obvious physical damage to the boards and pins that connected them, each 1mm in length, testing any that looked faulty. I discovered that 15 out of 240 had failed. One post doctorate who was preparing to leave the group was in charge of this testing. He taught me the procedure, and, as I was the only person left who knew how to run this test, I wrote a full manual on testing this part.

## CAD
My biggest take away from this experience was my CAD knowledge. During my time at Penn, I taught myself how to use SolidWorks. I had used it a small amount at Dartmouth, but had very little working knowledge. My boss at Penn taught me how to think when using CAD. He taught me to always keep the design as simple as possible while making it elegant. After returning to Dartmouth, I noticed that my parts were very easy to modify when they needed changes. When performing finite element analysis on my parts, we seldom ran into errors in testing their strength, but, for parts designed by piers, we often ran into issues when creating the mesh of the part. 
While at Penn, I was tasked with devising a method to mix a radioactive solution into a large tube of water while keeping the entire system enclosed to reduce the risk of spilling the solution. Their method at the time was to add the solution and stir it with a stick. The issue here is that, when removing the stick, they risked spilling some radioactive solution. My solution to the problem was to add a stir bar to the solution and a modified cap to increase turbulence within the container to facilitate mixing. 

One module being tested for the Explorer
{: style="text-align: center;"}
![Chassis cad](/assets/img/Module.png){:height="75%" width="75%"}
{: style="text-align: center;"}

Insert to increase turbulence in the mixing project
{: style="text-align: center;"}
![Chassis cad](/assets/img/stir bar.PNG){:height="75%" width="75%"}
{: style="text-align: center;"}
