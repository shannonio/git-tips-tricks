expunge = !git branch --merged mainline | grep -v 'mainline$' | xargs git branch -d
