# stable-video
stable video hackathon

ffmpeg -i output.mp4 -filter:v "minterpolate='fps=30'" output0.mp4

ffmpeg -i output0.mp4 -i audio.m4a -c:v copy -c:a aac -strict experimental output1.mp4\


