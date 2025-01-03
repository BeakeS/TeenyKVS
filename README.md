# TeenyKVS

Key Value Store (KVS) Tool for Arduino and Arduino-Like Applications

KVS is a convenient format to store collections of data as Key-Value pairs in a linked list.  I created this tool for an Arduino project that needed to store and analyze data and, after attaching an I2C FRAM to the processor, I couldn't find any convenient/generic way to manage FRAM data storage and retrieval.  KVS seemed like an obvious choice but the only KVS application I could find was Embedis which was a hybrid host/arduino app that made a good starting point for building a simple, teeny Arduino KVS tool.

KVS is great for storing data on an attached FRAM or sdcards.

Also great format for radio packets!!!  I used to design custom radio packets with unique headers and content BUT now I only have two packet types - A KVS request packet with keys and no values and a response or send packet with KVS keys and values.

I'll add more documentation soon but you can find an example used to store program application defaults on an sdcard here - https://github.com/BeakeS/TeenyGPSTestbed_M5.git.

