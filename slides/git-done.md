done = "!f() { git co -b $1 && git add . --all && git commit -m $2 && git push -u origin $1 && hub pull-request -m $2; }; f"
