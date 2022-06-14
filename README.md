## For your information
Original EPG repository is in an archived state. See https://github.com/weareblahs/epg-old for the original one.
## Currently encountered problems
No Problems.
## Solved problems
- HITZ FM EPG Unavailable.
- BBC World News HD (String was not recognized as a valid DateTime)
  - Now using SiteIni by aa6my ([See here](https://github.com/weareblahs/epg/issues/2#issuecomment-841613022)), most of the channels that returned "String was not recognized as a valid DateTime" are fixed. All of the EPG data should be working now.
- Some channels unavailable on Astro.
  - Fixed: Changed the unavailable WebGrab ID from SD channel ID to HD channel ID.

## Updates
No guide updates tomorrow. Guide updates will continue on 14/6/2021.
FOUND: unifi PlayTV is powered by Huawei's Envision Video Platform.
 - [Here is an example of the EPG data for this platform.](https://gist.github.com/weareblahs/89fc50e4011094628749b6362187e669)
 - If someone made a SiteIni for unifi TV (Unencrypted), please contact me through my email (tanyuxuan2005@gmail.com) and I will process it as soon as possible to update the unifi TV Guide through unifi.com.my.
   - the SiteIni file will not be uploaded into GitHub.
## Auto-update bot information
The auto-update process will run daily.

## Important information
Do not fork it unless you want to change something on the configuration files, as it will not update the EPG by itself! If you want to update it, modify "GenerateAll.bat" to point to your WebGrab directory and repository directory. Make sure you have git setted up on the epg directory (you might have to use ``del .git`` to delete the existing one, then link it to your own fork). If you want to update it locally, delete all lines that contain the "git" command.

# About
This repository is for Malaysian TV Channels (and some Southeast Asian ones, too) and anyone can use it.

# What to know before using this EPG
- This EPG is free-of-charge and **NOT for sale** at any platforms! You can use these links for your YouTube tutorials, blogs, and more.
- All rights reserved to the respective companies. Special thanks to Astro and RTM for providing channel guide (and SingtelTV / Hong Kong Cable TV (Mainly for BBC Channels on unifi TV) for some of the channels).

# Currently available providers (Slowly Updating Right Now)
- Astro

- unifi TV (Partial Channels, **not including unifi Sports and unifi TV in-house channels** (like HyppSensasi and Dunia Sinema))
    
    - **Extra Stuffs Available!** [Watch unifi TV on your IPTV player, legally!](https://github.com/weareblahs/unifi-tv) (I made that repository, too)
    
- RTM Klik (RTM-operated Channels only, not including radio stations)

- MYTV Broadcasting (aka myFreeview) (Including RTM Radio Stations)

    # Providers Coming Soon

    - Sirius TV

# Current Channel Statistics
## Total Channels
- Astro: 192 (including Astro First, Astro Best and Radio Channels)
- unifi TV: 57 (Partial Channels Only)
- RTM Klik: 8
- MYTV Broadcasting: 21
## Channel Source
- Astro: astro.com.my
- unifi TV: astro.com.my / i-cable.com / singtel.com.sg / nowtv.now.com / peotv.com / sfr.fr (Luxe TV and France24) / sky.com
  - Inaccurate EPGs are Star Chinese Movies (Singapore Feed?), Now Jelli (Feed from Hong Kong, different from other areas), Sony SAB and Sony SET (Modified Feed by unifi TV to add local content), Colors Cineplex (UK Feed)
  - See Fix [Here](https://github.com/weareblahs/unifi-tv#epg-for-polimer-and-jaya-max) for Polimer and Jaya Max EPGs (Note that you must have a IPTV player capable of multiple EPG sources)
- RTM Klik: rtmklik.rtm.gov.my
- MYTV Broadcasting: rtmklik.rtm.gov.my / astro.com.my  
## XMLTV ID Type
- Astro: Channel Number
   - [Astro GO Exclusive Channels XMLID](https://weareblahs.github.io/epg/misc/AGEC.md)
- unifi TV: Channel Number  
- RTM Klik: [Channel List Here](https://weareblahs.github.io/epg/misc/RTMK.md)
- MYTV Broadcasting: Channel Number  
## Download Links / Links to copy into your IPTV player
- Astro: https://weareblahs.github.io/epg/astro.xml
  - Astro (Compressed): https://weareblahs.github.io/epg/compressed/astro.xml.gz
- unifi TV: https://weareblahs.github.io/epg/unifitv.xml  
  - unifi TV (Compressed): https://weareblahs.github.io/epg/compressed/unifitv.xml.gz
- RTM Klik: https://weareblahs.github.io/epg/rtmklik.xml  
  - RTM Klik (Compressed): https://weareblahs.github.io/epg/compressed/rtmklik.xml.gz
- MYTV Broadcasting: https://weareblahs.github.io/epg/mytv.xml    
  - MYTV Broadcasting (Compressed): https://weareblahs.github.io/epg/compressed/mytv.xml.gz
# Extras
No information available for any of your channels? Change the XMLTV ID to CHN to display a "Channel Information Not Available" notice on your EPG guide.

# What's this all about?
This repository contains all the XMLTV data for Malaysian TV providers. All grabbed from respective providers.

## Important information
Do not fork it unless you want to change something on the configuration files, as it will not update the EPG by itself! If you want to update it, modify "GenerateAll.bat" to point to your WebGrab directory and repository directory. Make sure you have git setted up on the epg directory (you might have to use ``del .git`` to delete the existing one, then link it to your own fork). If you want to update it locally, delete all lines that contain the "git" command.

# About
This repository is for Malaysian TV Channels (and some Southeast Asian ones, too) and anyone can use it.

# What to know before using this EPG
- This EPG is free-of-charge and **NOT for sale** at any platforms! You can use these links for your YouTube tutorials, blogs, and more.
- All rights reserved to the respective companies. Special thanks to Astro, RTM and unifi TV for providing the channel guide.

# Viewing EPG on your PC
You can download the EPG data (see "What's available in the guides") and open it with any compatible XMLTV viewer. I recommend using [ERD XMLTV Viewer](https://erdesigns.eu/app/freeware/view/4).

# Credits
Thanks to Khalis (@hantu08 on Telegram) for helping me doing some WebGrab+Plus stuffs, including:
 - Access to unifi TV Channel Guide directly from playtv@unifi  
 - Access to the new Astro Guide page (content.astro.com.my)
 - Access to the new RTM Klik SiteIni

# What's Available in the guides
| (Provider) | Astro | unifi TV | RTM Klik | MYTV Broadcasting / myFreeview |
|--|--|--|--|--|
| Channel Logos | ✓ | ✓ | ✓ (Not Transparent) | ✓ (RTM Klik sources are not transparent) |
| Channel Guide Images | ✓ | - (Except Astro sources) | - | - |
| Source | content.astro.com.my | playtv.unifi.com.my (Some channels uses same source as Astro) | rtmklik.rtm.gov.my | rtmklik.gov.my / content.astro.com.my | AqFad2811 rtmklik.gov.my / content.astro.com.my / playtv.unifi.com.my
| XMLTV EPG ID (tvg-id) | Channel Number ([See here for IDs for Astro GO Exclusive Channels](https://weareblahs.github.io/epg/misc/AGEC.md)) | Channel Name | [See Here](https://weareblahs.github.io/epg/misc/RTMK.md) | Channel Number Channel Number ([See here for IDs for Astro GO Exclusive Channels](https://weareblahs.github.io/epg/misc/AGEC.md)) | Channel Name | [See Here](https://weareblahs.github.io/epg/misc/RTMK.md) | Channel Number | ([See here for IDs for Astro GO Exclusive Channels](https://weareblahs.github.io/epg/misc/AGEC.md)) | Channel Name | [See Here](https://weareblahs.github.io/epg/misc/RTMK.md) | Channel Number Channel Number ([See here for IDs for Astro GO Exclusive Channels](https://weareblahs.github.io/epg/misc/AGEC.md)) | Channel Name | [See Here](https://weareblahs.github.io/epg/misc/RTMK.md) |
| XMLTV Links | https://weareblahs.github.io/epg/astro.xml  https://weareblahs.github.io/epg/astro.xml.gz | https://weareblahs.github.io/epg/unifitv.xml  https://weareblahs.github.io/epg/unifitv.xml.gz | https://weareblahs.github.io/epg/rtmklik.xml  https://weareblahs.github.io/epg/rtmklik.xml.gz | https://weareblahs.github.io/epg/mytv.xml  https://weareblahs.github.io/epg/mytv.xml.gz  https://raw.githubusercontent.com/AqFad2811/epg/main/singapore.xml  https://raw.githubusercontent.com/AqFad2811/epg/main/indonesia.xml https://raw.githubusercontent.com/AqFad2811/epg/main/astro.xml https://raw.githubusercontent.com/AqFad2811/epg/main/mytv.xml
| Guide Update Estimated Time | 56 minutes - 1 hours 30 minutes | 2 minutes - 10 minutes | 36 seconds - 2 minutes | 3 minutes - 4 minutes | 99 minutes - 9 minutes 
| Additional Channel Information ( "-" means Title and Description only) | Categories, Program Rating, Credits, Episode Number | Episode Number | Episode Number, Category | Program Rating, Episode Number |
Channel count depends on if the TV provider adds channels.
# Extras
No information available for any of your channels? Change the XMLTV ID to CHN to display a "Channel Information Not Available" notice on your EPG guide.

# What's Available in the guides
| (Provider) | Astro MYTV Broadcasting Unifi TV | meWATCH Indonesia Astro MYTV Broadcasting 
|--|--|--|--|--|
| Channel Logos | ✓ | ✓ | ✓ (Not Transparent) | ✓ (RTM Klik sources are not transparent) |
| Channel Guide Images | ✓ | - (Except Astro sources) | - | - |
| Source | mewatch.sg | content.astro.com.my (Some channels uses same source as Astro) | Indonesia | rtmklik.gov.my / content.astro.com.my | AqFad2811 rtmklik.gov.my / content.astro.com.my / playtv.unifi.com.my
| XMLTV EPG ID (tvg-id) | Channel Number ([See here for IDs for Astro GO Exclusive Channels](https://weareblahs.github.io/epg/misc/AGEC.md)) | Channel Name | [See Here](https://weareblahs.github.io/epg/misc/RTMK.md) | Channel Number Channel Number ([See here for IDs for Astro GO Exclusive Channels](https://weareblahs.github.io/epg/misc/AGEC.md)) | Channel Name | [See Here](https://weareblahs.github.io/epg/misc/RTMK.md) | Channel Number | ([See here for IDs for Astro GO Exclusive Channels](https://weareblahs.github.io/epg/misc/AGEC.md)) | Channel Name | [See Here](https://weareblahs.github.io/epg/misc/RTMK.md) | Channel Number Channel Number ([See here for IDs for Astro GO Exclusive Channels](https://weareblahs.github.io/epg/misc/AGEC.md)) | Channel Name | [See Here](https://weareblahs.github.io/epg/misc/RTMK.md) |
| XMLTV Links | https://raw.githubusercontent.com/AqFad2811/epg/main/singapore.xml | https://raw.githubusercontent.com/AqFad2811/epg/main/indonesia.xml | https://raw.githubusercontent.com/AqFad2811/epg/main/astro.xml | https://raw.githubusercontent.com/AqFad2811/epg/main/mytv.xml |
| Guide Update Estimated Time | 56 minutes - 1 hours 30 minutes | 2 minutes - 10 minutes | 36 seconds - 2 minutes | 3 minutes - 4 minutes | 99 minutes - 9 minutes 
| Additional Channel Information ( "-" means Title and Description only) | Categories, Program Rating, Credits, Episode Number | Episode Number | Episode Number, Category | Program Rating, Episode Number |
Channel count depends on if the TV provider adds channels.
# Extras
No information available for any of your channels? Change the XMLTV ID to CHN to display a "Channel Information Not Available" notice on your EPG guide.

EPG 
https://iptv-org.github.io/epg/guides/id/beinsports.com.epg.xml
https://iptv-org.github.io/epg/guides/id/vidio.com.epg.xml
https://iptv-org.github.io/epg/guides/id/transvision.co.id.epg.xml
https://iptv-org.github.io/epg/guides/id-id/mncvision.id.epg.xml
https://iptv-org.github.io/epg/guides/id-en/mncvision.id.epg.xml
https://iptv-org.github.io/epg/guides/my/beinsports.com.epg.xml
https://iptv-org.github.io/epg/guides/my/astro.com.my.epg.xml
https://iptv-org.github.io/epg/guides/sg/starhubtvplus.com.epg.xml
