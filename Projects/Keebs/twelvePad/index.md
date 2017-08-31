---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
---

I've wanted to build my own mechanical keyboard for a while now, and I think I've finally gathered enough knowledge and resources to try it out.
I'm going to start small with a simple number pad. I value a small form factor and simplicity, so first I need to design a layout that works for me.
The site I used to design the layout is (not suprisingly) [www.keyboard-layout-editor.com](http://www.keyboard-layout-editor.com/ "layout editor website").
This is pretty much the standard for custom keyboards, and other tools will use the output of this program to aid in other aspects of the build, 
so starting here makes sense.

![Image of final layout][layout_pic]

[This is the layout I ended up with][layout], and I have to say I really like it. It's a simple 3x4 grid of 1u size keys, which is just enough to have all of
the numbers on the default layer, and one key left over which will be used to switch to the layer with the math symbols (along with return, delete, and num lock).


![all switches soldered into a matrix][switches_soldered]
![a look at the teensy microcontroller, here connected for testing][teensy]
![teensy attached to a breakout connecter and soldered to the rest of the pad][board_soldered]
![Angled view of finished keypad][angled_finished]
![Side view of finished keypad][side_finished]
![Top view of finished keypad][finished]

[finished]: /assets/images/pad/IMG_20170416_212048.jpg "Finished Keypad"
[switches_soldered]: /assets/images/pad/IMG_20170406_212510.jpg "Switches soldered"
[teensy]: /assets/images/pad/IMG_20170406_212537.jpg "Teensy controller test"
[board_soldered]: /assets/images/pad/IMG_20170415_155215.jpg "Teensy soldered to keypad"
[angled_finished]: /assets/images/pad/IMG_20170416_212151.jpg "Finished Keypad"
[side_finished]: /assets/images/pad/IMG_20170416_212225.jpg "Finished Keypad"
[layout]: http://www.keyboard-layout-editor.com/#/gists/1d57b9caed0c38da67a4c6adc07e87d6 "Link to layout"
[layout_pic]: /assets/images/pad/layout.jpg "Image of layout"
