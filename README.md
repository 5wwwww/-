#!/usr/bin/python
import re
import urllib

def getHtml(url):
    page =urllib.urlopen(url)
    html=page.read()
    return html

getHtml("http://www.icoolxue.com/play/1945")
