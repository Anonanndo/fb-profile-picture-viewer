# Facebook Profile Picture Viewer

![](https://i.imgur.com/oysTQEP.png)

Bypass the Facebook profile picture guard and see user's profile picture in __full size__ 📷

### How to Install
[Click Here to Download from Chrome Web Store](https://chrome.google.com/webstore/detail/facebook-profile-picture/olhdholihhioakdjhfhligfehfjjfeoc?hl=fr&authuser=0)


### How to Install (From Github):

0. Download this repository
1. Navigate to **chrome://extensions/** 
2. Ensure the checkbox labeled **Developer mode** is enabled. 
3. Click the button labeled **Load unpacked extension...**
4. Select the directory 

### How To Use

0. Open victim's profile
1. Right-Click and Select "Unlock full size profile picture"

### How does this extension works

The trick is simple : 

1. Fetch `https://mbasic.facebook.com/USERNAME` and get "Profile id"
2. Fetch `https://m.facebook.com/composer/ocelot/async_loader/?publisher=feed` and get "Facebook User Access Token"
3. Open this url to get full size image: `
https://graph.facebook.com/${profile_id}/picture?width=5000&access_token=${access_token}
`

### Note

I highly recommend to not use these kinds of tricks to find and view private profile pictures, because all people like to maintain some privacy and they don't want others to disclose their privacy.
