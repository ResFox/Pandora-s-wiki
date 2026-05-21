# 📟 Makcu 1 PC Guide

{% hint style="danger" %}

#### Pandora's Box does not recommend using Makcu on a single PC. All our software uses its own drivers with a high level of security. We advise against using Makcu unless you plan to use two PCs setup.

{% endhint %}

#### Welcome to the MAKCM setup

<figure><img src="https://2000999588-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2Fxr02iQbBt5IsdQ3g6zQo%2Fuploads%2FmylpQSH5JuOeRXCLKcpX%2Fimage.png?alt=media&amp;token=3a2a9673-fc98-4ca1-bc99-2cb649e12c23" alt=""><figcaption></figcaption></figure>

## <mark style="color:$success;">OFFICAL MAKCU GUIDE:</mark>

<mark style="color:$success;">PLEASE FOLLOW OFFICIAL GUIDE SINSE CURRENT VERSION OF SHODAN USE LAST FIRMWARE</mark>&#x20;

{% embed url="https://www.makcu.com/en/setup" fullWidth="true" %}

{% embed url="https://youtu.be/QoyAVuE8MY8" %}

**Steps to Flash Your Unit:**

**Download the AIO Tool:** Get the tool from here or Download.

{% embed url="https://cdn.discordapp.com/attachments/1379256725982548082/1380919881448558613/MAKCM_v2_files-main.zip?ex=68d7f7db&is=68d6a65b&hm=dc637e8432987884f7cb9fbac978fb13693c1ef2b3391acdfeee732f90e1c703&" %}

Download and install CH343 Driver

{% embed url="https://cdn.discordapp.com/attachments/1323462758028541992/1347212100543713300/CH343_Driver.zip?ex=68d7f28a&is=68d6a10a&hm=de2553a4525e7f3cbc0c922fc8d0753b3e6fdf42f27e64e3f0b291bc2e0a11bf&" %}

**Open the AIO Too**l: Let it update automatically.

**Requirement USB cable:** You’ll need one USB cable to flash the PCB. This master cable will be connected to the second PC.

{% hint style="danger" %}
**WHEN FLASHING REMOVE ALL CABLES**
{% endhint %}

<figure><img src="https://2000999588-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2Fxr02iQbBt5IsdQ3g6zQo%2Fuploads%2FYKeHmEhTpoKrmeaubQQ%2Fimage.png?alt=media&amp;token=aa0966d0-1208-46b2-9abe-836d7778c185" alt=""><figcaption></figcaption></figure>

hold the LEFT button and plug the blue cable into the LEFT USB port.

1. **After MAKCM is in flash mode, you should see "MCU connected in flash mode"**

<figure><img src="https://2000999588-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2Fxr02iQbBt5IsdQ3g6zQo%2Fuploads%2FYFSpHzrT6fUxBP1llkkN%2Fimage.png?alt=media&amp;token=d0dd5196-f0f4-4633-94c2-924821ddc91c" alt=""><figcaption></figcaption></figure>

*This confirms that your makcu is in flash mode*

Click **Flash Left** on your AIO, wait for it to finish

<figure><img src="https://2000999588-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2Fxr02iQbBt5IsdQ3g6zQo%2Fuploads%2FHfW7aQXzbPgcgFXsS7Te%2Fimage.png?alt=media&amp;token=529231ff-5f62-47f9-b6da-76833fe1d42f" alt=""><figcaption></figcaption></figure>

Unplug **USB cable** from left port when your finished

<figure><img src="https://2000999588-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2Fxr02iQbBt5IsdQ3g6zQo%2Fuploads%2F9Sd1ql8m4YayHhs4qe4e%2Fimage.png?alt=media&amp;token=1bde3b3f-1fb1-4bb2-8ad2-e57d13a920b4" alt=""><figcaption></figcaption></figure>

*Plug the same the same cable into the RIGHT USB port, while holding the RIGHT button*

Click F**lash Right** on your AIO, wait for flash to finish.

<figure><img src="https://2000999588-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2Fxr02iQbBt5IsdQ3g6zQo%2Fuploads%2FaGm0AhcAxrAd2YKvtgyi%2Fimage.png?alt=media&amp;token=e80a43c3-f7a6-4e41-ac5e-c5ffc171c8cd" alt=""><figcaption></figcaption></figure>

### Install CH343 Driver

Download

{% embed url="https://cdn.discordapp.com/attachments/1323462758028541992/1347212100543713300/CH343_Driver.zip?ex=68d7f28a&is=68d6a10a&hm=de2553a4525e7f3cbc0c922fc8d0753b3e6fdf42f27e64e3f0b291bc2e0a11bf&" %}

Extract to a folder

Right click install

<figure><img src="https://2000999588-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2Fxr02iQbBt5IsdQ3g6zQo%2Fuploads%2FhEZ1deYQbxnt1aNHfSLc%2Fimage.png?alt=media&amp;token=817e73cd-61f3-4551-9962-5a6d1ad8a0f1" alt=""><figcaption></figcaption></figure>

### Com Port

On your PC, go to Device Manager and open COM

<figure><img src="https://2000999588-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2Fxr02iQbBt5IsdQ3g6zQo%2Fuploads%2F7Kyw6sVYoOVH7O5u0Opf%2Fimage.png?alt=media&amp;token=5ec78172-b990-46e1-890c-c0687b8a27ac" alt=""><figcaption></figcaption></figure>

Make sure the COM port number for Makcu is below **3** (shown as CH343).

Right click and click properties.

<figure><img src="https://2000999588-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2Fxr02iQbBt5IsdQ3g6zQo%2Fuploads%2FXXzSgJiyzyKwRGKrXrdd%2Fimage.png?alt=media&amp;token=f27f6be8-c126-46da-82c0-b0943c5a3ad5" alt=""><figcaption></figcaption></figure>

Click on advance

<figure><img src="https://2000999588-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2Fxr02iQbBt5IsdQ3g6zQo%2Fuploads%2FtZwvNsGv4OHuisUX2W7m%2Fimage.png?alt=media&amp;token=e219bbde-367f-4e67-8c88-bc71cce389d8" alt=""><figcaption></figcaption></figure>

Pick a lower com port than 10, then press Ok to save. If you have the Makcu AIO tool open, close it and restart Makcu by unplugging and replugging the left most cable. After completing all the steps, the flash process should be complete.

### Setting up Makcu

<figure><img src="https://2000999588-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2Fxr02iQbBt5IsdQ3g6zQo%2Fuploads%2FJp8eXRtTuIED3SG8fdmo%2Fimage.png?alt=media&amp;token=f0c0868b-d6fc-4200-bea6-3a1ade7790c2" alt=""><figcaption></figcaption></figure>

If you are in same pc both USB comes to same pc Plug the **FARTHEST LEFT** cable into your **main PC**, **MIDDLE** cable into your **secondary PC**, **FARTHEST RIGHT** cable should be **your mouse**. After flash, restart the **AIO** and click **"TEST"**. If your cursor teleports on your main screen, everything is working properly.
