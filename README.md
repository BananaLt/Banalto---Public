Versions:
C++17
Visual Studio 2022
JUCE 8.0.12

Steps:
1. Install the JUCE library: https://github.com/juce-framework/JUCE
2. In the "extras" folder, find "AudioPluginHost". Build and compile on an IDE.
3. Install an audio player (I used this: https://miraxlabs.com/products/vstplayer/).
4. Install the VST3 file. Create a folder and place this file into it.
5. In AudioPluginHost, press "ctrl+P". Check that the VST3 file is visible.
6. Open both your audio player and the VST3 in AudioPluginHost and connect the channels.
7. Begin playing audio. Use the knobs and sliders to adjust incoming audio data.

Additional Resources:
1. https://juce.com/learn/tutorials/
2. https://www.youtube.com/watch?v=i_Iq4_Kd7Rc (This video is very useful.)
3. https://www.learncpp.com/