# JSSpeechExample
This repository has an example project of a HTML speech client using the Microsoft Bing Speech APIs.

# Usage
To use, first replace the string ADD_BING_SPEECH_KEY_HERE in index.html with your Bing Speech API key.  You can get this key through your Azure subscription, or through the Bing Speech homepage (see https://docs.microsoft.com/en-us/azure/cognitive-services/Speech/Home).

After adding your Bing Speech API key, then deploy the files as static html content.  The page should request to use your microphone upon loading, and after that repeat everything you say as text in the web page, and through TextToSpeech.  English only in this demo, but you can change the language in the index.html code.

![screenshot](https://github.com/tyayers/JSSpeechExample/blob/master/screenshot.PNG)
