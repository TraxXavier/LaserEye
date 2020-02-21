# Disclosure to public of Next gen laser protection concepts 

Laser protection is an important field of work safety.

Using modern Technology there are multiple approaches how to implement eye protection from laser radiation while maintaining a good sight and the ability to perceive the laser radiation, including invisible wavelengths.

## Extended Spectral perception + Full protection

The most obvious Approach to this issue is to use cameras to record the surroundings and reproduce it on Micro-Displays inside the laser protection glasses. Hence allowing the wearer to see the world in full color + additional wavelengths that the cameras can record, while being fully protected as there is no direct optical path a laser beam could hit the eyes.

Like patented under: US2009231417A1, US8334899, US2012249400A1, US20120249400, WO2017182431

This approach is very challenging regarding its technical implementations, the streamed picture needs to be sufficiently high resolution and have sufficiently low latency, an image correction for the cameras perspective not being placed in the user’s head may also be necessary to improve the user experience.

As such a system if it fails renders the wearer effectively blind, and it can not be safely removed, it is a reasonable improvement to implement the system in a redundant way, for example independent circuits and batteries for each eye / side. 
Additionally, various interlocks and overrides would be recommended, interlocks that disable all lasers in the room when one of the protective devices in use would to fail (dead man switch style), as well as override options to disable all AR aspects of the product that may hinder vision with a fall back to a see-through only mode of operation.


## Extended Spectral perception + Limited protection

As one of the main benefits of such a system is the ability to perceive laser radiation while being protected there exist also a simplified solution that does not offer full protection.

Here an augmented reality approach is where normal, optical filters-based laser protection glasses are used to protect the wearer, and a (semi) transparent micro display (or micro projectors or holographic displays, or other solutions known from the VR/AR field) between the optical filter glasses and the eyes of the wearer displays a camera image visualizing the laser. A camera placed on the outside frame of the glasses can image the laser radiation unhindered and allow for visualization of even to the human eye invisible wavelengths.
It is also possible to combine the image reproduction system with the laser protection filter glasses, for example using wave guides, although that would be a subpar implementation.

Augmented Reality in combination with regular Laser protection glasses have already been patented: US20160349539A1

The novelty here is the inclusion of one or more cameras on the body of the glasses to visualize the laser radiation on the internal image reproduction system.

Using control elements like one (or multiple) touch pad and/ or buttons on the body of the glasses can allow to control the device, to adjust the image overlap, camera exposure, zoom, focus, etc… as well as control the AR aspects of the product, the controls can also be used to enable/disable the image, or switch between off, image pass through, AR or image pass through + AR.
Another way of controlling the device may be gestures, as perceived by the camera’s, or radar ICs, or accelerometers placed in the product itself, or other interface concepts already known in the VR/AR field.

The AR aspect of such a product can be used to render virtual laser paths as presumed to be known in implementation that tracks the user’s head position in the workplace. 

It is also possible to implement advanced image processing from multiple cameras to realize a good automatic image overlap between the image as seen by the user through the filter glasses with the camera image, as here a good overlap is essential for the user.

Improvements to the implementations of this and the above variation of the concept can be achieved by adding eye tracking capabilities, such that the computing unit can make better perspective/image adjustments based on the information where the wearer is looking at any given moment.  This information can also be employed to control the camera, or cameras, parameters like focus and zoom.

The downside of this implementation is the limited protection that isn’t better as with classical protective eyewear, but the visualization of the laser beam, or more general any otherwise invisible (or filtered out) radiation that can be imaged with cameras, microbolometers or other imaging technologies improves the wearers ability to work with lasers especially when spatial awareness of the exact beam path is important. 
Examples here is generally lab work with lasers, aligning laser paths in experimental or industrial setups, but also in the field of medicine where the operator needs to see the laser beam on the patient’s body. 

As the cost of high-performance optical filter glasses is high, it is expedient to implement the described device such that the optical filters can be replaced by the user depending on his momentary needs.
Another component worth implementing in a replaceable manner are the cameras (or camera if there is only one) themselves, as they not only may suffer damage from direct laser incident (and user reparability here would be a usability improvement) but being customizable would benefit the customers a lot.
Camera varies greatly in their spectral capabilities as do the associated costs, hence it is very useful when the user can swap in the right camera type for his application on his own.


## Simplified Extended Spectral perception + Limited protection

If the goal of the user is to simpler visualize otherwise not visible to him laser radiation a device like the previous concept can be further simplified by realizing the device as an external addon to an already existing protective eyewear.
Here the displays as well as the cameras are placed in an addon device that is externally attached to existing protective eyewear, such an approach holds the benefit that it can be manufactured much cheaper as it’s no longer strictly speaking a safety product.
Such a device can for further simplicity be implemented as a single eye variant (monocular) cutting further down on the costs and improving the user experience.
Being placed externally to the area enclosed by the protective eyewear the image alignment here can be done by the user also just fully mechanically my moving the device around.
Another advantage is here that the user experience does not longer benefits from semitransparent implementation and cheaper display solutions can be employed. Here another advantage is that the camera can be placed directly behind the display.



## Summary

This is a dump of some ideas that crossed my mind in the past decade, to be noticed by the public as prior art, such that no one can in the years to come claim anything her exclusively for his/her own.

