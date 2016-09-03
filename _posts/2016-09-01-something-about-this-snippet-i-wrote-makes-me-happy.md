---
datePublished: '2016-09-01T04:29:36.841Z'
sourcePath: _posts/2016-09-01-something-about-this-snippet-i-wrote-makes-me-happy.md
inFeed: true
author: []
via: {}
dateModified: '2016-09-01T04:29:36.739Z'
title: ''
publisher: {}
description: ''
starred: false
_type: Blurb

---
ticker.addEventListener("animationiteration", function DisplayItem(e) {
                $log.log('We have ' + newsData.length + '\' items of news to display');
                if (newsData.length <= 0) {
                    GetTickerMessages();
                    return;
                } 
                ticker.innerText = newsData[newsData.length - 1].Msg
                newsData.pop(); 
            }, false);