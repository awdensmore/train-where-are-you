# train-where-are-you
People of Cape Town - let's build a HW/SW platform to inform passengers when their train is arriving.

**Components**
1. Android app: in background, determine when user approaches a station (GPS / cell tower). Log data when user leaves station along track. This is a "train". Determine speed and estimate arrival at other stations. Interface: where are you going? Next train arrives at \[closest station to user\] in \[x\] minutes.
2. Data learning: with large data set, identify trends in terms of average speeds, delays, comparison of lines, etc.
3. API: let's make the data publicly available.
4. Hardware: will phone sensors be enough? Maybe before critical mass have HW devices along track every x km. Collect data via two microphones pointing in opposite directions to determine presence of train and direction of travel. Arduino + LM386 + solar + bat + LORA. Guerilla install on utility poles.
