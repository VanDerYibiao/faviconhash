#python 3

import mmh3
import requests
import codecs
import sys

response = requests.get(sys.argv[1])

favicon = codecs.encode(response.content,"base64")

hashout = mmh3.hash(favicon)

print("http.favicon.hash:"+str(hashout)+'\n'+"iconhash:"+str(hashout))
