# UGG_Authenticity_CNN
An ongoing project to help potential UGG boot buyers determine if the shoes they are about to purchase from 
an unknown individual on the internet are authentic or not. 
This CNN can identify particular features of the boot, then learn if they are authentic or replicas with 94% accuracy. 
The testing accuracy resulted in 91% accuracy which I attribute to my small dataset

For my own personal training and testing, I created 14 total classes detailing 7 features, each having 'real' or 'fake' identification:
- Stiching (the stitching along the side of the boot)
- Heel Label (Label found on the back of the heel)
- Inside Tag (The tag on the inside of the boot that should feature the size, style number, and holographic image)
- Soles (the print on the soles of the shoes)
- Back (Back of the boots showing both the back heel label and the top of the boots)
- Front (Straight-on picture showing the entirety of the front of the boots)
- Outside (pictures that do not fall within these previously defined categories but are still useful)

This code allows you to first convert your images into the same type and size.
Then, you create your dataset with image_generator.

This is still a work in progress, but I've gotten it to a point where I think it can be published.
As my dataset grows, I will add more. 

I hope this helps!
