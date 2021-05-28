# video-translator
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mx-pro/video-translator/blob/main/video_translator_google_colab.ipynb) <br><br>



## step 1 install required modules<br>
![Demo](https://github.com/mx-pro/temp/blob/main/1.PNG)
## step 2 select storage type<br>
temporary mean we will use google colab free storage as storage<br>
![Demo](https://github.com/mx-pro/temp/blob/main/2.PNG)
google drive mean we will use google drive as storage<br>
![Demo](https://github.com/mx-pro/temp/blob/main/3.PNG)
## step 3 paste your YouTube video link to get all available resolution<br>
First copy first cell code and paste in next cell and run <br><br>
Then pick the resolution id. You can find in on left side.<br>
![Demo](https://github.com/mx-pro/temp/blob/main/4.PNG)
## step 4 download youtube video <br><br>
enter youtube link = your youtube video link <br><br>
youtube_quality = "Auto"  mean you do not need to paste the resolution id in  "quality_number". That mean "quality_number" not use in the code. <br><br>
youtube_quality = "Manual" mean you need to paste the resolution id in  "quality_number". <br><br>
select_duration ="full video" mean we want to use the full video. So enter_start_time= "00:00:00"  and  enter_end_time= "00:00:60" not will use in the code. <br><br>
if select_duration ="some part" mean we want to trim the video. Here you need to type trim starting point in this format HH:MM:SS . Then type trim end time in enter_start_time= "00:00:00" in HH:MM:SS format<br>

![Demo](https://github.com/mx-pro/temp/blob/main/5.PNG)
## step 5 create translate video<br>
first download video subtitle using this website https://downsub.com/ or any other website then copy the subtitle and paste in "paste_subtitles=" <br> <br>
do_you_want__original_video_background_music ="Yes" meaning assume in the original video we have some background music so we want to keep it in your translated video. <br><br>
do_you_want__original_video_background_music ="No" we will remove background music <br><br>
subtitles_language = "" choose your subtitle language <br><br>
english_accent: this feature only working with english accent you can choose different accent <br><br>
synchronize_video_and_audio_time="yes" mean for example video duration is 1 minutes and audio time is 1.50 minutes. To match the time we will speed up audio speed the our audio duration will 1 minutes. <br><br>
synchronize_video_and_audio_time="No" mean for example video duration is 1 minutes and audio time is 1.50 minutes. When  we merge the video and audio audio will play but video freeze.<br>

![Demo](https://github.com/mx-pro/temp/blob/main/6.PNG)

## step 6 run this cell to download the video<br>
![Demo](https://github.com/mx-pro/temp/blob/main/7.PNG)
## step 7 run the cell to play the video on google colab using kora<br>

![Demo](https://github.com/mx-pro/temp/blob/main/8.PNG)
