# SPWS
Solar Powered Weather Station

The SPWS project was finally completed after about three years of work. The beginning of doing this project was many years ago when there was PM2.5 dust around our places. Whenever I go for exercising outdoors, I must first check what the weather and dust are like. At that time, they still used the SmartMi meter to measure it, so the idea was to make my own meter. Initially it was a standalone device, but it evolved over time to eventually integrate with Home Assistant so it can be viewed from any mobile device anywhere. As well as I want the it to be installed outside the house, which is sometimes inconvenient to find a power supply so eventually it has been developed to use solar energy. In the daytime, it uses solar energy while charging lithium batteries as well. And in the night, it uses battery power repeatly over the day.

The real fun and challenge of this project lies in the energy management, on how manage solar energy and batteries to be able to use without having to look after it. The rough idea is to want the battery to be able to last in the case if there is no sunlight for 3-4 days, which is the reason for choosing ESP32 because it can be coded to go into deep sleep mode while not in use.

The first prototype is now being installed at my place in Samut Prakan. Do a field test for a year and then see what will be developed next. Perhaps add a set of speed and wind direction measurements in the future.
