import requests
url = 'http://localhost:3333/'
files = {'img' : open('img.jpg', 'rb')}
requests.post(url, files=files)