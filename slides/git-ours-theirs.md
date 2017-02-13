accept-ours = "!f() { files=\"$@\"; [ -z $files ] && files='.'; git checkout --ours -- $files; git add -u $files; }; f"
accept-theirs = "!f() { files=\"$@\"; [ -z $files ] && files='.'; git checkout --theirs -- $files; git add -u $files; }; f"
