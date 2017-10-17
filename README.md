# Video-Grapher
Video-Grapher helps you control your videos playing anywhere in the browser.

If you switch between multiple tabs in which videos are playing, then this extension will help you play the currrent video you are focused on.

For instance : If there is already a Youtube tab thats playing a video and you try to play another video on different tab then this extension will automatically pause the earlier one and focuses on the current video.

You can control the video of non-active tab from the extension icon. There will be no effect for active tab if you try to contorl thar from extesion icon.

For facebook : If just stops the another background video if you are playing Facebook vides. There will be no effect of extension icon in Facebook website.

# Requirements:
Any operating system having Google Chrome as its browser.

# API's:
It uses Google Chrome JavaScript APIs's
https://developer.chrome.com/extensions/api_index

## Methods used are as follows : 
* chrome.runtime.onMessage.addListener
* chrome.storage.sync.get
* chrome.tabs.query
* chrome.tabs.sendMessage
* chrome.browserAction.onClicked
* chrome.tabs.onUpdated.addListener
* chrome.tabs.onActivated.addListener




# Future scope 
Doing sentimental analysis for youtube videos. It will retrieve comments data about the videos as well as basic information about the links count and view count of the videos. Then, we will use NLTK to see most frequently used words in the comments and plot some sentimental graphs.


