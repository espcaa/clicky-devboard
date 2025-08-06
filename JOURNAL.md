---
Title: "Clicky devboard"
Author: "@spc"
Description: "a rp2350 based devboard with mechanical switches :D"
Created On: "2/08/2025"
---

# August 1st-2nd, 2025 (we like working at midnight pf)

I got most of the schematic done! I just need to figure out what type of io i'll use (uh probably just pin headers?) and i'll be done!!!! \
Now comes the routing.... aaaaa

<img width="600" height="1329" alt="image" src="https://github.com/user-attachments/assets/6169d300-bb19-4eb7-b256-2ec7db2adbb6" />


**Total time spent: 2h30**

# August 2nd, 2025 (Part II)

I attributed all of the footprints to the symbols after some research and converted my board to a pcb!
I spent a good hour trying to debugging why i couldn't see the GND net when trying to make a plane (even cyao told me it was over :sob:) but i finally found it was because of another net connected to the GND that renamed it!

<img width="560" height="81" alt="Screenshot 2025-08-02 at 14 27 38" src="https://github.com/user-attachments/assets/cfaab81c-a86a-483c-bf12-704a3387dca1" />

I also changed the symbol from the easyeda one to the official one for more legibility + added headers to expose the gpios! \

<img width="600" height="1156" alt="Screenshot 2025-08-02 at 14 26 27" src="https://github.com/user-attachments/assets/ebbe954e-467f-4b85-86c6-160d2438b5c9" />

**Time spent: 3h, Total time spent: 5h30**

# August 2nd, 2025 (Part III) & August 3rd, 2025

I grinded with tongyu and kailing on my board during the night and after a lot, a lot and a lot of errors, crashouts i managed to fully route my board!
It looks very cool and comes at under 100$/5 units!!!
I learned so much about kicad, and that's very cool!

<img width="719" height="465" alt="image" src="https://github.com/user-attachments/assets/38a57371-701e-4bd8-8cf2-8567adf9b96f" />


**Time spent: 9h, Total time spent: 14h30**

# August 5-6th

After realizing my pcb was quite bad (bad crystal routing and uh a lot of other things that rudy pointed at) + the fact that it wasn't "clicky", i decided to re route it!
I spent a lot of time on it but it's cleaner, HAS 0 DRC ISSUES!!!! (i'm so proud of that one :sob:) + it looks waay cooler!!!
I also updated to a 4 layer board with this stackup:
- 1st layer : 3v3
- 2nd layer : GND
- 3nd layer : gpio, slow signals
- 4nd layer : vbus + random things

<img width="600" height="821" alt="image" src="https://github.com/user-attachments/assets/89526ad8-f0a8-495c-919b-152e3edc97cd" />

<img height="300" alt="Screenshot 2025-08-06 at 01 27 20" src="https://github.com/user-attachments/assets/82231134-2c69-4897-afa0-327363debd31" /><img height="300" alt="Screenshot 2025-08-06 at 01 27 38" src="https://github.com/user-attachments/assets/074f94ec-5958-4b79-aebd-710e42d1428a" />

**Time spent : 5 hours, Total time spent: 19h30**
