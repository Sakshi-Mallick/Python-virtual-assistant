# Python-virtual-assistant
This program is voice-based personal assistant has . It’s a useful tool for search, for reminders, and to write the note just by speaking it up. 
Window assistant is to create voice apps for the intelligent assistant.

1.When user need to open any other application, he/she can use the command open. 
E.g. Open Notepad, File explorer, goggle chrome, this will help to open the applications.

2.When user want to write the message can use command write. And to for searching purpose google can be used. It will also restart and shutdown on the command. 

3.It will detect the speech and save in the database, and retrieve from the database and executive command and delete it from database. 

4.Interactions between a user and your Window assistant skill are mostly free-form, so assistant must understand language naturally and also in context. Window assistant determines what a user wants to do by identifying the user intent from spoken or textual input 

5.If user want to know about something from the web , then It will also gives information about particular search through voice.




Install below packages

pip install SpeechRecognition - For the robot to listen to our voice/speech

pip install pyttsx3 - To speak out, or text to speech

pip install pywhatkit - For advance control on browser

pip install wikipedia - To get wikipedia data

pip install pyjokes - To get funny jokes

pip install ecapture

pip install wolframalpha

pip install PyAudio

If you come across any issues regarding pyaudio or Text to speech module, please go through below solution.

error: failed building wheel for pyaudio

if you are getting above error then try below steps on windows

open command prompt.
pip install pipwin (then press enter)
pipwin install pyaudio (press enter)
if Text to speech (pyttsx3) module is not working on windows 10 then install the older version of pyttsx3.

python -m pip install pyttsx3==2.71

(Run the above code in terminal. It will uninstall current version and then it installs the older version.)
