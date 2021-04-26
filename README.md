# CoreMLiPhoneApp

TGIF project: A day to develop my first iPhone app that identifies objects

The demo video is here.  To hear sound, click on the video, or follow along with slides and transcript below the video.

![demo](https://user-images.githubusercontent.com/38410965/111802199-1bf53180-88a4-11eb-97d2-886bbd716a3e.mov)

#

**Steve Depp**
462-55

Demo of:
- Apple
- Apple Core ML
- Apple Create ML
- Apple Vision

Need:
- Developers license
- X code
- iPhone
- 3 lines of code

Skill level:
- Never used X code
- Never exposed to any Apple hardware development 

#

> Thank you for taking the time to watch my video.  I started this morning with a goal to create an iPhone app that uses inferences trained by Apple API’s to classify random objects.  One thing I quickly realized is that Apple’s form of authentication prevents anyone from testing developed solutions on Apple hardware without developer identity.  As usual Apple has real people that communicate very well and that was sorted quickly.  

### CoreML iPhone App

<img width="1023" alt="image" src="https://user-images.githubusercontent.com/38410965/116094997-011d9600-a676-11eb-9666-3a9d1bf8ea78.png">

<img width="1025" alt="image" src="https://user-images.githubusercontent.com/38410965/116095479-75f0d000-a676-11eb-8b17-bee38b6c06c4.png">

#

> I spent the next few hours watching this fellow, Frank Derpke, demo his development on CoreML, CreateML and Vision.  

https://developer.apple.com/videos/play/wwdc2018/717/

<img width="1041" alt="image" src="https://user-images.githubusercontent.com/38410965/116096831-98cfb400-a677-11eb-967a-fa217ce0bddf.png">

<img width="1045" alt="image" src="https://user-images.githubusercontent.com/38410965/116096993-bd2b9080-a677-11eb-8c71-2dd4dbf19afb.png">

<img width="1050" alt="image" src="https://user-images.githubusercontent.com/38410965/116097066-cae11600-a677-11eb-8b23-54a096d305e3.png">

<img width="1052" alt="image" src="https://user-images.githubusercontent.com/38410965/116097119-d7656e80-a677-11eb-83df-704708a586f1.png">

<img width="1048" alt="image" src="https://user-images.githubusercontent.com/38410965/116097174-e51af400-a677-11eb-9e34-afb8fa04c516.png">

#

> I spent another half hour or so looking at other solutions that got me psyched up for my final project, because they’re going to be helping me out there, ...


https://developer.apple.com/documentation/vision/classifying_images_with_vision_and_core_ml

<img width="1047" alt="image" src="https://user-images.githubusercontent.com/38410965/116097530-388d4200-a678-11eb-9718-474f15e1fda3.png">

https://developer.apple.com/documentation/vision/detecting_objects_in_still_images

<img width="1051" alt="image" src="https://user-images.githubusercontent.com/38410965/116097697-61153c00-a678-11eb-87fb-1bd6866ff931.png">

https://apple.github.io/turicreate/docs/userguide/object_detection/

<img width="1047" alt="image" src="https://user-images.githubusercontent.com/38410965/116097830-83a75500-a678-11eb-9b2f-ea008878e67b.png">

https://help.apple.com/xcode/mac/current/#/dev23aab79b4

<img width="1046" alt="image" src="https://user-images.githubusercontent.com/38410965/116097905-9c176f80-a678-11eb-9778-702ca8c46b71.png">

https://apple.github.io/turicreate/docs/userguide/object_detection/export-coreml.html

<img width="1051" alt="image" src="https://user-images.githubusercontent.com/38410965/116097998-b3565d00-a678-11eb-8ff1-ce009e1d1403.png">

#

> ... and a little bit of time reading some meaningful research that applied what Frank and the gang are doing.

https://arxiv.org/abs/1808.08230

<img width="1047" alt="image" src="https://user-images.githubusercontent.com/38410965/116100717-34165880-a67b-11eb-8d22-ca6e83b41b7d.png">

#

> Like Frank, in the end, I wrote three lines of code.  That’s because training leans heavily on transfer learning from models that are optimized for Apple hardware.  Three lines of code means that the model takes up only 102 kilobytes of disk.  

<img width="651" alt="image" src="https://user-images.githubusercontent.com/38410965/116101084-88b9d380-a67b-11eb-8234-655473d55f41.png">

#

> My data are contained in 11 classes of objects: 16 photos I took of a book, 16 photos I took of brownie mix, 17 of a camera, 17 of an ice cream sandwich, 13 of keys, 17 of crumpled sheet music, 13 each of my identical twins (which didn’t work out very well in classification), 12 of a piano, 19 photos of salt and pepper shakers. 

<img width="1110" alt="image" src="https://user-images.githubusercontent.com/38410965/116102126-6bd1d000-a67c-11eb-9773-6814ad1d87ce.png">

<img width="1110" alt="image" src="https://user-images.githubusercontent.com/38410965/116102223-886e0800-a67c-11eb-9d94-31c2eb2c0708.png">

<img width="1110" alt="image" src="https://user-images.githubusercontent.com/38410965/116102273-94f26080-a67c-11eb-9900-b5ca6c99d0f1.png">

<img width="1110" alt="image" src="https://user-images.githubusercontent.com/38410965/116102323-9f145f00-a67c-11eb-9d6a-523489279800.png">

<img width="1110" alt="image" src="https://user-images.githubusercontent.com/38410965/116102368-a89dc700-a67c-11eb-9635-679b8e2b96ec.png">

<img width="1110" alt="image" src="https://user-images.githubusercontent.com/38410965/116102412-afc4d500-a67c-11eb-9ad7-da031c297a8f.png">

<img width="1110" alt="image" src="https://user-images.githubusercontent.com/38410965/116102441-b6534c80-a67c-11eb-8b41-84887680de14.png">

<img width="1110" alt="image" src="https://user-images.githubusercontent.com/38410965/116102464-bc492d80-a67c-11eb-8449-1568b8023f00.png">

<img width="1110" alt="image" src="https://user-images.githubusercontent.com/38410965/116102510-c539ff00-a67c-11eb-977a-ab519390e128.png">

<img width="1110" alt="image" src="https://user-images.githubusercontent.com/38410965/116102539-cbc87680-a67c-11eb-8aab-2fa99aa5f3c7.png">

<img width="1110" alt="image" src="https://user-images.githubusercontent.com/38410965/116102569-d2ef8480-a67c-11eb-8603-fdcccab14dfa.png">

#

> To load the code, err, to load the data, you run the code,  

<img width="1110" alt="image" src="https://user-images.githubusercontent.com/38410965/116102861-10541200-a67d-11eb-9258-1f016fff7daf.png">

> ... drag and drop, … drag and drop, (there we go), drag and drop ... 

<img width="573" alt="image" src="https://user-images.githubusercontent.com/38410965/116103194-5dd07f00-a67d-11eb-8b8b-e7a04b65ccb6.png">

<img width="689" alt="image" src="https://user-images.githubusercontent.com/38410965/116103366-835d8880-a67d-11eb-8cd1-e2f835d43103.png">

<img width="686" alt="image" src="https://user-images.githubusercontent.com/38410965/116103411-8e181d80-a67d-11eb-8bf6-ec796ab673c7.png">

<img width="692" alt="image" src="https://user-images.githubusercontent.com/38410965/116103486-a1c38400-a67d-11eb-8b3c-561ab90244ed.png">

> ... and watch the training.

<img width="694" alt="image" src="https://user-images.githubusercontent.com/38410965/116103601-bd2e8f00-a67d-11eb-9f18-dca0fc2d2a07.png">

<img width="712" alt="image" src="https://user-images.githubusercontent.com/38410965/116107402-0207f500-a681-11eb-922e-f19510d81093.png">

#

> You can validate the training, but I didn’t.  There you go.   

<img width="1072" alt="image" src="https://user-images.githubusercontent.com/38410965/116109322-accce300-a682-11eb-8d90-d00508030bb4.png">

#

> OK. And the results, the test results are contained here:  So, up here, you have the various labels and comments for each one of the classes, and they’re kept in a plist.      
 
<img width="724" alt="image" src="https://user-images.githubusercontent.com/38410965/116111626-d424af80-a684-11eb-959c-46d629249229.png">

#

> On the right hand side, *(top video below)*, I’m recording my iPhone.  It’s untethered from my computer as it runs the model. So, start the model here.  It’s going to classify a piano, no problem.  No problem with the book.  Seems the scores *(in the bottom video below)* are saying it’s seeing the salt and pepper shaker, but just can’t label it.  So, no go with the next items, which is the brownies.  I put that in there to confuse it with the book. No problem with the knife, right away.  Or keys; it got those every time.  It almost never got this next item; it almost never got the camera.  And this next one is the one I thought was most interesting: it’s a collection of papers that were all ruffled together and … (let’s see …  just can’t find the camera) … the papers, it actually found the papers even though I mixed the papers up quite a bit (versus their images in the training set). Tried to move them around a little bit: there you go.   


https://user-images.githubusercontent.com/38410965/116114737-a3924500-a687-11eb-9cf2-f22757019654.mp4 

https://user-images.githubusercontent.com/38410965/116114818-b7d64200-a687-11eb-9809-8a7608bfa536.mp4
