# Connect driver
- from google.colab import drive
- drive.mount('/content/drive')
# add Path 
- path = "/content/drive/MyDrive/AI /AI Specialist Self/Bài Tập/25 6"
- import os
- %pwd => /content
- os.chdir(path)
- %pwd => /content/drive/MyDrive/AI /AI Specialist Self/Bài Tập/25 6
- os.listdir() => [ list file in path same %ls]
- pip install patool => [install package to extract file]
-