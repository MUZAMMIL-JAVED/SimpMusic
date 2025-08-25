<div align="center"> <img src="https://raw.githubusercontent.com/maxrave-dev/SimpMusic/jetpack_compose/fastlane/metadata/android/en-US/images/featureGraphic.png"> <h1>SimpMusic</h1>  
A FOSS YouTube Music client for Android with many features from<br>Spotify, SponsorBlock, ReturnYouTubeDislike
<br> 
<br>

  
## Features ✨️    
- Play music from YouTube Music or YouTube for free, without ads and in the background    
- Browsing Home, Charts, Podcast, Moods & Genre with YouTube Music data at high speed    
- Search everything on YouTube    
- Analyze your playing data, create custom playlists, and sync with YouTube Music...    
- Spotify Canvas supported    
- Play 1080p video option with subtitle    
- AI song suggestions    
- Notifications from followed artists    
- Caching and offline playback support    
- Synced lyrics from SimpMusic Lyrics, LRCLIB, Spotify (require login) and YouTube Transcript - AI lyrics translation (BETA) (\*)  
- Personalize data (\**) and multi-YouTube-account support    
- Supports SponsorBlock and Return YouTube Dislike
- Sleep Timer    
- Android Auto with online content    
- And many more!    
  
> (\*) Use your OpenAI or Gemini API key    
> (\**) For users who chose "Send back to Google" feature    
    
> **Warning**    
 > This app is in the beta stage, so it may have many bugs and make it crash. If you find any bugs,      
> please create an issue or contact me via email or Discord server.   
    
## Screenshots    
 <p align="center">          
 <img src="https://github.com/maxrave-dev/SimpMusic/blob/jetpack_compose/asset/screenshot/2.png?raw=true" width="200" />          
  <img src="https://github.com/maxrave-dev/SimpMusic/blob/jetpack_compose/asset/screenshot/3.png?raw=true" width="200" />          
   <img src="https://github.com/maxrave-dev/SimpMusic/blob/jetpack_compose/asset/screenshot/4.png?raw=true" width="200" />          
   <img src="https://github.com/maxrave-dev/SimpMusic/blob/jetpack_compose/asset/screenshot/5.png?raw=true" width="200" /> </p> <p align="center">          
 <img src="https://github.com/maxrave-dev/SimpMusic/blob/jetpack_compose/asset/screenshot/6.png?raw=true" width="200" />          
  <img src="https://github.com/maxrave-dev/SimpMusic/blob/jetpack_compose/asset/screenshot/7.png?raw=true" width="200" />          
   <img src="https://github.com/maxrave-dev/SimpMusic/blob/jetpack_compose/asset/screenshot/8.png?raw=true" width="200" />          
   <img src="https://github.com/maxrave-dev/SimpMusic/blob/jetpack_compose/asset/screenshot/9.png?raw=true" width="200" /> </p> <p align="center">          
 <img src="https://github.com/maxrave-dev/SimpMusic/blob/jetpack_compose/asset/screenshot/10.png?raw=true" width="200" />          
  <img src="https://github.com/maxrave-dev/SimpMusic/blob/jetpack_compose/asset/screenshot/11.png?raw=true" width="200" />         
  <img src="https://github.com/maxrave-dev/SimpMusic/blob/jetpack_compose/asset/screenshot/12.png?raw=true" width="200" /> 
</p>

 #### More [screenshots](https://photos.app.goo.gl/AbieoXG5ctDrpwzp7) here.
 
 ## Data    
 - This app uses hidden API from YouTube Music with some tricks to get data from YouTube Music.    
- Use Spotify Web API and some tricks to get Spotify Canvas and Lyrics    
- Thanks to [InnerTune](https://github.com/z-huang/InnerTune/) for the idea to get data from YouTube Music. This repo is my inspiration to create this app.    
- Special thanks to [SmartTube](https://github.com/yuliskov/SmartTube). This repo help me to extract the streaming URL of YouTube Music.    
- My app is using [SponsorBlock](https://sponsor.ajay.app/) to skip sponsor in YouTube videos.    
- ReturnYouTubeDislike for getting information on votes    
- Lyrics data from LRCLIB. More information [LRCLIB](https://lrclib.net/)    
 
 ## Privacy    
 SimpMusic doesn't have any tracker or third-party server for collecting user data in FOSS version. If YouTube      
logged-in users enable "Send back to Google" feature, SimpMusic only uses YouTube Music Tracking API to send listening history and listening record of video to Google for better recommendations and      
supporting artist or YouTube Creator (For API reference,      
see [this](https://github.com/maxrave-dev/SimpMusic/blob/13f7ab6e5fa521b62a9fd31a1cefdc2787a1a8af/kotlinYtmusicScraper/src/main/java/com/maxrave/kotlinytmusicscraper/Ytmusic.kt#L639C4-L666C1)).

We collect crash data in the Full version to improve the app.
   

