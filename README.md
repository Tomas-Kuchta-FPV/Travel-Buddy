# Travel-Buddy
Pocketable, smart and sleek Meshtastic node. With keyboard, Eink screen, GPS and all day baterry life thanks to it's Solar panel. Based on the [Seed Studio Wio tracker L1](https://meshtastic.org/docs/hardware/devices/seeed-studio/wio-series/tracker-l1/).  

Took inspiration from the original idea of Meshtastic and made a hiker, prepper and EDC friendly device.  

## Specifications
- **Wio tracker L1 Eink** a nifty main board
    - **GPS** to know where you and your frinds are
    - **nRF52840** to sip power bit by bit
    - **2.3 Inch Eink screen** so you never miss anything 
    - **Navigation buttons** for easy and intuitive navigation
    - **On-Off button** to save power for when the Sun is hiding
    - **Antenna** the default antenna is pretty good
- [3x4 Nokia style](https://en.wikipedia.org/wiki/T9_%28predictive_text%29) keyboard for easy texting
- **Solar panel** so your battery can be rechargerd from 0 to 100 in just two daays
- Space for a **big battery** for the days when the sun isn't shining

![front](/Screens/Front.png)
![back](/Screens/Back.png)

## Use cases
Built for hikers, makers, preppers, and everyday carry adventurers who like their tech smart, tough, and a little bit magical.

**Hikers** can wander freely without worrying about battery life, coverage, or fragile screens. Solar charging keeps it alive on long trails, GPS keeps you oriented, and Meshtastic keeps you connected with your group even when civilization politely vanishes. The only real responsibility is remembering to bring it along. 😅

**Makers** will feel right at home. It’s open-source, hackable, and begging to be customized. New firmware ideas, experimental features, clever power optimizations. This thing is a playground for curious minds who like to bend hardware to their will.

**Preppers** get a resilient, low-power communication tool that keeps working when the grid doesn’t. Solar charging, long battery life, offline mesh networking, and the ability to tinker and repair make it a quiet little survival ally that doesn’t ask for much.

**EDC** enthusiasts get a pocketable device that just works. No constant charging anxiety, no fragile glass screens, no babysitting. Toss it in your bag or clip it to your gear and let it quietly do its job, day after day, powered by sunlight and good engineering dreams.


![Top](/Screens/Top.png)
![Front_trans](/Screens/Front_transparent_4-3.png)  
![PCB_screen](/Screens/PCB_V2.png)

## My motivation to build it
It is some sort of challange to see wether I can do a project thar can be comercialized, almost evhery project can end up making some money but many times it depends wether its worth it.  
I have way more faith when I built the physical prototype as it seems like a super cool and handy idea.  
And also it's a whole lot of fun to do a project that doesn't need to worry about money or the general public. ;)


## Higway BOM

| Item                | Qty | Price (USD) | Link                                                         |
| ------------------- | --- | ----------- | ------------------------------------------------------------ |
| Wio tracker L1 Eink | 1   | 52          | https://www.seeedstudio.com/Wio-Tracker-L1-E-ink-p-6456.html |
| PCB                 | 1   | 5.5         | jlcpcb.com                                                   |
| I have the pasives  | -   | *freeeeee/2 |                                                              |
| TCA8418RTWR         | 1   | 4.13        | https://www.aliexpress.com/item/33026225094.html             |
| ME6211C33M5G        | 1   | 1.08        | https://www.aliexpress.com/item/1005010191995723.html        |
| TS-1187A-B-A-B      | 12  | 2.7         | https://www.aliexpress.com/item/1005009929216261.html        |
| S4B-PH-K-S(LF)(SN)  | 1   | 1.12        | https://www.aliexpress.com/item/1005005565308002.html        |
| Ali shipping        | -   | 3.14        |                                                              |
| Total               |     | 69.67       |                                                              |

When ordering from LCSC is $74.89, wchich is so expensive because of the shipping and handling fees. Its in the [ods BOM](/BOM.ods).  
When ordeing from aliexpress its $69.67 which is great, but the Eink Wio tracker is out of stock in europe. So I'll go with the Oled one, So the total cost should be around $55 for this higway project.