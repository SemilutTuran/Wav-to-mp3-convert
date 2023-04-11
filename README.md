# Wav-to-mp3-convert
This Bash script convert wav to mp3


To user this in i have used debian 11 

install the nessesary tools for it 

sudo apt update


sudo apt install ffmpeg libavcodec-extra libavformat-extra libavutil-dev libswscale-dev


ffmpeg -version


chmod +x  Wav-to-mp3-convert.sh

Create a directry input and output

upload the *.wav to the input directry it will automaticly convert it to mp3 in output directory

./ Wav-to-mp3-convert.sh 
