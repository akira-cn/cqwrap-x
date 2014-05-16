# cqwrap-x 

cqwrap-x is a project-creator for cocos2d-x-2.2.2 jsbinding with [cqwrap](https://github.com/akira-cn/cqwrap)

## How to create

1. Copy the multi-platform-cqwrap dir to your $COCOS2D_ROOT/template/ dir.
2. Replace the create_project.py file to $COCOS2D_ROOT/tools/project-creator/create_project.py
3. Run shell command

```bash
python create_project.py -project YourProject -package com.your.package -language cqwrap
```

4. You can find your created project on $COCOS2D_ROOT/projects

## How to run

1. proj.web

  Simply run ./server.sh.

2. proj.ios

  Open your xcode and build.

3. proj.android

  Open the build_native.sh file add NDK_ROOT="$HOME/your/path/to/ndk" then you can run it on ADT or android studio.

## Docs

http://cqwrap.weizoo.com/wiki
