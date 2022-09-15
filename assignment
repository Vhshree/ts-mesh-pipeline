import requests
from bs4 import Beautifulsoup
req = request.get("https://opentender.eu/")
soup=Beautifulsoup(req.content, "html.parser")
print(soup.prettify())
