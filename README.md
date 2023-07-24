# AI-Powered-Text-to-Speech-Translator-with-GoogleTranslateTTS
The Code is developed via "Python" language .
DESCRIPTION 


This Python code demonstrates an AI-Powered Text-to-Speech Translator using the `gTTS` (Google Text-to-Speech) library and `googletrans` for translation. The purpose of this code is to take user input in English and then translate and convert it to speech in the target language, which is set to Tamil (ta) by default. You can also change the target language.



Here's a breakdown of the code:



1. The script imports necessary libraries:

  - `gTTS`: A library to generate speech from text using Google Text-to-Speech API.

  - `googletrans`: A library to interact with Google Translate for language translation.

  - `os`: Used for handling the operating system commands.



2. The function `text_to_speech_with_translation` takes two parameters:

  - `text`: The English text input that the user wants to translate and convert to speech.

  - `target_language`: The language code for the target language, set to Tamil (ta) by default.



3. Inside the function:

  - The text is translated to the target language (Tamil) using `googletrans`.

  - The translated text is saved in the variable `translated_text`.

  - The translated text is printed to the console to display the translation.



4. The translated text is then passed to the `gTTS` library to generate speech in the target language.

  - The `gTTS` library generates an audio file in MP3 format using Google's Text-to-Speech API.

  - The audio file is saved as "translated_speech.mp3".



5. Finally, the script uses the `os.system` command to play the generated audio file.

  - On Windows, the "start" command opens the default media player to play the speech.



The user is prompted to enter the English text they want to translate and hear in the target language. When executed, the script performs the translation, converts the text to speech, and plays it using the default media player. The code showcases how AI-powered language translation and text-to-speech technology can be utilized to enhance cross-language communication and accessibility.
