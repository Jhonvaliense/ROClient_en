# ROClient_en

2025-04-16 kro (EN)
https://drive.google.com/file/d/1hIczvHPMF19PvA2TsHDUR9Ms5eZxBq7u/view?usp=sharing

These client files are provided solely for server testing purposes.

Commercial use is strictly prohibited.

No additional patches will be applied beyond the ones already included.

These files are intended for private server development and testing only.

Please respect the intended use and do not monetize these files.

In 2025, KRO added a feature where quickly pressing Shift + Right-click allows items from the inventory to be moved directly into the Favorites tab.

clif_packetdb.hpp
#if PACKETVER_MAIN_NUM >= 20250305
packet(0x0c22, 12);
#endif

20231220+ CLIENT bodystylefix
https://github.com/AoShinRO/brHades/commit/1396b012600db9b0688f3cd3fdb9ac273d525bd0

*2025-04-02 client update, opening a shop linked to barters.yml causes the client to crash if there are more than two trade items.
It seems that the packet structure has changed!*


