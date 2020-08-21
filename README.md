# pulseeffect-config

Pulseeffects settings specially targeted for **Asus N551**

There are two settings for pulseeffects
1. **advanced_auto_gain**\
  This is specially optimized for laptop speakers and tries to balance bass and treble.
  
 2. **subwoofer**\
  This is specific to **Asus N551** and tries to produce deep bass.
  
  I have also bundled helper scripts to automate the process.\
  The `nowoofer` script enables the **advanced_auto_gain** and also puts the audio card to **Analog Stereo** (applicable to **Asus N551**).
  You can look your audio codec supported profiles.
  
  The `woofer` script applies the **subwoofer** configuration in pulseeffects and also pusts the audio codec to 2.1 surround (applicable to **Asus N551**)
  
  ## Installation
  Just clone the repository and then copy the `.json` files into the PulseEffects directory you can find in the local config directory. The location of that directory
  depends on how you installed PulseEffects. If you installed it through Flatpak, you can find it in `~/.var/app/com.github.wwmm.pulseeffects/config/PulseEffects`, for
  other systems it should be `~/.config/PulseEffects`.
