### sync from xcode

``` sh
rsync -r  ~/Library/Developer/Xcode/UserData/CodeSnippets/* ./snip
```

### sync to xcode

``` sh
rsync -r ./snip/*  ~/Library/Developer/Xcode/UserData/CodeSnippets 
```