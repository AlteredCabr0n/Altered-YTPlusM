<h1 align="center">Altered-YTPlusM</h1>
<p align="center">
  <img src="Resources/AlteredYTPlusM1.png" width="435"><br>
  An <strong>altered</strong> version of the BEST fork of enhancer for YouTube on iOS, <a href="https://github.com/Mark02-2012/YTPlusM">YTPlusM</a>. Featuring over hundred customizable options but with the latest version freed and with more tweaks than  <a href="https://github.com/dayanch96/YTLite">YouTube Plus.</a>
</p>

<h3 align="center">
 <strong>Disclaimer</strong>
</h3>

<p align="center">
  This project is an independent developer modification and is not affiliated with, authorized, maintained, sponsored, or endorsed by Google LLC or YouTube. All product and company names are trademarks of their respective holders.
</p>

<h3 align="center">
   <strong>More info</strong>
</h3>




**Don't know how to build iPA? Read [How-to Create the YTPlusM app(s) D.I.Y.](#how-to-create-the-ytplusm-apps-diy) and ['YTPlusM' vs 'Altered-YTPlusM'](#ytplusm-vs-altered-ytplusm)**

## Table of Contents
- [Screenshots](#screenshots)
- [Main Features](#main-features)
- [FAQ](#faq)
- ['YTPlusM' vs 'Altered-YTPlusM'](#ytplusm-vs-altered-ytplusm)
- [How-to Create the YTPlusM app(s) D.I.Y.](#how-to-create-the-ytplusm-apps-diy)
- [How-to Generate .DEB files](#how-to-generate-deb-files)
- [Supported YouTube Version](#supported-youtube-version)
- [Supported YouTube Version For iOS 15](#supported-youtube-version-for-ios-15)
- [Tweak Integration Details](#tweak-integration-details)
- [Special thanks](#special-thanks)

## Screenshots
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

## Main Features
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

## 'YTPlusM' vs 'Altered-YTPlusM'
<details>
> [!NOTE]
> You can build **both** in this repo:
 <summary><strong>YTPlusM</strong></summary>
<p><strong>YTPlusM</strong> is a fork of <a href="https://github.com/dayanch96/YTLite">YTPlus</a> but with <strong>7 more tweaks</strong> injected by Mark02-2012 with GitHub Actions (<a href="https://github.com/fosterbarnes/YTweaks">YTweaks</a>, <a href="https://github.com/castdrian/Gonerino">Gonerino</a>, <a href="https://github.com/PoomSmart/YouSpeed">YouSpeed</a>, <a href="https://github.com/arichornlover/YTLowContrastMode">YTLowContrastMode</a>, <a href="https://github.com/VasirakCalgux/VolumeBoostYT">VolumeBoostYT</a>, <a href="https://github.com/PoomSmart/YouGetCaption">YouGetCaption</a> and <a href="https://github.com/Mark02-2012/YTPlaybackFix">YTPlaybackFix</a>).</p>
</details>

<details>
  <summary><strong>Altered-YTPlusM</strong></summary>
<p><strong>YTPlusM</strong> is a fork of <a href="https://github.com/Mark02-2012/YTPlusM">Mark02-2012's fork</a> and adding EVEN MORE more tweaks injected by me (<a href="https://github.com/PoomSmart/YouMute">YouMute</a>, <a href="https://github.com/thaibm92/YouTimeStamp">YouTimeStamp</a>, <a href="https://github.com/oceandrift7/YTLocalQueue">YTLocalQueue</a>).</p>
</details>


## How-to Create the YTPlusM app(s) D.I.Y.
<details>
  <summary>BUILD Altered-YTPlusM</summary>
  <ol>
     <p><blockquote>
      <p><strong>NOTE:</strong>
      If this NOT your first time, you can skip complete the first 2 steps.</p>
     </blockquote></p>
    <li>Fork <a href="https://github.com/AlteredCabr0n/Altered-YTPlusM">this repository</a> using the fork button on the top right</li>
    <li>On your forked repository (eg. "github.com/yourusername/Altered-YTPlusM"), go to <strong>Actions</strong> tab, enable workflows <strong>I understand my workflows, go ahead and enable them</strong>.</li>
    <li>Click on <strong>Sync fork</strong>, and if your branch is out-of-date, click on <strong>Update branch</strong>.</li>
    <li>Navigate to the <strong>Actions tab</strong> in your forked repository and select <strong>Create YTPlusM iPA [Altered-Patch]</strong>.</li>
    <li>Click the <strong>Run workflow</strong> button located on the right side.</li>
    <li>Tick or untick the tweaks you want to integrate. Learn more about them in the <a href="#tweak-integration-details">Tweak Integration Details</a> section.</li>
    <li>Prepare a decrypted .ipa file (if you don't know where to find it, create one yourself or get from other places sites (e.g. decryptedappstore, decrypt.day)</li> 
    <li>Upload the decrypted .ipa file to a file provider (e.g., <a href="https://litterbox.catbox.moe">litterbox.catbox</a>). Paste the URL of the decrypted IPA file in the provided field.</li>
    <li><strong>NOTE:</strong> Make sure to provide a direct download link to the file, not a link to a webpage. Otherwise, the process will fail.</li>
    <li>Enter the tweak version from the releases (the latest release is selected by default). You can also change the BundleID and Display Name if desired.</li>
    <li>Make sure all inputs are correct, then click <strong>Run workflow</strong> to start the process.</li>
    <li>Wait for the build to finish. You can download the YouTube Plus app from the releases section of your forked repo. (If you can't find the releases section, go to your forked repo and add /releases to the URL, i.e., github.com/yourusername/Altered-YTPlusM/releases)

**NOTE:** This builds YTPlusM with YTPlus's DRM removed.</li>
   </ol>
</details>

<details>
  <summary>BUILD YouTube Plus w/ your own URL</summary>
  <ol>
    <p><blockquote>
      <p><strong>NOTE:</strong> This option is primarily intended for building the YouTube Plus app using your own beta file and YTPlusM tweaks WILL NOT BE INTEGRATED. In other cases, it is generally not needed.</p>
    </blockquote></p>
   <p><blockquote>
      <p><strong>NOTE:</strong>
      If this NOT your first time, you can skip complete the first 2 steps.</p>
     </blockquote></p>
    <li>Fork <a href="https://github.com/AlteredCabr0n/Altered-YTPlusM">this repository</a> using the fork button on the top right</li>
    <li>On your forked repository (eg. "github.com/yourusername/Altered-YTPlusM"), go to <strong>Actions</strong> tab, enable workflows <strong>I understand my workflows, go ahead and enable them</strong>.</li>
    <li>Click on <strong>Sync fork</strong>, and if your branch is out-of-date, click on <strong>Update branch</strong>.</li>
    <li>Navigate to the <strong>Actions tab</strong> in your forked repository and select <strong>[BETA] Create YouTube Plus app</strong>.</li>
    <li>Click the <strong>Run workflow</strong> button located on the right side.</li>
    <li>Tick or untick the tweaks you want to integrate. Learn more about them in the <a href="#tweak-integration-details">Tweak Integration Details</a> section.</li>
    <li>Prepare a decrypted .ipa file (if you don't know where to find it, create one yourself or get from other places sites (e.g. decryptedappstore, decrypt.day)</li> 
    <li>Upload the decrypted .ipa file to a file provider (e.g., <a href="https://litterbox.catbox.moe">litterbox.catbox</a>). Paste the URL of the decrypted IPA file in the provided field.</li>
    <li>Upload your beta tweak file to a file provider and paste direct link to the <strong>URL to the YouTube Plus tweak file</strong> field. You can also change the BundleID and Display Name if desired.</li>
    <li><strong>NOTE:</strong> Make sure to provide a direct download link to the file, not a link to a webpage. Otherwise, the process will fail.</li>
    <li>Make sure all inputs are correct, then click <strong>Run workflow</strong> to start the process.</li>
    <li>Wait for the build to finish. You can download the YouTube Plus app from the releases section of your forked repo. (If you can't find the releases section, go to your forked repo and add /releases to the URL, i.e., github.com/yourusername/Altered-YTPlusM/releases)</li>
  </ol>
</details>

## How-to Generate .DEB files
<details>
  <summary>How to generate deb files of all the integrated tweaks (also for jailbreak)</summary>
  <ol>
    <blockquote>
      <p><strong>NOTE:</strong> All generated .deb files are built as rootless (iphoneos-arm64), except for YTPlus, which is compiled in rootful format (iphoneos-arm). If you are using a rootless jailbreak, please convert the YTPlus package using Derootifier.</p>
    </blockquote>
    <li>If you already have a fork of MY repository Altered-YTPlusM, click on <strong>Sync fork</strong>, and if your branch is out-of-date, click on <strong>Update branch</strong>.</li>
    <li>Navigate to the <strong>Actions tab</strong> in your forked repository and select <strong>Generate deb files</strong>.</li>
    <li>Click the <strong>Run workflow</strong> button located on the right side.</li>
    <li>Mark or unmark the tweaks you want to generate. Learn more about them in the <a href="#tweak-integration-details">Tweak Integration Details</a> section.</li>
    <li>Enter the YTPlus/Lite version (starting from 5.1 to 5.2.2 cracked, no 5.2; <strong>the latest is selected by default</strong>).</li>
    <li>Make sure all inputs are correct, then click <strong>Run workflow</strong> to start the process.</li>
    <li>Wait for the build to finish. You can download the generated debs from the Artifacts section when the build has finished. (If you can't find the Artifacts section, reload the page.)</li>
  </ol>
</details>


## Supported YouTube Version
<ul>
   <li><strong>Latest confirmed:</strong> <em>21.33.6</em></li>
   <li><strong>Recommended for working downloads:</strong> <em>21.24.3</em></li>
   <li><strong>Date tested:</strong> <em>August 24, 2026</em></li>
   <li><strong>YouTube Plus:</strong> <em>5.2.2</em></li>
</ul>
<strong>⚠️YTPlus 5.2b4 doesn't work with the latest versions of yt (from 21.14.4 and above), so use YTPlus 5.2.1 to build YTPlusM with newest yt versions⚠️</strong>

## Supported YouTube Version For iOS 15
<ul>
   <li><strong>Latest confirmed:</strong> <em>20.21.6</em></li>
   <li><strong>Date tested:</strong> <em>July 24, 2026</em></li>
   <li><strong>YouTube Plus:</strong> <em>5.2.2</em></li>
<p>View <a href="https://github.com/Mark02-2012/YTPlus_by_Mark02/releases/tag/5.2b4_20.21.6">this release (YouTube Plus)</a> and <a href="https://github.com/Mark02-2012/YTPlusM/releases/tag/5.2.1_20.21.6(54)">this release (YTPlusM)</p>
</ul>

## Tweak Integration Details
<details>
  <summary>YouPiP</summary>
  <p><p>YouPiP is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a> that enables the native Picture-in-Picture feature for videos in the iOS YouTube app.</p>
  <p><strong>YouPiP preferences</strong> are available in the <strong>YouTube settings</strong>.</p>
  <p>Source code and additional information are available <a href="https://github.com/PoomSmart/YouPiP">in PoomSmart's GitHub repository</a>.</p></p>
</details>

<details>
  <summary>YouMute</summary>
  <p><p>YouPiP is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a> that enables the native Picture-in-Picture feature for videos in the iOS YouTube app.</p>
  <p><strong>YouMute can be enabled</strong> in the <strong>Video overlay</strong> section under <strong>YouTube settings</strong>.</p>
  <p>Source code and additional information are available <a href="https://github.com/PoomSmart/YouMute">in PoomSmart's GitHub repository</a>.</p></p>
</details>

<details>
  <summary>YouTimeStamp</summary>
  <p><p>YouTimeStamp is an iOS YouTube Tweak made for YTVideoOverlay. Forked by <a href="https://github.com/thaibm92">thaibm92</a> Adds a button that lets you copy your timestamp in the Video Player.</p>
  <p><strong>YouTimeStamp can be enabled</strong> in the <strong>Video overlay</strong> section under <strong>YouTube settings</strong>.</p>
  <p>Find the latest updated files here: https://github.com/thaibm92/YouTimeStamp</p></p>
</details>

<details>
  <summary>YTLocalQueue</summary>
  <p><p>YTLocalQueue is a tweak forked by <a href="https://github.com/oceandrift7">oceandrift7</a>. A YouTube tweak for creating + managing a video queue LOCALLY.</p>
  <p><strong>YTLocalQueue preferences</strong> can be found in the <strong>YouTube settings</strong>.</p>
  <p>Find the latest updated dylib/deb files here: https://github.com/oceandrift7/YTLocalQueue</p></p>
</details>

<details>
  <summary>YTUHD</summary>
  <p><p>YTUHD is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a> that unlocks 1440p (2K) and 2160p (4K) resolutions in the iOS YouTube app.</p>
  <p><strong>YTUHD preferences</strong> are available in the <strong>Video quality preferences</strong> section under <strong>YouTube settings</strong>.</p>
  <p>Source code and additional information are available <a href="https://github.com/PoomSmart/YTUHD">in PoomSmart's GitHub repository</a>.</p></p>
</details>

<details>
  <summary>Return YouTube Dislikes</summary>
  <p><p>Return YouTube Dislikes is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a> that brings back dislikes on the YouTube app.</p>
  <p><strong>Return YouTube Dislikes preferences</strong> are available in the <strong>YouTube settings</strong>.</p>
  <p>Source code and additional information are available <a href="https://github.com/PoomSmart/Return-YouTube-Dislikes">in PoomSmart's GitHub repository</a>.</p></p>
</details>

<details>
  <summary>YouQuality</summary>
  <p><p>YouQuality is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a> that allows to view and change video quality directly from the video overlay.</p>
  <p><strong>YouQuality can be enabled</strong> in the <strong>Video overlay</strong> section under <strong>YouTube settings</strong>.</p>
  <p>Source code and additional information are available <a href="https://github.com/PoomSmart/YouQuality">in PoomSmart's GitHub repository</a>.</p></p>
</details>

<details>
  <summary>DontEatMyContent</summary>
  <p><p>DontEatMyContent is a tweak developed by <a href="https://github.com/therealFoxster">therealFoxster</a> that prevents the Notch/Dynamic Island from munching on 2:1 video content in the iOS YouTube app.</p>
  <p><strong>DontEatMyContent preferences</strong> are available in the <strong>YouTube settings</strong>.</p>
  <p>Source code and additional information are available <a href="https://github.com/therealFoxster/DontEatMyContent">in therealFoxster's GitHub repository</a>.</p></p>
</details>

<details>
  <summary>YTABConfig</summary>
  <p><p>YTABConfig is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a> that permits to configures A/B settings in iOS YouTube app.</p>
  <p><strong>YTABConfig preferences</strong> are available in the <strong>YouTube settings</strong>.</p>
  <p>Source code and additional information are available <a href="https://github.com/PoomSmart/YTABConfig">in PoomSmart's GitHub repository</a>.</p></p>
</details>

<details>
 <summary>YTweaks</summary>
 <p><p>YTweaks is a tweak developed by <a href="https://github.com/fosterbarnes">fosterbarnes</a> that adds various tweaks for the iOS YouTube app.</p>
 <p><strong>YTweaks preferences</strong> are available in the <strong>YouTube settings</strong>.</p>
 <p>Source code and additional information are available <a href="https://github.com/fosterbarnes/YTweaks">in fosterbarnes' repository</a>.</p>
 <p><em>From now, YOU can build your version of YTPlusM! View <a href=#how-to-create-the-ytplusm-apps-diy>How-to Create the YTPlusM app(s) D.I.Y.</a> and <a href=#ytplusm-vs-altered-ytplusm>'YTPlusM' vs 'Altered-YTPlusM'</a></em></p></p>
</details>

<details>
 <summary>Gonerino</summary>
 <p><p>Gonerino is a tweak developed by <a href="https://github.com/castdrian">castdrian</a>, a tweak to block specific videos, channels and words for the iOS YouTube app.</p>
 <p><strong>Gonerino preferences</strong> are available in the <strong>YouTube settings</strong>.</p>
 <p>Source code and additional information are available <a href="https://github.com/castdrian/Gonerino">in castdrian's repository</a>.</p>
 <p><em>Gonerino is available only from <a href="https://github.com/Mark02-2012/YTPlusM/releases/tag/5.2b4_21.13.6_updated_YTPlusM">YTPlusM 21.13.6 updated</a> and <a href="https://github.com/Mark02-2012/YTPlusM/releases/tag/5.2b4_20.21.6_YTweaks">YTPlusM 20.21.6 for iOS 15</a> pre-built releases, but you can build your version of YTPlusM now! View <a href=#how-to-create-the-ytplusm-apps-diy>How to build YTPlusM app(s) using GitHub Actions</a> and <a href=#ytplusm-vs-altered-ytplusm>'YTPlusM' vs 'Altered-YTPlusM'</a></em></p></p>
</details>

<details>
 <summary>YouSpeed</summary>
 <p><p>YouSpeed is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a>, a tweak to view, change and add video speed options in the video overlay.</p>
 <p><strong>YouSpeed preferences</strong> are available in the <strong>Video overlay</strong> section under <strong>YouTube settings</strong>.</p>
 <p>Source code and additional information are available <a href="https://github.com/PoomSmart/YouSpeed">in PoomSmart's repository</a>.</p>
 <p><em>YouSpeed is available only from <a href="https://github.com/Mark02-2012/YTPlusM/releases/tag/5.2b4_21.13.6_updated_YTPlusM">YTPlusM 21.13.6 updated</a> and <a href="https://github.com/Mark02-2012/YTPlusM/releases/tag/5.2b4_20.21.6_YTweaks">YTPlusM 20.21.6 for iOS 15</a> pre-built releases, but you can build your version of YTPlusM now! View <a href=#how-to-create-the-ytplusm-apps-diy>How-to Create the YTPlusM app(s) D.I.Y.</a> and <a href=#ytplusm-vs-altered-ytplusm>'YTPlusM' vs 'Altered-YTPlusM'</a></em></p></p>
</details>

<details>
 <summary>YTLowContrastMode</summary>
 <p><p>YTLowContrastMode is a tweak developed by <a href="https://github.com/arichornlover">arichornlover</a>, a Tweak to make YT and YTMusic apps' Interface Low Contrast as possible and Easy on the eyes.</p>
 <p><strong>YTLowContrastMode preferences are not available</strong>; the tweak <strong>is already activated</strong> when you choose to inject it.</p>
 <p>Source code and additional information are available <a href="https://github.com/arichornlover/YTLowContrastMode">in arichornlover's repository</a>.</p>
 <p><em>YTLowContrastMode is available only from <a href="https://github.com/Mark02-2012/YTPlusM/releases/tag/5.2.1_21.18.4_updated">YTPlusM 5.2.1 and 21.18.4 updated</a> pre-built release, but you can build your version of YTPlusM now! View <a href=#how-to-create-the-ytplusm-apps-diy>How-to Create the YTPlusM app(s) D.I.Y.</a> and <a href=#ytplusm-vs-altered-ytplusm>'YTPlusM' vs 'Altered-YTPlusM'</a></em></p></p>
</details>

<details>
 <summary>VolumeBoostYT</summary>
 <p><p>VolumeBoostYT is a tweak developed by <a href="https://github.com/VasirakCalgux">VasirakCalgux</a> that provides an independent, gesture-based volume control for the YouTube app, completely separate from the system volume.</p>
 <p><strong>VolumeBoostYT preferences</strong> are available in the <strong>YouTube settings</strong>.</p>
 <p>Source code and additional information are available <a href="https://github.com/VasirakCalgux/VolumeBoostYT">in VasirakCalgux's repository</a>.</p>
 <p><em>VolumeBoostYT is available only from <a href="https://github.com/Mark02-2012/YTPlusM/releases/tag/5.2.1_21.19.2(56)">YTPlusM 5.2.1 and 21.19.2</a> pre-built release, but you can build your version of YTPlusM now! View <a href=#how-to-create-the-ytplusm-apps-diy>How-to Create the YTPlusM app(s) D.I.Y.</a> and <a href=#ytplusm-vs-altered-ytplusm>'YTPlusM' vs 'Altered-YTPlusM'</a></em></p></p>
</details>

<details>
 <summary>YouGetCaption</summary>
 <p><p>YouGetCaption is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a> that views and copies video caption from YouTube app from the video overlay.</p>
 <p><strong>YouGetCaption preferences</strong> are available in the <strong>Video overlay</strong> section under <strong>YouTube settings</strong>.</p>
 <p>Source code and additional information are available <a href="https://github.com/PoomSmart/YouGetCaption">in PoomSmart's repository</a>.</p>
 <p><em>YouGetCaption is available only from <a href="https://github.com/Mark02-2012/YTPlusM/releases/tag/5.2.1_21.19.2(56)">YTPlusM 5.2.1 and 21.19.2</a> pre-built release, but you can build your version of YTPlusM now! View <a href=#how-to-create-the-ytplusm-apps-diy>How-to Create the YTPlusM app(s) D.I.Y.</a> and <a href=#ytplusm-vs-altered-ytplusm>'YTPlusM' vs 'Altered-YTPlusM'</a></em></p></p>
</details>

<details>
 <summary>YTPlaybackFix</summary>
 <p><p>YTPlaybackFix is a tweak developed by <a href="https://github.com/Mark02-2012">Mark02-2012</a> that tries to fix playback issues by refreshing the video every time the error 14 appears ("something went wrong")</p>
     <p><blockquote>
        <p><strong>NOTE:</strong>
           YTPlaybackFix preferences for the moment are not available as the tweak will refresh
           videos only if the error appears.</p>
     </blockquote></p>
 <p>Source code and additional information are available <a href="https://github.com/Mark02-2012/YTPlaybackFix">in my repository</a>.</p>
 <p><em>You can build your version of YTPlusM now! View <a href=#how-to-create-the-ytplusm-apps-diy>How-to Create the YTPlusM app(s) D.I.Y.</a> and <a href=#ytplusm-vs-altered-ytplusm>'YTPlusM' vs 'Altered-YTPlusM'</a> (or <a href="https://t.me/Mark02workshop_official">join my telegram channel</a> to download the pre-built IPA with this new tweak)</em></p></p>
</details>

<details>
 <summary>YouChooseQuality</summary>
 <p><p>YouChooseQuality is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a> that auto-selects the video quality of choice in iOS YouTube app.</p>
 <p><strong>YouChooseQuality preferences</strong> are available in the <strong>YouTube settings</strong>.</p>
 <p>Source code and additional information are available <a href="https://github.com/PoomSmart/YouChooseQuality">in PoomSmart's repository</a>.</p></p>
</details>

<details>
 <summary><strong>YouShare</summary>
 <p><p>YouShare is a tweak developed by <a href="https://github.com/PoomSmart">PoomSmart</a> (but I'm using <a href="https://github.com/Tonwalter888/YouShare">this fork</a> by <a href="https://github.com/Tonwalter888">TonWalter888</a>) that allows you to share videos faster in iOS YouTube app.</p>
 <p><strong>YouShare preferences</strong> are available in the <strong>Video Overlay</strong> section under <strong>YouTube settings</strong>.</p>
 <p>Source code and additional information are available <a href="https://github.com/Tonwalter888/YouShare">in Tonwalter888's repository</a>.</p></p>
</details>

<details>
 <summary>PleaseDontStopTheMusic</summary>
 <p><p>PleaseDontStopTheMusic is a tweak developed by <a href="https://github.com/mikey820">mikey820</a> that prevents apps (e.g. Roblox) from pausing your background music.</p>
 <p><strong>PleaseDontStopTheMusic preferences</strong> are not available.</p>
 <p>Source code and additional information are available <a href="https://github.com/mikey820/PleaseDontStopTheMusic">in mikey820's repository</a>.</p></p>
</details>

<details>
 <summary>YouLoop</summary>
 <p><p>YouLoop is a tweak developed by <a href="https://github.com/bhackel">bhackel</a> that adds a player button to enable/disable looping on the current video.</p>
 <p><strong>YouLoop preferences</strong> are available in the <strong>Video Overlay</strong> section under <strong>YouTube settings</strong>.</p>
 <p>Source code and additional information are available <a href="https://github.com/bhackel/YouLoop">in bhackel's repository</a>.</p></p>
</details>





## Special thanks
This project is alive **only** thanks to those guys:


<a href="https://github.com/dayanch96">Dayanch96</a>: **creator of YTPlus/YTLite**


<a href="https://www.reddit.com/u/shinewake/s/ZeFbBOkUAa">shinewake</a>: **patcher of YTPlus/YTLite (he removed Patreon DRM)**


<a href="https://github.com/bpetrynski">bpetrynski</a>: **creator of YTLocalQueue**


<a href="https://github.com/Mark02-2012">Mark02-2012</a>: **creator of YTPlaybackFix**


<a href="https://github.com/fosterbarnes">fosterbarnes</a>: **creator of YTweaks**


<a href="https://github.com/PoomSmart">PoomSmart</a>: **creator of YouSpeed, YouGetCaption, YouChooseQuality, YouShare and YouMute**


<a href="https://github.com/arichornlover">arichornlover</a>: **creator of YTLowContrastMode and YouTimeStamp**


<a href="https://github.com/castdrian">castdrian</a>: **creator of Gonerino**


<a href="https://github.com/VasirakCalgux">VasirakCalgux</a>: **creator of VolumeBoostYT**

<a href="https://github.com/mikey820">mikey820</a>: **creator of PleaseDontStopTheMusic**

<a href="https://github.com/bhackel">bhackel</a>: **creator of YouLoop**

<a href="https://github.com/AppropriateNet2928">AppropriateNet2928</a>: **creator of YouFixPlaybackIssues, the other method used by my YTPlaybackFix**





