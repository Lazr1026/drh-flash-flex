# DRH Flash Flex
I suck at naming things, the flex relocates the flash for the DRH to the top of the board.

Why? The flash sticks up alot, so much so that securing the 5GHz module becomes a challenge as it is (usually) relocated to sit in that area.

![](https://github.com/Lazr1026/drh-flash-flex//blob/main/img/drhflashflex.png?raw=true)

The flex should be compatible with all board revisions, but the via for 3v3 was designed with the WUP-50 in mind. In theory it should reach the small 3v3 plane for the DRH on the previous boards, but just in case it doesnt I added a pad and a line to follow to snip off that area.

Shorts between 3v3 and GND should not be a worry, as there is no copper on the other side of the flex in that area.

### Credits
[YveltalGriffin](https://github.com/mackieks): Suggestion of rotating the IC to be vertical, which then really cleaned up the routing.
[BitBuilt](https://bitbuilt.net/): Being pretty fucking cool.
