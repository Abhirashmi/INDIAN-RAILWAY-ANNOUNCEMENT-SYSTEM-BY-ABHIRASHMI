# INDIAN-RAILWAY-ANNOUNCEMENT-SYSTEM-BY-ABHIRASHMI
we all have been travelling in indian railways since childhood and we all have been mimicing the saying "yatrigan kripya dhyan de" or "may i have your attention  please".
what if we want to automate this announcement system with few lines of code and everything will be automatic. 
using modules of python we can do that , provided the csv file of data comprising train no, train name, from city , to city , via ,platformm number, etc 
using modules like 

import os
import pandas as pd
from pydub import AudioSegment  #“Pydub lets you do stuff to audio in a way that isn’t stupid.”pydum needs ffmpeg
from gtts import gTTS   #Google Text-to-Speech), a Python library and CLI tool to interface with Google Translate's text-to-speech API.

and creating function to convert the text to speech,generating audios by combining the audios we have formed .
this way is quite helpful in indian railways annoncement system we can generate millions of audios  named as train_nu_announcement for the comfort and we can automate the function of indian railways announcement all through few lines of code 
