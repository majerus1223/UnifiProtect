# UnifiProtect


cd /var/etc/sounds/sounds_ring_button  
mv Chime.wav oldChime.wav  
cp ../hohohomf2.wav Chime.wav  
chmod 777 Chime.wav  


File must be wav and 44100 hertz. Mono does not appear to be a requirement based on hohohomf2.wav


ffmpeg  
ffmpeg.exe -i orig.mp4 -vn -acodec copy out.m4a  
ffmpeg.exe -i .\out.m4a .\final.wav
