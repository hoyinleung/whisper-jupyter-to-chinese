# youtube 上字幕實在太麻煩，用太多時間，看了這次影片後以後就不這麼辛苦了
示範怎樣利用Python，OpenAI 的Whisper Speed-to-Text AI model，在Google Colab上運行，去實現AI自動上字幕的功能，輕鬆批量地為多個影片上中文字幕，很適合經營youtube影道的人。

# 影片連結
https://youtu.be/wOlpt-bfkvQ

# FFmpeg提取影片中的音頻指令
ffmpeg -i '01.mp4' -vn -c:a aac -b:a 72k output.aac

# whisper-jupyter-to-chinese
語音轉中文字幕script
