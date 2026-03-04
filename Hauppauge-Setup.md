---
uid: Hauppauge-Setup
title: Hauppauge Setup
---

Emby has native support for current [Hauppauge](https://hauppauge.com/) PCIe and USB Tuners on Windows.

You will need first to install the Hauppauge WinTV app and go through the configuration process and ensuring latest drivers and channel data is in place. WinTV needs to be installed and activated. The earliest supported version is v8.5. The following is the link for the [WinTV v10 app](https://www.hauppauge.com/pages/support/support_wintv10.html).

After installing the Hauppauge WinTV app, ensure all the channel tuning data is updated, click on **Settings** and then **Check for Tuning Updates** in the **General** tab.

![](images/tvtuners/hauppauge-1.png)

After ensuring that the tuning data is up to date, make sure the Hauppauge Pause Buffer path is setup and permissions are set for the Emby Server windows process for full access. Select the **Recordings** tab and set the folder paths. The Disk Buffering Pause-Mode Recording Directory is used by Emby Server for Live TV streaming and recordings.

![](images/tvtuners/hauppauge-2.png)

Next is to configure the tuner and scan for the TV channels. The example in the following screenshots is for DVB-T OTA channels for the UK.

![](images/tvtuners/hauppauge-3.png)

Select the tuner and click on **Tuner Setup**.

Go through the options applicable to your region, type of tuner and channels available for you.

![](images/tvtuners/hauppauge-4.png)

![](images/tvtuners/hauppauge-5.png)

On completion of the scan and setup, use the WinTV app to test that the channels do stream and the signal and quality is good. 

Close the WinTV application and prepare to add the Hauppauge tuner to the Emby Server.

The LiveTV and DVR feature requires a valid [Emby Premiere](Emby-Premiere.md) subscription. This would be indicated on the setup screen when there is no subscription:

![](images/server/livetv6.png)

To add an Hauppauge device, click on **Add TV Source** and select **Hauppauge**

![](images/server/hauppauge-server1.png)

This will show the following

![](images/server/hauppauge-server2.png)

Click on **Detect Devices**

You will then see all the detected DVR devices that have not been added to Emby Server already, select the Hauppauge device you wish to add

![](images/server/hauppauge-server3.png)

You will be back to this screeen. Click on **Add TV Source**

![](images/server/hauppauge-server4.png)

You will now see the device added.

![](images/server/hauppauge-server5.png)

You are ready now to add guide data and where needed, map tuner channels to guide data and optionally configure the advanced DVR settings. See [Live-TV](Live-TV.md)
