---
datePublished: '2016-09-01T04:02:51.622Z'
inFeed: true
author: []
via: {}
dateModified: '2016-09-01T04:02:47.621Z'
title: ''
publisher: {}
description: Something about this snippet I wrote makes me happy.
starred: false
sourcePath: _posts/2016-09-01-something-about-this-snippet-i-wrote-makes-me-happy.md
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

Something about this snippet I wrote makes me happy.