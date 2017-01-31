#iOS 10(.2) Artwork

##Synopsis
iOS 10.2 Artwork Extract using Anemone Car support. 
Extracting *Assets.car*

##Installation
There *isn't* really anything for you to install. Download a Zip or Clone the repo to use the artwork files to build themes.

If you want to use the below cardump commands you need to have **Anemone** installed and mTeriminal on the iOS device. Alternatively you can use SSH access and Terminal on a Mac/PC.

##Current Support
This is ongoing currently. I will mention **here** when it is complete. Only **@3x**  Images for now. **Frameworks** and SpringBoard.app are **extracted**. Whats left todo:

1. ~~Private Frameworks~~ **complete**
2. @2x Images
3. Added Images not in Assets.car
2. Stock Applications

##Motivation
I create iOS themes so this is useful to me and many of my peers. I would like to expand this later to include artwork for popular apps, but the initial goal is to show themers what they can now theme to try and get as many **complete** themes out there as possible.

##Cardump Commands
#### CoreServices
```cardump --dumpall /var/mobile/Documents/com.apple.springboard /System/Library/CoreServices/SpringBoard.app/Assets.car```

#### Frameworks
```cardump --dumpall /var/mobile/Documents/com.apple.AVKit /System/Library/Frameworks/AVKit.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.AddressBookUI /System/Library/Frameworks/AddressBookUI.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.ContactsUI /System/Library/Frameworks/ContactsUI.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.eventkitui /System/Library/Frameworks/EventKitUI.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.MapKit /System/Library/Frameworks/MapKit.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.MediaPlayer /System/Library/Frameworks/MediaPlayer.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.messageui /System/Library/Frameworks/MessageUI.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.PhotosUI /System/Library/Frameworks/PhotosUI.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.quicklook /System/Library/Frameworks/QuickLook.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.ReplayKit /System/Library/Frameworks/ReplayKit.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.SafariServices /System/Library/Frameworks/SafariServices.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.sociald.Social /System/Library/Frameworks/Social.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.uikit.Artwork /System/Library/Frameworks/UIKit.framework/Artwork.bundle/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.uikit.CarPlayArtwork /System/Library/Frameworks/UIKit.framework/CarPlayArtwork.bundle/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.VideoSubscriberAccount.VideoSubscriberAccountFramework /System/Library/Frameworks/VideoSubscriberAccount.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.sociald.Social /System/Library/Frameworks/Social.framework/Assets.car```

#### PrivateFrameworks

```cardump --dumpall /var/mobile/Documents/com.apple.ControlCenter /System/Library/PrivateFrameworks/ControlCenterUI.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.ControlCenterUIKit /System/Library/PrivateFrameworks/ControlCenterUIKit.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.chatkit /System/Library/PrivateFrameworks/ChatKit.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.CameraUI /System/Library/PrivateFrameworks/CameraUI.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.VoiceMemos.framework /System/Library/PrivateFrameworks/VoiceMemos.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.Stocks /System/Library/PrivateFrameworks/Stocks.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.UserNotificationsUIKit /System/Library/PrivateFrameworks/UserNotificationsUIKit.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.UpNextWidget /System/Library/PrivateFrameworks/UpNextWidget.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.iCloudQuotaUI /System/Library/PrivateFrameworks/iCloudQuotaUI.framework/Assets.car```

//empty
```cardump --dumpall /var/mobile/Documents/com.apple.MobileMusicPlayer.MusicCarDisplayUI /System/Library/PrivateFrameworks/MusicCarDisplayUI.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.weather-framework /System/Library/PrivateFrameworks/Weather.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.TVMLKit /System/Library/PrivateFrameworks/TVMLKit.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.ios.StoreKitUI /System/Library/PrivateFrameworks/StoreKitUI.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.VideosExtras /System/Library/PrivateFrameworks/VideosExtras.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.SpringBoardUIFramework /System/Library/PrivateFrameworks/SpringBoardUI.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.HealthUI /System/Library/PrivateFrameworks/HealthUI.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.TelephonyUI /System/Library/PrivateFrameworks/TelephonyUI.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.SpotlightUI /System/Library/PrivateFrameworks/SpotlightUI.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.SiriUI /System/Library/PrivateFrameworks/SiriUI.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.SearchUI /System/Library/PrivateFrameworks/SearchUI.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.PhotosUICore /System/Library/PrivateFrameworks/PhotosUICore.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.PhotoLibrary /System/Library/PrivateFrameworks/PhotoLibrary.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.MediaPlayerUI /System/Library/PrivateFrameworks/MediaPlayerUI.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.CameraUI /System/Library/PrivateFrameworks/CameraUI.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.preferences-ui-framework /System/Library/PrivateFrameworks/PreferencesUI.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.BatteryCenter /System/Library/PrivateFrameworks/BatteryCenter.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.MediaSocial /System/Library/PrivateFrameworks/MediaSocial.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.MapsSupport /System/Library/PrivateFrameworks/MapsSupport.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.Memories /System/Library/PrivateFrameworks/Memories.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.FitnessUI /System/Library/PrivateFrameworks/FitnessUI.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.RemindersUI /System/Library/PrivateFrameworks/RemindersUI.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.FlightUtilities /System/Library/PrivateFrameworks/FlightUtilities.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.PlacesKit /System/Library/PrivateFrameworks/PlacesKit.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.Pegasus /System/Library/PrivateFrameworks/Pegasus.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.CoreSuggestionsUI /System/Library/PrivateFrameworks/CoreSuggestionsUI.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.icloud.FMFUI /System/Library/PrivateFrameworks/FMFUI.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.helpkit /System/Library/PrivateFrameworks/HelpKit.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.VoiceTriggerUI /System/Library/PrivateFrameworks/VoiceTriggerUI.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.icloud.FMCoreUI /System/Library/PrivateFrameworks/FMCoreUI.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.CloudDocsUI /System/Library/PrivateFrameworks/CloudDocsUI.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.AnnotationKit /System/Library/PrivateFrameworks/AnnotationKit.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.HomeUI /System/Library/PrivateFrameworks/HomeUI.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.FuseUI /System/Library/PrivateFrameworks/FuseUI.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.GameCenterUI /System/Library/PrivateFrameworks/GameCenterUI.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.AuthKitUI /System/Library/PrivateFrameworks/AuthKitUI.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.CoreRoutine /System/Library/PrivateFrameworks/CoreRoutine.framework/Assets.car```

```cardump --dumpall /var/mobile/Documents/com.apple.Contacts.ContactsUICore /System/Library/PrivateFrameworks/ContactsUICore.framework/Assets.car```
