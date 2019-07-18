 # ATMEGA328 STANDALONE DEVBOARD


### This dev-board is designed to reduce power consumption making it ideal for battery operated projects.

Key Features:
1. On board 5V(HT7850) and 3.3V(HT7833) low dropout voltage regulators which can provide upto 500mA(360mV dropout ,5uA active current)
2. Designed to fit between 2 breadboards which gives you more space for experiments
3. Dedicated pinout for serial programming (compaitable with CH340g USB to TTL programmer and RS232 FTDI programmer)
4. On board SMD switch to select between 5V or 3.3V

Quick Tips:
1. We have tested the board for power consumption under various scenarios and we were able to bring down the current consumption to 30uA in deep sleepmode @ 3.3V/8Mhz(with onboard power led ON)
2. We recommend using blue led as power indicator to minimise power consumption
3. Dev Board is also compaitable with ATmega8,ATmega48,
ATmega168  
4. If you are planning to use only one of 3.3V and 5V, remove the other voltage regulator . This will help to bring down the power conumption even furthur.

Components Required:
1. ATmega328/ATmega168/ATmega48/ATmega8
2. 16Mhz THT crystal oscillator
3. HT7850 x 1, HT7830 x 1
4. SMD tactile switch(5mmx5mm) x 1
5. SMD slide switch x 1
6. SMD 1206 LED - Blue x 1(PWR), Any colour x 1
7. SMD 0805 RESISTOR
	10K(R1) x 1
	100k(R2) x 1 (You can use different value as per your convenience)
	1K(R3) x 2 (You can use different value as per your convenience)
8. SMD 0805 CERAMIC CAPACITOR
	0.1uF(C1) x 6
	22pF(C2) x 2
	10uF(C3) x 4
