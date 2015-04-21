# The Echo Vortex - ReadMe
###How to Use
To start, you will need to download and install pd-extended: https://puredata.info/downloads/pd-extended. Then download this repository (you can use the download as zip button to the right) and run the echovortex.pd patch.

When you run the patch, you will see a screen with some sliders and buttons. There are 4 gain sliders. IN controls the input volume, OUT controls the overall output volume, which is the combination of DRY (raw input) and WET (the delay effects). There are also 4 feedback sliders. LFB and RFB are feedback for the left and right channels, respectively. L2R and R2L control crossfeedback between the channels. To get some interesting effects, I like to use some crossfeedback while the delays are set to different values for each channel. 

To set the delay, you'll drag the horizontal delay slider to adjust the base value. You can change the range of the slider using the x2,/2 etc. buttons right by it. The delay value in ms will be shown in the number box below the slider. Then set the delay for a channel by pressing one of the SET FOR buttons, either L, R, or both. The delay value currently used by each channel is shown in the number boxes to the left and right of the buttons. 

The SWITCH DELAY button toggles between two different sets of delay lines, if the output starts to have too much feedback, you can bring the feedback sliders all the way down, then hit the buttons a couple of times and hopefully that will take care of it (can't guarantee that it will, depending on what sort of delay values you've been using).

###To Do
* Android version in the works.
* Better way of clearing the delay lines than the switch delay button.

###Contact
For questions and feedback, please feel free to email me at sean[dot]manton[at]gmail[dot]com