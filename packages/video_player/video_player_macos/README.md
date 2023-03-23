A working version of video player for MacOS only. Works with other libraries.

You must also include video_player: ^2.4.4 as a base.
This will work with chewie and other video overlays.

Based on Flutter video player.

Needs addtional maintanence. Please make PRs.

```
video_player_macos:
git:
    url: https://github.com/ollydixon/flutter_macos_video_player
    path: packages/video_player/video_player_macos
```

You can also use

```
video_player_macos: 2.0.1
```

I would suggest using a cominbation like such in your pub.dev
(For all platforms except Windows)

You will need to write a different view for each, spanning  

```
# For iOS and Android
better_player: ^0.0.83
# For Windows
flutter_meedu_videoplayer: ^3.2.0
# For Web 
video_player: ^2.6.0
chewie: ^1.4.0
# This library
video_player_macos: 2.0.1
```
