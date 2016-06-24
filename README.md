#!/usr/bin/python
import re
import urllib

def getHtml(url):
    page =urllib.urlopen(url)
    html=page.read()
    return html

getHtml("http://cd.qq.com/a/20160624/009454.htm?pgv_ref=aio2015&ptlang=2052")
