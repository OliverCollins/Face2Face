# Face2Face

<center>Facial recognition software to detect during an interview or interrogation if someone is lying.</center>

## Facial Recognition

Through Microsoft Azure's Facial Recognition API (https://azure.microsoft.com/en-us/services/cognitive-services/face/), I was able to display emotions, facial landmarks, face attributes, and many more characteristics given through the algorithm. Through the data we collected, I would then parse through the data and run it through an algorithm created to determine if the interviewee or the interrogatee are telling the truth or not.

![alt text](/assets/images/Azure_API.png)

## Video Slicing

Using @ilkkao's capture-video-frame micro-library (https://github.com/ilkkao/capture-video-frame) I was able to take slices of video and split them into frames or individual "pictures" to be evaluated, and so I can run them through the algorithm.

![alt text](/assets/images/AllTogether.png)

Once I gathered a bunch of these frames, I then individually parsed through each picture and determine if there was significant information to determine if the interviewee is telling the truth. Through each frame, we send the data to the user so they can see results in live time.

## Lie-Detector Algorithm

Unfortunately, I did not get to the actual algorithm that would parse through the images.
