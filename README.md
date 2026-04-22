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
<sup>I have designed this casing to fit [this battery exactly](https://www.amazon.co.uk/dp/B09DPN31KM?th=1) for a snug, structured fit. You can theoretically use any other SlimeVR compatible battery **as long as it is smaller than 17mm width, 32mm length and 6mm height;** you would just need to secure it into the casing using something like double-sided foam tape.</sup>

- **General purpose lead-free solder wire**  
<sup>The 'normal' type you will find in many electronics and craft stores.</sup>


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

- **A small screwdriver, compatible with the screw head type you got in your materials**  
<sup>I used a Phillips #1 for mine.</sup>

## -~ Printing The Casing ~-
<sup>(If you're outsourcing your printing, simply skip to [Assembly](--assembly--))</sup>
1. Firstly, go to the releases tab on this page and download all of the files in the latest release.

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

7. If you are happy with the results of the shell print, load your printer with your flexible filament and repeat steps 3 through 6 with the file labelled `Malachite-FlexiConnector.step`. 

<p align="center">
<img width="400" height="225" alt="Flexi Insert" src="https://github.com/user-attachments/assets/7940fdfe-0f64-40e4-a9d8-6548c9c7ae05" />
</p></br>

## -~ Assembly ~-
