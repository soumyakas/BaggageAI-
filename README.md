# BaggageAI-
Image processing on airport X-ray images 
Given two sets of images:- background and threat objects. Background images are the
background x-ray images of baggage that gets generated after passing through a X-ray machine at
airport. Threat images are the x-ray images of threats that are prohibited at airport while travelling.
• Task is to cut the threat objects, scale it down, rotate with 45 degree and paste it
into the background images using image processing techniques in python.
• Threat objects should be translucent, means it should not look like that it is cut pasted. It
should look like that the threat was already there in the background images. Translucent
means the threat objects should have shades of background where it is pasted.
• Threat should not go outside the boundary of the baggage. **difficult**
• If there is any background of threat objects, then it should not be cut pasted into the
background images, which means while cutting the threat objects, the boundary of a threat
object should be tight-bound.
