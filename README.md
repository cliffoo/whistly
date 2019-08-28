# Whistly - React Native Music App
![Collage](https://i.imgur.com/T8PRCx3.png)
## Demo video
Click to watch video. Read General info below for context.
[
![Demo video](https://i.imgur.com/GdnIrjL.png)](https://www.youtube.com/watch?v=2qI87Yws7vc)
## General info
I thought it'd be fun to rip off YouTube Music by making an app that allows you to download MP3 directly from YouTube. In retrospect this idea was pretty stupid because:
1. Google Play will reject it. I found out later that it rejects all apps that allow users to play YouTube videos in the background.
2. All audio/video-related components in RN are finicky. They work, but the controls need to be customized. There is no integration with YouTube, as the YouTube component doesn't work on Android unless the user has YouTube installed. The solution was to use WebView, which has performance issues and messes up the UI.
3. This was the biggest setback: I couldn't for the life of me get my custom Song component to keep rendering. I.e. the music wouldn't play unless the user was on the same screen all the time. This was the deal-breaker that made me put a stop to this project.
4. Violation of YouTube EULA.
<br>
Nevertheless, I'm glad I did this. It was the best learning experience possible. I had fun making the logo and trying to design a reasonably good UI. I learned how to prototype and wireframe; how to deal with authentication flow; how to persist key-value pairs/files on the phone; how to use Redux (and its middleware) in conjunction with RN, etc.
## Prototype
It's not professionally made with something like Adobe XD, but it gets the job done. This is the first time I tried wireframing, and now I can't imagine building a mobile app without it. It gives you directions on what to build, instead of thinking about what you want it to look like as you are building.
![Wireframe](https://i.imgur.com/DNB0DGZ.png)
## Lesson
Plan... Plan a lot beforehand. Think about what I want out of the project. Yes the project was fun and it really sharpened my React Native and Redux skills, but it was time-consuming and I can't deliver the app due to the issues I mentioned above. I need a clear objective for the project: Is it for training purposes only? Or do I actually want to make a production build and publish it? Only after answering this question can I start thinking about whether or not the idea is feasible, how much time it will take, etc.
###### Shameless notice

Not putting the code here because it's too messy lol.

