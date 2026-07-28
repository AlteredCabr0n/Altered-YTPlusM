# YTPlusM
<p align="center">
  <img src="Resources/YTPlusM.png" width="435"><br>
  The best fork of an incredible enhancer for the popular video app on iOS, featuring over a hundred customizable options but with the latest version freed and with more tweaks than the original <a href="https://github.com/dayanch96/YTLite">YTPlus.</a>
</p>

<p align="center">
 <strong>Disclaimer</strong>
</p>

<p align="center">
  This project is an independent developer modification and is not affiliated with, authorized, maintained, sponsored, or endorsed by Google LLC or YouTube. All product and company names are trademarks of their respective holders.
</p>

<strong>Fork this repo to build yourself YTPlus and YTPlusM IPAs (with YouTube Plus from 5.1 to 5.2.2, no 5.2) without DRM Patreon subscription or <a href="https://t.me/Mark02workshop_official">join my telegram channel</a> for updates, communications and pre-built releases.
Don't know how to build YTPlus or YTPlusM? Read [How to build YouTube Plus and YTPlusM app using GitHub Actions](#how-to-build-youtube-plus-and-ytplusm-app-using-github-actions) and [What Means YTPlusM and YTPlusM DIY](#what-means-ytplusm-and-ytplusm-diy)</strong>


