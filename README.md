# AudioFileTranslator
AFT is a python nano framework based on the googletrans and speech_recognition modules. AFT transcribe and translate an audio file to another language. The code is easy to understand and edit, the demo version translate a French dialogue to an English text.

*AFT work by installing the two required python modules:
</br>`$ pip install googletrans`
</br>`$ pip install SpeechRecognition`

## AFT Engine
"AFT Engine" is the module version of AFT. 
### Installation
To use AFT Engine, it's required to move "AFT_Engine.py" in the same directory of your own python script.
### Importation and usage
To import and use AFT Engine use the following code.</br>
```python
from AFT_Engine import *
print(AFTcore("audio.wav", "fr-FR", "fr", "ja"))
```
or (if you don't want to print the translated audio)</br>
```python
from AFT_Engine import *
AFTcore("audio.wav", "fr-FR", "fr", "ja"))
```
#### As you noticed the AFTcore function need 4 arguments: </br> ("AudioFilePath", "SourceLanguageCode-SourceCountryCode", "SourceLanguageCode", "DestinationLanguage")
[Language Code List](https://cloud.google.com/translate/docs/languages "Language Code List")</br></br>
#### The Repo contains a demo folder to help you use AFT Engine.

</br>

## AFT One
"AFT_One.py" is a version for people who only want to use AFT as Translator and not as a module. </br> </br>
![AFT Base ScreenShot](https://raw.githubusercontent.com/nnnzo/Ressources/master/img/Capture%20d%E2%80%99e%CC%81cran%202020-08-02%20a%CC%80%2012.28.09.png)

PS: The audio used in the screenshot is not really appropriate, it is made to learn the pronunciation of French words; hence the errors towards the end of the translation.
