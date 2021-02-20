# youtube-uploader
Python application for uploading videos to youtube


Execute:
Youtube-Uploader.py --file="your_file.mp4" --title="" --description="" --keywords="" --category="" --privacyStatus="public"

privacyStatus:
public, private, unlisted

Categories:
    2 - Cars & Vehicles
    23 - Comedy
    27 - Education
    24 - Entertainment
    1 - Film & Animation
    20 - Gaming
    26 - How-to & Style
    10 - Music
    25 - News & Politics
    29 - Non-profits & Activism
    22 - People & Blogs
    15 - Pets & Animals
    28 - Science & Technology
    17 - Sport
    19 - Travel & Events

Depencies:

pip3 install oauth2client
pip3 install google-auth-oauthlib
pip3 install google-api-python-client

OAuth:
https://developers.google.com/youtube/v3/guides/uploading_a_video
