Connections:
WM8960 (Waveshare module)  <-> Omega2+  

SDA<->SDA#5
SCL<->SCL#4
CLK<->I2S CLK #3
WS<->I2S WS #2
RXSDA<->I2S SDO

WM8960 (MCLK) is clocked from 24MHz generator


To get sound you must unmute:
Right Output Mixer PCM 
Left Output Mixer PCM 

And for headphone:
Headphone Playback ZC  
and ofcourse set:
Headphone [dB gain: -15.00, -15.00]  


Files path for files (after first build)
target\linux\ramips\dts
build_dir\target-mipsel_24kc_musl\linux-ramips_mt76x8\linux-4.14.81\sound\soc\codecs
build_dir\target-mipsel_24kc_musl\linux-ramips_mt76x8\linux-4.14.81\sound\soc\generic


Based on:
https://github.com/OnionIoT/source
https://github.com/waveshare/WM8960-Audio-HAT


