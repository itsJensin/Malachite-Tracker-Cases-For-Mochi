<p align="center">
  <a href="https://git.io/typing-svg">
    <img 
      src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=2000&color=67F702&center=true&width=600&lines=%F0%9F%A6%8B+Malachite+Tracker+Cases+For+Mochi+%F0%9F%A6%8B;%F0%9F%A6%8B+DIY+Butterfly+Trackers+for+SlimeVR+%F0%9F%A6%8B" 
      alt="Typing SVG" 
    />
  </a>
</p>

3D-printable files to print butterfly-style casings for the Mochi SlimeVR chip from VyroVR. Includes .STEP files for all five pieces and a quick tutorial on how to assemble the trackers.

### -~ Contents ~-
[1. Material Requirements](#--material-requirements--)  
[2. Tools](#--tools--)  
[3. Printing The Casing](#--printing-the-casing--)  
[4. Assembly](#--assembly--)  

<p align="center">
<img width="720" height="540" alt="Malachite Tracker" src="https://github.com/user-attachments/assets/a4928458-2369-4a29-a849-68f7f55796c5" />
</p>

## -~ Material Requirements ~-
In order to build these casings, you will need...  

- **A strong, durable printer filament for the casing shells**  
<sup>PLA Tough+ or PETG is advisable. I used this [PLA Tough+](https://uk.store.bambulab.com/products/pla-tough-upgrade?id=624454208526409776) for mine. Don't get ones labelled with "-CF"; whilst these may be stronger they are usually less precise when printing.</sup>

- **A flexible printer filament for the central link**  
<sup>TPU or TPE is advisable here due to its elastic properties. I used [TPU-95A](https://www.amazon.co.uk/dp/B00TI3JUSI?th=1) for mine as it is flexible, durable and impact resistant.</sup>

- **Four M2.5 x 8mm Flat Head Screws**  
<sup>The length is imperative to hold everything in place. I used [these ones from Amazon](https://www.amazon.co.uk/gp/product/B0D2R68YBC) and they work great.</sup>

- **A Mochi v4 LSM6DSV DIY Tracker PCB**  
<sup>The default board chip this case should be used with. [Find it here if you haven't already.](https://vyrovr.com/products/mochi-v4-lsm6dsv-slimevr-compatible-tracker)</sup>

- **An LP601730 260mAh LiPo Battery**  
<sup>I have designed this casing to fit [this battery exactly](https://www.amazon.co.uk/dp/B09DPN31KM?th=1) for a snug, structured fit. You can theoretically use any other SlimeVR compatible battery **as long as it is smaller than 17mm width, 32mm length and 6mm height, with a wire length of at least 40mm;** you would just need to secure it into the casing using something like double-sided foam tape.</sup>

- **General purpose lead-free solder wire**  
<sup>The 'normal' type you will find in many electronics and craft stores.</sup>

- **Heavy duty adhesive velcro - the 'hook' side**  
<sup>This is what to stick on the back of the tracker, to attach it firmly to your straps.</sup>

- *Optional* **Soldering Flux**  
<sup>This is quite cheap on [Amazon](https://www.amazon.co.uk/dp/B003JFVCYG) and can help when using an older soldering iron with less unoxidized metal on the tip.</sup>


## -~ Tools ~-
The essential tools required to build these.  

- **Access to an FDM 3D printer with a printing nozzle no smaller than 0.4mm**  
<sup> If you don't own your own printer, there are many online forums with helpful people willing to do small custom printing jobs at a small fee. I had someone from [this subreddit](https://www.reddit.com/r/3Dprintmything/) print some parts for this project. Just be warey of scammers!</sup>

- **A small pair of wire clippers, or if not possible, nail clippers / scissors**  
<sup>For cutting the battery wires to length if necessary.</sup>

- *(Optional)* **A pair of wire strippers**  
<sup>This is optional as I found I could use the clippers to strip the wires.</sup>

- **A soldering iron**  
<sup>For connecting the battery onto the PCB.</sup>

- **A pair of tweezers, or fine tip pliers**
<sup>For holding onto wires during the soldering process.</sup>

- **A small screwdriver, compatible with the screw head type you got in your materials**  
<sup>I used a Phillips #1 for mine.</sup>

## -~ Printing The Casing ~-
<sup>.If you're outsourcing your printing, simply skip to [Assembly](README.md#--assembly--).</sup>
1. Firstly, go to the [releases](https://github.com/itsJensin/Malachite-Tracker-Cases-For-Mochi/releases/latest) tab on this page and download all of the files in the latest release.
2. Load your strong filament into your printer that you will be using for the hard casings.
3. Open your printing software, and drag and drop the four files labelled `Malachite-Shell-... .step` onto the printing plate. You can copy and paste these parts to print however many trackers you will be making.

<p align="center">
<img width="400" height="225" alt="PLA Parts Build Plate sized" src="https://github.com/user-attachments/assets/2cce889e-611b-4316-ba34-38a52765a252" />
</p></br>

4. When you drag the files in, you will need to flip both of the top plates over, so the flate side prints flat on the plate. You should be able to simply do this inside your software.

<p align="center">
<img width="400" height="225" alt="top flipping" src="https://github.com/user-attachments/assets/5b36c400-fc81-42e4-943b-899c06b9b817" />
</p></br>

5. Set each part's infill to 100% in a rectalinear pattern, to ensure a fully solid print.

<p align="center">
<img width="400" height="225" alt="Infill sized" src="https://github.com/user-attachments/assets/53c2e5f2-9ef6-470d-b977-df01bc631f18" />
</p></br>

6. Check it all looks good in your preview and print away! 😊

7. If you are happy with the results of the shell print, load your printer with your flexible filament and repeat steps 3 through 6 with the file labelled `Malachite-FlexiConnector.step`. Just remember to change the filament profile in your printer's / software's settings before running the flexible material.

<p align="center">
<img width="400" height="225" alt="Flexi Insert" src="https://github.com/user-attachments/assets/7940fdfe-0f64-40e4-a9d8-6548c9c7ae05" />
</p></br>

## -~ Assembly ~-

So. For each tracker, you should have five pieces; two bases, two tops and a flexible connector piece.

<p align="center">
<img width="400" height="225" alt="disassembled sized" src="https://github.com/user-attachments/assets/66e68249-7989-44b4-99a8-26c24d147395" />
</p></br>

The first step is to prepare the batteries and the PCBs for soldering.  
1. If your battery cables aren't already stripped, strip about 3mm of the sheath off of the end of the battery's wires.    
<sup>For reference, the protruding pillars on the bottom case pieces are around 3mm, so you can use these as a rough measurement if needed.</sup>

<p align="center">
<img width="400" height="225" alt="stripping sized" src="https://github.com/user-attachments/assets/6cc70bc6-3c68-43b3-9590-27cbe68961c5" />
</p></br>

2. Put some solder onto the end of the soldering iron, then rub the wire tips into the solder to prepare them for joining. If you have access to soldering flux, dipping the tips in this will make it easier for the solder to bind.  
<sup>This part isn't essential, but it will allow the wire to bond with the PCB with much less hassle.</sup>

3. Place your soldering iron onto the power plates on the PCB one at a time, then create a small blob of solder once the plate is hot enough for it to take.  
<sup>You can place a drop of flux onto the pad to help it take the solder.</sup>

<p align="center">
<img width="400" height="225" alt="mochi solder" src="https://github.com/user-attachments/assets/8d7e2e8e-027b-4b9f-9709-9666bde38a9c" />
</p></br>

4. Feed the battery wires through the loop in the center of the flexible connector; pull them as far through as you can to keep the plastic as far away from the soldering processes.

<p align="center">
<img width="400" height="225" alt="threading sized" src="https://github.com/user-attachments/assets/23e9d665-3ef5-4d70-8862-3ef82a16d24b" />
</p></br>

6. Using tweezers or pliers, hold the wires onto the pad and heat with the soldering iron to bond the connection together. Solder the negative (black) wire to the board first, and then the positive (red) wire.  
<sup>Take care to keep the flexible part as far away from the soldering iron as you can; rotating it 90 degrees worked best for me.</sup>

<p align="center">
<img width="400" height="225" alt="soldering sized" src="https://github.com/user-attachments/assets/7585e81f-183f-4c38-987e-baa4ec8e6c7c" />
</p></br>

🟡 *Once the battery has been soldered, the PCB may turn on. Press and hold down the switch on the board for around two seconds, and the board will turn off.*  

6. You can now start assembling the other parts of the tracker. Slot both of the bases up through the holes on the flexible piece, and position the PCB and battery into their respective slots.  
<sup>Take care to insert the casing pieces into the flexible part first before slotting in the electronics, as this will reduce the chance of a snag on the battery wires.</sup>

<p align="center">
<img width="400" height="225" alt="Electronics Insert" src="https://github.com/user-attachments/assets/2cb5b07f-e288-4867-8c99-aaaaf8f732ca" />
</p></br>

7. Feed the battery wires behind the top pillar in the battery casing, so that they follow around the back of the curved pillar.  
<sup>This is important to reduce the chance of catching the wire when mounting the top piece.</sup>

<p align="center">
<img width="400" height="225" alt="Wire Routing sized 2" src="https://github.com/user-attachments/assets/42e28a70-a9fb-43ce-81a2-162e7223af81" />
</p></br>

8. The tops should snap into place relatively easily. Clip the tops of the casings onto the bases, taking care to route the wire through the central notches. The top with the word "Malachite" goes over the battery.
<These will only fit one way around!</sup>

<p align="center">
<img width="400" height="225" alt="topsnap" src="https://github.com/user-attachments/assets/803a3231-58b7-456c-b5c2-49b124037819" />
</p></br>

9. Flip the tracker onto its back. Using a small amount of force, drive the M2.5 screws into the screw holes. You may need to screw and unscrew them a couple of times for the tops to screw on flush with the bases.

<p align="center">
<img width="400" height="225" alt="screwing sized" src="https://github.com/user-attachments/assets/70556691-bc90-454d-9e45-39c140d29bd4" />
</p></br>

11. Make a small rectangular cutout of your velcro piece slightly smaller than the size of the casings, and cut two of the corners off of one of the long sides. Remove the protector tape from the back and stick it firmly onto the back of the tracker.

<p align="center">
<img width="400" height="225" alt="velcro sized" src="https://github.com/user-attachments/assets/a177bb77-db41-447f-b527-b9a738bf96a5" />
</p></br>

### And that's all! You have your tracker!  
Was this overly complicated, unneccesary and time consuming? Yes! That's the fun of it!  
For the next stage of getting your tracker connected, take a look at the SmolSlime documentation on the official SlimeVR website [here.](https://docs.slimevr.dev/smol-slimes/index.html)  

This has been a really fun project to work on. Going back two months ago, I knew nothing about modelling or how to do any of this, so a big thank you to all of the lovely people at VyroVR and SlimeVR for all of the tips and helpfulness that helped me get here 😊

<p align="center">
<img width="900" height="1200" alt="IMG_3464" src="https://github.com/user-attachments/assets/3ff29246-86d4-48ea-bff7-dc734c17fbc2" />
</p>

