This is a project in which i am designing breakout borad of IC ES8388 by Everest electronics. 

Software used : KiCAD

All the project specific libraries are included in psl folder

Main Microcontroller used is ESP32 for i2s and i2c communication purposes.

Hardware to be used by es8388 : 
1. Radio Module RRD102 Ver2
2. 2 x 3W Speakers
3. 2 x Microphones

IC's which are needed for this circuit :
1. ES8388
2. LM1117 3.3V Voltage Regulator
3. RDA5807M (we'll be using directly the smd rrd102 breakout on pcb)

Application :
1. To play bluetooth a2dp via esp32 on speakers.
2. Record sound from MIC and send it to ESP for phone call purposes.
3. Playing Radio on Speakers.

Goals :
1. Fulfilling all the applications.
2. Introduction of AUX_IN for external mic.
