# Project Overview: Transforming an Android Tablet into a Linux Device

I'm setting up this repository purely for fun, driven by a long-standing goal. Ever since my studies and continuing into my professional life, I’ve always dreamed of carrying a fully functional, portable Linux system with me—one I could use throughout my daily routine.
For years, I’ve relied on a personal laptop, often running a dual-boot setup with Windows or juggling multiple virtual machines (up to 10 at a time). This setup has been irreplaceable for many reasons, but there are still scenarios where a full laptop feels like overkill. In these cases, a portable solution like a Linux-powered tablet would be ideal for quick, lightweight tasks.

Here are some examples of tasks where a Linux tablet would come in handy:

*Performing network monitoring sessions (both wireless and wired)
*Running packet sniffing tools like Wireshark (again, wireless and wired)
*Crafting and sending L3 and L2 packets over various network interfaces
*Initiating SSH client sessions to remote servers (I’m aware there are apps for this, but a Linux like environment offers greater flexibility)
*Hosting an SSH server to create a home entry point for SSH tunneling (both remote and local), useful for managing older DVR systems
*Setting up an OpenVPN server for secure remote access to the home network
*Sharing a WiFi connection over Ethernet for network bridging
etc. etc.







Many of the examples mentioned earlier have been personal challenges for me. In the past, I’ve experimented with various Android devices, including old phones that I repurposed as test platforms. Some of these experiments were successful, while others still remain unsolved mysteries that continue to keep me up at night.
This repository is not just a fun project for me; it’s a way to challenge myself while also sharing knowledge with others. The devices we carry every day, whether they’re phones or tablets, aren’t limited to social media, entertainment, or online banking. These are powerful tools capable of much more.
Through this project, I want to demonstrate the potential these devices hold—whether it’s for network security, system administration, or creating a portable development environment.

So let me introduce one of the main protagonist of this story, my last purchase: Lenovo Tab M11 (11" MTK TB330XU): 
https://www.amazon.it/Lenovo-Tab-M11-Processore-Bluetooth/dp/B0CS6TWPGR

Here some basic specification:
* Processor: MediaTek™ Helio G88 (8 Cores, 2x A75 @2.00 GHz + 6x A55 @1.80 GHz) (MT6769H)
* Operating System: Android™ 13 
* Memory: 4 GB LPDDR4X
* Ports/Slots: USB-C 2.0, 3.5mm audio jack, MicroSD slot
* Connectivity: WiFi 2.4Ghz / 5Hz (802.11 a/b/g/n/ac), Bluetooth® 5.1, LTE*
* Display: 11″ WUXGA (1920 x 1200) IPS, anti-fingerprint, touchscreen, 400 nits, 90Hz refresh rate

*A curious aspect of this tablet is that there is no clear indication anywhere that it has an onboard LTE module. You can insert the SIM card in the same slot as the microSD card, which is not immediately obvious until you do not pull off the slot.

As you can see, it’s not an expensive device (it cost around €160), but it still serves well for entertainment, video playback, browsing, and lightweight office tasks. I’m managing the repository directly from the tablet while connected to a Bluetooth keyboard and a wireless USB mouse. Additionally, it comes with a nice and functional stylus for hand drawing. So, good job, Lenovo!
While I aim to "hack" this device, I also want to preserve its original functionalities because, at the end of the day, I plan to use it for relaxing moments as well.

So, let’s begin this journey! Below, you will find the index, which will be updated periodically as I embark on new adventures.

1) Starting from the roots
2) First struggling on environment setup
3) Serf the network (Wireshark)
