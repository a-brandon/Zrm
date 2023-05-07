# Zrm
![image](https://github.com/a-brandon/Zrm/blob/main/images/chat_logs.png)

Zrm is a tool used to collect chat data from a Twitch stream and gives you the option of having the parsed data saved locally or emailing it to a recipient(s). The type of data collected:
- The keyword you're searching for.
- Which user(s) said the keyword (along with the message the keyword was in).
- The date and time the message was sent.
- Zrm currently only matches the actual word, not the word in another word.
  - Example: "Let's go". Zrm will pick this sentence up. "Let's ggo" won't be picked up.

# Table Of Contents
|Section|Explanation|
|---------------------------------------------------------------|---------------------------------------------------------------------|
|[Setup.](#setup)                                               |   Learn where to get TwitchDownloader from.                         |
|[Usage.](#usage)                                               |   Quick tutorial on how to use Zrm.                             |

# Setup
- Go to https://github.com/lay295/TwitchDownloader/releases and download the latest "release.zip" file (Zrm currently working with 1.40.7).
- Extract the files in the .zip file to the folder of your choice.
- Download the [Zrm](https://github.com/a-brandon/Zrm/releases/tag/v1.0.0) .exe file.
- Copy the .exe file to the same folder containing the files from the zip file.
- Folder should look like this if the above steps were done properly:
 
![Folder Preview](https://github.com/a-brandon/Zrm/blob/main/images/folder_preview.png)

# Usage.
- Run the TwitchDownloader .exe.
- Select the "Chat Downloader" option.
- Go to any **published** VOD on Twitch and copy the VOD ID (should look similar to this):

![VOD ID](https://github.com/a-brandon/Zrm/blob/main/pictures/vod_id.png)
- Paste it into the "VOD Link/ID" box in TwitchDownloader.
- Click "Get Info".
- Save it in the **same** folder that has the Zrm .exe file.
- Run the Zrm .exe file.
- Any recipient(s) will receive an attached text file containing the parsed data.
 - Note: Make sure to check junk mail if you don't see the email in your main inbox.
