# gimp-curves-to-ffmpeg
Converts gimp color adjustment curves to ffmpeg  
Quick hack that probably falls apart in all of the edge cases. curve types, linearity etc ignored  

1. tweak color curves in gimp, choose "Export Current Settings To File"
2. python gimp-to-ffmpeg.py input-curve-file.txt > ffmpeg-filter-command.txt
3. have fun


