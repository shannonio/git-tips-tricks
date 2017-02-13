### Pieces of Git

- The thing that makes your git repo a git repo is the hidden .git folder in your repo
- HEAD -- the snapshot of ***your last commit.***
- Tree Objects
- Commit Objects
```bash
sha1(
    commit message  => "initial commit"
    commiter        => Christoph Burgdorf <christoph.burgdorf@gmail.com>
    commit date     => Sat Nov 8 10:56:57 2014 +0100
    author          => Christoph Burgdorf <christoph.burgdorf@gmail.com>
    author date     => Sat Nov 8 10:56:57 2014 +0100
    tree            => 9c435a86e664be00db0d973e981425e4a3ef3f8d
    parents         => [0d973e9c4353ef3f8ddb98a86e664be001425e4a]
)
```

[Simple Internals](https://blog.thoughtram.io/git/2014/11/18/the-anatomy-of-a-git-commit.html)
[Adv Internals](https://git-scm.com/book/en/v2/Git-Internals-Git-Objects)
