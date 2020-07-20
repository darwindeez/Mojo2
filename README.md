# Mojo2 Audio Unit

I just wanted a version of Mojo with an internal highpass like Density/Drive. Here's what I did:


I added the "gain" variable and the mojo function into Density. 

I replaced all instances of the word "Density" with "Mojo2" throughout the codebase. 

I set the range of parameter1 ('Mojo') to be -12.0 to 12.0, like it is in Mojo. 

I added "uint32_t fpd" as a private member in the class access modifiers. 

I did not alter any plist files, nor any of the files inside Mojo2.xcodeproj. 


Would this work if you compiled it? I don't have xcode.
