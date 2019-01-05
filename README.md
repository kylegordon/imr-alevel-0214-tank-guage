# Some information pertaining to the decoding of the AUIT Alevel 0214 'Smart LPG Tank Level Sensor'

This appears to be a magnetically operated LPG tank sensor that periodically transmits the level reading on 433.920MHz. As far as I've been able to determine, it uses Amplitude Shift Keying (ASK) and Non Return to Zero encoding. 

Unfortunately, as can be seen in the 0pct directory, the reported number changes with every transmission. The manufacturer has emailed me to say that they will not release protocol information. The serial number from this sample unit I have is 51355990 and is likely embedded in the signal, as the reciever for the data, the OKO 5100 reciever, is designed to handle multiple tank sensors.
