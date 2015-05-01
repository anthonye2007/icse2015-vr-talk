ICSE Talk
- Intro to VR and new generation of VR.
- Affordances
    - Spatial Cognition
    - Manipulation and Motion
    - Feedback
- RiftSketch
    - Debug window
    - Leap motion integraiton
    - Flocking algorithm


# What is VR?
There are many definitions of virtual reality, but we will use a casual definition that virtual reality is a combination of innate human abilities and the malleability provided by digital technology.

Humans are amazing creatures with all sorts of amazing abilities.  However, current programming environments only take advantage of a few of these abilities.  We have built VR prototypes that take more fully take advantage of the innate human abilities of spatial cognition, manipulation and motion, and feedback.

# Why use VR with SE?
VR enables more natural programming solutions. 

## More familiar
These solutions can be more familiar to users than traditional solutions which we expect would increase task speed and decrease cognitive load (ex: looking around in 3D via head vs. mouse). 

## New techniques
These solutions could also enable techniques that have been previously impossible. For example, VR enables video game developers to be *inside* their game while creating it.


------

# Intro, VR history and future

Our research paper describes the application of Virtual Reality to Software Engineering but, before we dive into the paper's specifics, we'd like to give you a primer on the history and future of Virtual Reality.

Most people probably know virtual reality from science fiction, where been a staple since the 1930s, not coincidentally around the dawn of television. The most popular fictional incarnations in William Gibson's Neuromancer in 1984 and Neal Stephenson's Snow Crash in 1992 and movies like the Matrix trilogy. In real-life though, VR enjoyed a golden age from the 1970s to the 1990s.  Despite the limitations in hardware , with rudimentary computing and graphical power, heavy CRT displays and low-resolution LCDs, VR research boomed with new ideas and thousands of papers.

However, the hardware of the time ultimately failed to meet the expectations and mainstream consumer adoption was simply not viable. Virtual reality was once again relagated to science fiction, game arcades and a handful of VR labs in institutions that could afford it. A movie called "The Lawnmower Man" was a symbolic nail in VR's coffin. Released in 1992 and starring Pierce Brosnan as a scientist who used VR to enhance the mental powers of an unsuspecting gardener who then goes on to exact revenge with this superhuman abilities before uploading himself into the world's telecommunications grid.  It was terrible. The public gave up on the idea of mainstream VR and researchers and developers returned to more practical work.

Fast forward about 15 years and VR is back with a vengeance. While most large companies had given up on VR, in 2012 a teenager named Palmer Luckey was busy building duck-taped head-mounted displays. Luckey exploited the mobile phone hardware and graphics processing that all of us now take for granted and he built a device with commodity displays and commodity gyroscope and accelerometor sensors and combined that with a simple GPU effect to undo the distortion introduced by a simple lens. With that, he set into motion a series of events that attracted programming legend John Carmack, games behemoth Valve and formed a company which debuted with a kickstarter campaign that raised 2.4 million dollars, got acquired by Facebook for 2 billion and resurrected the VR industry.

This new generation of VR devices provide an unparalleled experience at accessible prices. A combination of factors, including display resolution, sensor and display frequency, field of view, and latency, have been refined and continue to be improved in order to achieve that elusive goal of presence. When done right, VR can give users the undeniable sense of inhabiting the virtual world that they're presented with. Almost all the sensory queues that your brain uses are fooled into thinking that the virtual world is indeed the truth.

Today several major companies are involved in VR including Facebook, Google, Microsoft, Facebook, Valve, Samsung, HTC. Consumer hardware is around the corner and the entertainment industry is adopting VR at an accelerating pace. Although games are the obvious and most popular application of at the moment, many in the community, including Mark Zuckerberg, believe that VR is bound to be a general computing platform that will rival the desktop and the mobile phone.

# Affordances

In that vein, our research suggests several affordances that VR can provide to software engineering and provides rudimentary examples of how they might be implemented.

The first affordance we considered was spatial cognition. Unlike any other computing interface, VR can fully engage your brain's inherent sense of space through head tracking and stereoscopy. Our research considers that unlocking this capability can lead to improvements in comprehension and recall. When learning a codebase, one could view the structure of an application laid out around you or while reviewing a code change, you could toss irrelevant code into a pile at your feet or pin interesting snippets front and center.

The second affordance, manipulation and motion, speaks about using VR perhiperals to track the movement of your limbs in order to interact with virtual objects as you would with physical ones. This affordance would allow improved perception and retention. For example, you'd be able to crank a handle in a mechanical simulation and have a visceral experience of the software's behaviour or you'd be able to walk along a row of commit histories while attempting to find where a bug was introduced in code.

Finally, we consider feedback in VR. Although live-coding has existed in 2D software systems for decades, real-time feedback is especially effective in VR when your software has a visual 3D analog. Allowing developers to experience and edit the software and the world around them in a short cycle can improve productivity, experimentation and learning.

# Demo

- RiftSketch
    - Debug window
    - Leap motion integraiton
    - Flocking algorithm