# MUST READ
**1. From June 1 2026 you do not need anymore [YTPlusM DIY](https://github.com/Mark02-2012/YTPlusM-DIY), but simply fork this repository (main branch). [YTPlusM DIY](https://github.com/Mark02-2012/YTPlusM-DIY) will not be updated anymore**

**2. I removed download table and all releases' files due to legal reason;**
### BUT I CREATED A NEW TELEGRAM CHANNEL FOR RELEASES! 👉[LINK TO JOIN](https://t.me/Mark02workshop_official)👈 (If t.me links do not work, search for this on Telegram: `@Mark02workshop_official`)

**3. I also created a new tweak to fix playback issues! You can find it in my new releases in the Telegram channel, in GitHub Actions and [in the official repository](https://github.com/Mark02-2012/YTPlaybackFix)**

## Table of Contents
- [Screenshots of YouTube Plus](#screenshots-of-youtube-plus)
- [Main Features of YouTube Plus](#main-features-of-youtube-plus)
- [FAQ](#faq)
- [Reviews](#reviews)
- [How to build YouTube Plus and YTPlusM app using GitHub Actions](#how-to-build-youtube-plus-and-ytplusm-app-using-github-actions)
- [How to find decrypted YouTube IPAs](#how-to-find-decrypted-youtube-ipas)
- [What Means YTPlusM and YTPlusM DIY](#what-means-ytplusm-and-ytplusm-diy)
- [YTPlusM versions changelog](#ytplusm-versions-changelog)
- [Supported YouTube Version](#supported-youtube-version)
- [Supported YouTube Version For iOS 15](#supported-youtube-version-for-ios-15)
- [Tweak Integration Details](#tweak-integration-details)
- [Special thanks](#special-thanks)

## Screenshots of YouTube Plus
<table>
   <tr>
      <td><img src="Resources/scr1.jpg" alt="Screenshot 1" /></td>
      <td><img src="Resources/scr2.jpg" alt="Screenshot 2" /></td>
      <td><img src="Resources/scr3.jpg" alt="Screenshot 3" /></td>
   </tr>
</table>

<details>
  <summary>More screenshots</summary>
  <table>
    <tr>
      <td><img src="Resources/scr4.jpg" alt="Screenshot 4" /></td>
      <td><img src="Resources/scr5.jpg" alt="Screenshot 5" /></td>
      <td><img src="Resources/scr6.jpg" alt="Screenshot 6" /></td>
    </tr>
    <tr>
      <td><img src="Resources/scr7.jpg" alt="Screenshot 7" /></td>
      <td><img src="Resources/scr8.jpg" alt="Screenshot 8" /></td>
      <td><img src="Resources/scr9.jpg" alt="Screenshot 9" /></td>
    </tr>
  </table>
</details>

## Main Features of YouTube Plus
  <li>Download videos, audio (including audio track selection), thumbnails, posts, and profile pictures</li>
  <li>Copy video, comment, and post information</li>
  <li>Interface customization: Remove feed elements, reorder tabs, enable OLED mode, and as use Shorts-only mode</li>
  <li>Player settings: Gestures, default quality, preferred audio track</li>
  <li>Save, Load and Restore settings. Clear cache once or automatically on app startup</li>
  <li>Built-in SponsorBlock</li>
  <li>And much, much more</li>
  <br>
  
**YouTube Plus preferences can be found in the YouTube Settings**

**All contributors are listed in the Contributors section**
**Used open-source libraries are listed in the Open Source Libraries section**

## FAQ
- [🇺🇸 English FAQ](FAQs/FAQ_EN.md)
- [🇷🇺 ЧаВо на Русском](FAQs/FAQ_RU.md)
- [🇮🇹 FAQ in Italiano](FAQs/FAQ_IT.md)
- [🇵🇱 FAQ po polsku](FAQs/FAQ_PL.md)

## Reviews
Review by [@qbap](https://github.com/qbap) on ONE Jailbreak: https://onejailbreak.com/blog/youtube-plus/

## How to build YouTube Plus and YTPlusM app using Github actions
> [!NOTE]
> If this your first time, complete following steps before starting:
>
> 1. Fork this repository using the fork button on the top right
> 2. On your forked repository, go to **Repository Settings** > **Actions**, enable **Read and Write** permissions.

<details>
  <summary>How to build YTPlus and YTPlusM app</summary>
  <ol>
    <li>Click on <strong>Sync fork</strong>, and if your branch is out-of-date, click on <strong>Update branch</strong>.</li>
    <li>Navigate to the <strong>Actions tab</strong> in your forked repository and select <strong>Create YouTube Plus or YTPlusM app</strong>.</li>
    <li>Click the <strong>Run workflow</strong> button located on the right side.</li>
    <li>Mark or unmark the tweaks you want to integrate. Learn more about them in the <a href="#tweak-integration-details">Tweak Integration Details</a> section.</li>
    <li>Prepare a decrypted .ipa file <em>(if you don't know where to find it read <a href="#how-to-find-decrypted-youtube-ipas">this</a>)</em>, then upload it to a file provider (e.g., filebin.net, filemail.com, Dropbox or catbox.moe are recommended). Paste the URL of the decrypted IPA file in the provided field.</li>
    <li><strong>NOTE:</strong> Make sure to provide a direct download link to the file, not a link to a webpage. Otherwise, the process will fail.</li>
    <li>Enter the YTLite version (starting from 5.1 to 5.2.2 crack, no 5.2; the latest is selected by default). You can also change the BundleID and Display Name if desired.</li>
    <li>Make sure all inputs are correct, then click <strong>Run workflow</strong> to start the process.</li>
    <li>Wait for the build to finish. You can download the YouTube Plus app from the releases section of your forked repo. (If you can't find the releases section, go to your forked repo and add /releases to the URL, i.e., github.com/user/YTLite/releases.)</li>
  </ol>
</details>

<details>
  <summary>How to build the YouTube Plus app with your own link for the YouTube Plus tweak (YTPLUSM TWEAKS NOT INTEGRATED)</summary>
  <ol>
    <blockquote>
      <p><strong>NOTE:</strong> This option is primarily intended for building the YouTube Plus app based on the beta file you have. In other cases, it is generally not needed.</p>
    </blockquote>
    <li>Click on <strong>Sync fork</strong>, and if your branch is out-of-date, click on <strong>Update branch</strong>.</li>
    <li>Navigate to the <strong>Actions tab</strong> in your forked repository and select <strong>[BETA] Build YouTube Plus app</strong>.</li>
    <li>Click the <strong>Run workflow</strong> button located on the right side.</li>
    <li>Mark or unmark the tweaks you want to integrate. Learn more about them in the <a href="#tweak-integration-details">Tweak Integration Details</a> section.</li>
    <li>Prepare a decrypted .ipa file <em>(if you don't know where to find it read <a href="#how-to-find-decrypted-youtube-ipas">this</a>)</em>, then upload it to a file provider (e.g., filebin.net, filemail.com, Dropbox or catbox.moe are recommended). Paste the URL of the decrypted IPA file in the provided field.</li>
    <li>Upload your beta tweak file to a file provider and paste direct link to the <strong>URL to the YouTube Plus tweak file</strong> field. You can also change the BundleID and Display Name if desired.</li>
    <li><strong>NOTE:</strong> Make sure to provide a direct download link to the file, not a link to a webpage. Otherwise, the process will fail.</li>
    <li>Make sure all inputs are correct, then click <strong>Run workflow</strong> to start the process.</li>
    <li>Wait for the build to finish. You can download the YouTube Plus app from the releases section of your forked repo. (If you can't find the releases section, go to your forked repo and add /releases to the URL, i.e., github.com/user/YTLite/releases.)</li>
  </ol>
</details>

## How to find decrypted YouTube IPAs

**If you have Telegram:**
1. Open Telegram
2. Search for "Eevee IPA Decrypter bot"
3. Start the bot and send him the link for YouTube on App Store
4. He will send you the latest YouTube decrypted IPA

**If you don't have Telegram/want another version of YouTube:**
> [!NOTE]
> For this make sure to disable all adblocks you have (NextDNS, ADGuard, Brave Shields, uBlock Origin etc.)

1. Open your browser and search "Decrypt Day"
2. Click the first link (It should be like decrypt . day the link, without spaces of course)
3. On the search bar, type "YouTube", click on "Search" and YouTube
4. Scroll down and click on "Download for free" to download the latest available version immediately, click on "Previous versions" instead to download older versions

## What Means YTPlusM and YTPlusM DIY
<details>
 <summary><strong>YTPlusM</strong></summary>
<p><strong>YTPlusM</strong> is a fork of <a href="https://github.com/dayanch96/YTLite">YTPlus</a> but with <strong>ten more tweaks integrated</strong> (<a href="https://github.com/fosterbarnes/YTweaks">YTweaks</a>, <a href="https://github.com/castdrian/Gonerino">Gonerino</a>, <a href="https://github.com/PoomSmart/YouSpeed">YouSpeed</a>, <a href="https://github.com/arichornlover/YTLowContrastMode">YTLowContrastMode</a>, <a href="https://github.com/VasirakCalgux/VolumeBoostYT">VolumeBoostYT</a>, <a href="https://github.com/PoomSmart/YouGetCaption">YouGetCaption</a>, my tweak <a href="https://github.com/Mark02-2012/YTPlaybackFix">YTPlaybackFix</a>, <a href="https://github.com/PoomSmart/YouChooseQuality">YouChooseQuality</a>, <a href="https://github.com/Tonwalter888/YouShare">YouShare</a> and <a href="https://github.com/mikey820/PleaseDontStopTheMusic">PleaseDontStopTheMusic</a>). <strong>YTPlus releases will not have those extra tweaks, but only YTLite and YouPiP, YTUHD, Return-YouTube-Dislikes, YouQuality, DontEatMyContent and YTABConfig.</strong></p>
</details>


<details>
  <summary><strong>YTPlusM DIY</strong></summary>
<p><strong>From April 14 2026, you can build the IPAs of YTPlusM with GitHub Actions! Fork this repo (to build YTPlusM with YTLite from 5.1 to 5.2.1, no 5.2, without DRM Patreon subscription); then go to Actions, workflows, "Create YouTube Plus or YTPlusM app", make sure it is selected the branch "main" and create your total functioning IPA!</strong>
View <a href=#how-to-build-youtube-plus-and-ytplusm-app-using-github-actions>How to build YouTube Plus and YTPlusM app using GitHub Actions</a> to learn how to create YTPlus and YTPlusM IPAs.
<li><strong>IMPORTANT: read <a href="#must-read">this</a></strong></li></p>

PS: DIY=DO IT YOURSELF
</details>

## YTPlusM versions changelog
<li><strong>1.0 (April 14 2026):</strong></li>
First release, added YTweaks, Gonerino and YouSpeed injectable
<li><strong>1.1 (May 5 2026):</strong></li>
Finally! YTLowContrastMode added, supporting also newest YT IPAs
<li><strong>1.2 (May 11 2026):</strong></li>
Added VolumeBoostYT and YouGetCaption
<li><strong>1.3 (June 24 2026):</strong></li>
Created by myself and added YTPlaybackFix
<li><strong>1.4 (July 12 2026):</strong></li>
Added YouChooseQuality, YouShare and PleaseDontStopTheMusic + replaced YTLowContrastMode with my new fork of it where I added a setting section
<li><strong>1.4.2 (July 17 2026):</strong></li>
Updated YouTube Plus from 5.2.1 to 5.2.2; cracked by <a href="https://www.reddit.com/u/shinewake/s/ZeFbBOkUAa">zarzel</a> and compiled the .deb by myself

## Supported YouTube Version
<ul>
   <li><strong>Latest confirmed:</strong> <em>21.13.6</em></li>
   <li><strong>Date tested:</strong> <em>Apr 1, 2026</em></li>
   <li><strong>YouTube Plus:</strong> <em>5.2 beta 4</em></li>
</ul>  

<strong>⚠️YTPlus 5.2b4 doesn't work with the latest versions of yt (from 21.14.4 and above), so use YTPlus from 5.2.1 to build YTPlusM with newest yt versions⚠️</strong>

<ul>
   <li><strong>Latest confirmed:</strong> <em>21.28.3</em></li>
   <li><strong>Recommended for working downloads:</strong> <em>21.24.3</em></li>
   <li><strong>Date tested:</strong> <em>July 12, 2026</em></li>
   <li><strong>YouTube Plus:</strong> <em>5.2.2</em></li>
</ul>

## Supported YouTube Version For iOS 15
<ul>
   <li><strong>Latest confirmed:</strong> <em>20.21.6</em></li>
   <li><strong>Date tested:</strong> <em>Apr 12 2026</em></li>
   <li><strong>YouTube Plus:</strong> <em>5.2.1</em></li>

## Tweak Integration Details
<details>
  <summary>YouPiP</summary>
  <p>YouPiP is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a> that enables the native Picture-in-Picture feature for videos in the iOS YouTube app.</p>
  <p><strong>YouPiP preferences</strong> are available in the <strong>YouTube settings</strong>.</p>
  <p>Source code and additional information are available <a href="https://github.com/PoomSmart/YouPiP">in PoomSmart's GitHub repository</a>.</p>
</details>

<details>
  <summary>YTUHD</summary>
  <p>YTUHD is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a> that unlocks 1440p (2K) and 2160p (4K) resolutions in the iOS YouTube app.</p>
  <p><strong>YTUHD preferences</strong> are available in the <strong>Video quality preferences</strong> section under <strong>YouTube settings</strong>.</p>
  <p>Source code and additional information are available <a href="https://github.com/PoomSmart/YTUHD">in PoomSmart's GitHub repository</a>.</p>
</details>

<details>
  <summary>Return YouTube Dislikes</summary>
  <p>Return YouTube Dislikes is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a> that brings back dislikes on the YouTube app.</p>
  <p><strong>Return YouTube Dislikes preferences</strong> are available in the <strong>YouTube settings</strong>.</p>
  <p>Source code and additional information are available <a href="https://github.com/PoomSmart/Return-YouTube-Dislikes">in PoomSmart's GitHub repository</a>.</p>
</details>

<details>
  <summary>YouQuality</summary>
  <p>YouQuality is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a> that allows to view and change video quality directly from the video overlay.</p>
  <p><strong>YouQuality can be enabled</strong> in the <strong>Video overlay</strong> section under <strong>YouTube settings</strong>.</p>
  <p>Source code and additional information are available <a href="https://github.com/PoomSmart/YouQuality">in PoomSmart's GitHub repository</a>.</p>
</details>

<details>
  <summary>DontEatMyContent</summary>
  <p>DontEatMyContent is a tweak developed by <a href="https://github.com/therealFoxster">therealFoxster</a> that prevents the Notch/Dynamic Island from munching on 2:1 video content in the iOS YouTube app.</p>
  <p><strong>DontEatMyContent preferences</strong> are available in the <strong>YouTube settings</strong>.</p>
  <p>Source code and additional information are available <a href="https://github.com/therealFoxster/DontEatMyContent">in therealFoxster's GitHub repository</a>.</p>
</details>

<details>
  <summary>YTABConfig</summary>
  <p>YTABConfig is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a> that permits to configures A/B settings in iOS YouTube app.</p>
  <p><strong>YTABConfig preferences</strong> are available in the <strong>YouTube settings</strong>.</p>
  <p>Source code and additional information are available <a href="https://github.com/PoomSmart/YTABConfig">in PoomSmart's GitHub repository</a>.</p>
</details>

<details>
 <summary>YTweaks (only on YTPlusM versions)</summary>
 <p>YTweaks is a tweak developed by <a href="https://github.com/fosterbarnes">fosterbarnes</a> that adds various tweaks for the iOS YouTube app.</p>
 <p><strong>YTweaks preferences</strong> are available in the <strong>YouTube settings</strong>.</p>
 <p>Source code and additional information are available <a href="https://github.com/fosterbarnes/YTweaks">in fosterbarnes' repository</a>.</p>
</details>

<details>
 <summary>Gonerino (only on YTPlusM versions)</summary>
 <p>Gonerino is a tweak developed by <a href="https://github.com/castdrian">castdrian</a>, a tweak to block specific videos, channels and words for the iOS YouTube app.</p>
 <p><strong>Gonerino preferences</strong> are available in the <strong>YouTube settings</strong>.</p>
 <p>Source code and additional information are available <a href="https://github.com/castdrian/Gonerino">in castdrian's repository</a>.</p>
</details>

<details>
 <summary>YouSpeed (only on YTPlusM versions)</summary>
 <p>YouSpeed is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a>, a tweak to view, change and add video speed options in the video overlay.</p>
 <p><strong>YouSpeed preferences</strong> are available in the <strong>Video overlay</strong> section under <strong>YouTube settings</strong>.</p>
 <p>Source code and additional information are available <a href="https://github.com/PoomSmart/YouSpeed">in PoomSmart's repository</a>.</p>
</details>

<details>
 <summary>YTLowContrastMode (only on YTPlusM versions)</summary>
 <p>YTLowContrastMode is a tweak developed by <a href="https://github.com/arichornlover">arichornlover</a>, a Tweak to make YT and YTMusic apps' Interface Low Contrast as possible and Easy on the eyes. (In the IPAs will be used my fork of it)</p>
 <p>YTLowContrastMode preferences are available in the <strong>YouTube settings</strong>.</p>
 <p>Source code and additional information are available <a href="https://github.com/Mark02-2012/YTLowContrastMode">in mine repository</a>.</p>
</details>

<details>
 <summary>VolumeBoostYT (only on YTPlusM versions)</summary>
 <p>VolumeBoostYT is a tweak developed by <a href="https://github.com/VasirakCalgux">VasirakCalgux</a> that provides an independent, gesture-based volume control for the YouTube app, completely separate from the system volume.</p>
 <p><strong>VolumeBoostYT preferences</strong> are available in the <strong>YouTube settings</strong>.</p>
 <p>Source code and additional information are available <a href="https://github.com/VasirakCalgux/VolumeBoostYT">in VasirakCalgux's repository</a>.</p>
</details>

<details>
 <summary>YouGetCaption (only on YTPlusM versions)</summary>
 <p>YouGetCaption is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a> that views and copies video caption from YouTube app from the video overlay.</p>
 <p><strong>YouGetCaption preferences</strong> are available in the <strong>Video overlay</strong> section under <strong>YouTube settings</strong>.</p>
 <p>Source code and additional information are available <a href="https://github.com/PoomSmart/YouGetCaption">in PoomSmart's repository</a>.</p>
</details>

<details>
 <summary>YTPlaybackFix (only on YTPlusM versions)</summary>
 <p>YTPlaybackFix is a tweak developed by me that try to fix playback issues by refreshing the video every time the error 14 appears ("something went wrong")</p>
 <p><strong>YTPlaybackFix preferences</strong> for the moment are <strong>not available</strong> as the tweak will refresh videos only if the error appears.</p>
 <p>Source code and additional information are available <a href="https://github.com/Mark02-2012/YTPlaybackFix">in my repository</a>.</p>
</details>

<details>
 <summary><strong>NEW!</strong> YouChooseQuality (only on YTPlusM versions)</summary>
 <p>YouChooseQuality is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a> that auto-selects the video quality of choice in iOS YouTube app.</p>
 <p><strong>YouChooseQuality preferences</strong> are available in the <strong>YouTube settings</strong>.</p>
 <p>Source code and additional information are available <a href="https://github.com/PoomSmart/YouChooseQuality">in PoomSmart's repository</a>.</p>
</details>

<details>
 <summary><strong>NEW!</strong> YouShare (only on YTPlusM versions)</summary>
 <p>YouShare is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a> (but I'm using <a href="https://github.com/Tonwalter888/YouShare">this fork</a> by <a href="https://github.com/Tonwalter888">TonWalter888</a>) that allows you to share videos faster in iOS YouTube app.</p>
 <p><strong>YouShare preferences</strong> are available in the <strong>Video Overlay</strong> section under <strong>YouTube settings</strong>.</p>
 <p>Source code and additional information are available <a href="https://github.com/Tonwalter888/YouShare">in Tonwalter888's repository</a>.</p>
</details>

<details>
 <summary><strong>NEW!</strong> PleaseDontStopTheMusic (only on YTPlusM versions)</summary>
 <p>PleaseDontStopTheMusic is a tweak developed by <a href="https://github.com/mikey820">mikey820</a> that prevents apps (e.g. Roblox) from pausing your background music.</p>
 <p><strong>PleaseDontStopTheMusic preferences</strong> are not available.</p>
 <p>Source code and additional information are available <a href="https://github.com/mikey820/PleaseDontStopTheMusic">in mikey820's repository</a>.</p>
</details>


## Special thanks
This project is alive also thanks to those fantastic guys:


<a href="https://github.com/dayanch96">Dayanch96</a>: **creator of YTPlus**


<a href="https://www.reddit.com/u/shinewake/s/ZeFbBOkUAa">shinewake</a>: **patcher of YTPlus 5.2.1 (he removed Patreon DRM)**


<a href="https://github.com/fosterbarnes">fosterbarnes</a>: **creator of YTweaks**


<a href="https://github.com/PoomSmart">PoomSmart</a>: **creator of YouSpeed, YouGetCaption, YouChooseQuality and YouShare**


<a href="https://github.com/arichornlover">arichornlover</a>: **creator of YTLowContrastMode**


<a href="https://github.com/castdrian">castdrian</a>: **creator of Gonerino**


<a href="https://github.com/VasirakCalgux">VasirakCalgux</a>: **creator of VolumeBoostYT**

<a href="https://github.com/mikey820">mikey820</a>: **creator of PleaseDontStopTheMusic**
