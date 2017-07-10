# lyric_analyser
Tamil Lyric Analyser

How to run and test the code:

Download the file and extract it in to folder named lyricanlayser. The folder can be opened as a project using Netbeans.

Main file: LyricAnalyser.java in the lyricanalyser package. 

When run opens a frame where you can select the lyric file you want to analyse and perform the required functions.

Input: A text file having the song lyrics which can be selected using the File -> Open option in the opened frame. The file gets loaded in the frame.

Output: The flow score of the lyric can be got by clicking the flow score button at the bottom of the frame or selecting the Analyse -> flow score options from the menu. Additionally the song can be transliterated to english by selecting the Tools -> Transliterate options from the menu.

Interface: Has the button flow score to ind the flow score of the lyric.

Example: Input : A text file with the song lyric.

<தலைப்பு>ஆலயமணியின் ஓசையை </தலைப்பு>
<படம்>பாலும் பழமும்</படம்>
<இசை>விஸ்வனாதன்,ராமமூர்த்தி</இசை>
<வரிகள்>கண்ணதாசன்</வரிகள்>
<பாடல்>
<பல்லவி>
ஆலயமணியின் ஒசையை நான் கேட்டேன்
அருள்மொழி கூறும் பறவைகள் ஒலி கேட்டேன்
என் இறைவன் அவனே அவனே 
எனப்பாடும் ஒலி கேட்டேன்
உன் தலைவன் அவனே அவனே 
எனும் தாயின் மொழி கேட்டேன்
</பல்லவி>
<சரணம்>
இளகும் மாலைப் பொழுதினிலே
என் இறைவன் வந்தான் தேரினிலே
ஏழையின் இல்லம் இதுவென்றான்
இரு விழியாலே மாலையிட்டான்
இரு விழியாலே மாலையிட்டான்
</சரணம்>
<சரணம்>
காதல் கோயில் நடுவினிலே
கருணைத் தேவன் மடியினிலே
யாரும் அறியாப் பொழுதினிலே
அடைக்கலம் ஆனேன் முடிவினிலே
அடைக்கலம் ஆனேன் முடிவினிலே
</சரணம்>
</பாடல்>


Output :

Flow score:0.3153

Transliterated lyrics:

aalayamaNiyin osaiyai naan kaettaen 
aruLmozhi kooRum paRavaikaL oli kaettaen 
en iRaivan avanae avanae 
enappaatum oli kaettaen 
un thalaivan avanae avanae 
enum thaayin mozhi kaettaen 


iLakum maalaip pozhuthinilae 
en iRaivan vanthaan thaerinilae 
aezhaiyin illam ithuvenRaan 
iru vizhiyaalae maalaiyittaan 
iru vizhiyaalae maalaiyittaan 


kaathal koayil natuvinilae 
karuNaith thaevan matiyinilae 
yaarum aRiyaap pozhuthinilae 
ataikkalam aanaen mutivinilae 
ataikkalam aanaen mutivinilae 
