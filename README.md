# jh.tools
Esoteric VST plugins made in Puredata compiled with Camomile (https://github.com/pierreguillot/Camomile).<br><br>

<br><br>
![Mangle screenshot](https://raw.githubusercontent.com/j-p-higgins/jh.tools/master/mangle_screenshot.png)<br>
**Mangle**<br>
A trio of distortions varying from gentle thickening to full sonic destruction. A multiband overdrive style distortion, a hard clipping distortion with control of the symmetry of the clipping and a '1-bit ADC' for turning all sounds into square waves.
<br><br>
![ResonantDownsample screenshot](https://raw.githubusercontent.com/j-p-higgins/jh.tools/master/resdownsample_screenshot.png)<br>
**ResonantDownsample**<br>
Sample and hold being abused with a feedback loop so that it works like a weird resonant filter. Switchable anti-aliasing type filtering to reduce high frequency artifacts for a more subtle effect. Warning, can self oscillate which can be very loud.
<br><br>
![L80sReverb screenshot](https://raw.githubusercontent.com/j-p-higgins/jh.tools/master/l80s_screenshot.png)<br>
**L80sReverb**<br>
Relatively rubbish reverb that sounds like a cheap, reverb unit from the late 80s. Where this plugin is interesting is that you can modify the block size, overlap and sample rate of the reverb processing which gives effects similar to circuit bent reverb units.
<br><br>
![Gloop screenshot](https://raw.githubusercontent.com/j-p-higgins/jh.tools/master/gloop_screenshot.png)<br>
**Gloop**<br>
Dual mono looper/freeze effect with tremolo. No zero crossing point detection so often clicks and pops. Switch on random for instant Alva Noto. 
<br><br>
![BankPass screenshot 1](https://raw.githubusercontent.com/j-p-higgins/jh.tools/master/bankpass_screenshot_1.png)<br>
![BankPass screenshot 2](https://raw.githubusercontent.com/j-p-higgins/jh.tools/master/bankpass_screenshot_2.png)<br>
**BankPass**<br>
Small bank of four resonant bandpass filters. There is a feedback loop built in which can add extra sustain to the resonance on the filters, or if pushed will go into screaming self oscillation. Plugin can optionally be controlled via MIDI in either four voice polyphonic mode or in unison. When controlled with MIDI frequency sliders work as an offset and can be used similar to an additive synthesiser in mono (unison) mode. Settings for MIDI along with some other features including toggleable pre-programmed scales can be found in the advanced features tab. 