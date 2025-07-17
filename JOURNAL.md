# July 2  
I created this! 
----
# July 10 2025

Gotta start the work on the board today, will do this IN SCHOOl with the schematic.

umm okay, we are trying to make a subesat and i am incharge of making the RF board, and i have thought of using the CC1125 by Texas Instruments(my fav semiconductor manufacturer).

it is a great IC tbh and i would adapt the openlst rf design i think, because i like openlst too!

and another goal i have, to make this board as good-looking as possible.


and umm yeah, i thought let's also add the RP2040, arguably the greatest MCU ever made for it's cost. i think i might even just use the RP2350A, but i am more familiar with RP2040 so idk what am i gonna choose, i am going with rp2350A for now.

yeah, i am following the cc1125 design guide right now, and i am gonna probably complete the circuit for the cc1125 today itself.

okay yup, i worked a bit today, i think the schematic for cc1125 is complete, here is the work i did:  
![](/images/10/sch.png)  

worked a bit more, will update the progress at home

### Time Spent Today: 1h 15 mins


# July 15 2025

Okay, i found a PA for the design, but the problem is that it is not available on LCSC, it is the rffm6406, the main PA and LNA for the design, the actual frontend :/ idk what am i gonna do man 

# July 16 2025

I found a balun, [Balf-SPI2-02D3](https://www.st.com/resource/en/datasheet/balf-spi2-02d3.pdf), and along with that i found an IC, the [ST S2-LP](https://www.st.com/resource/en/datasheet/s2-lp.pdf). not sure what i am gonna use, but i am thinking i might just change the cc1125 to the new ST transceiver as it has faster data rate

### Time Spent today: 15 mins