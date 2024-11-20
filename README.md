# Installing Ubuntu as a Dual Boot with Windows

Follow these steps to set up Ubuntu alongside Windows:

## Prerequisites

- A USB drive with at least 8GB of storage.
- Access to the internet to download required files.

---

## Step 1: Prepare the Bootable USB

1. **Download Ubuntu ISO**  
   Download the latest Ubuntu Desktop ISO from [here](https://ubuntu.com/download/desktop).

2. **Download Rufus**  
   Download Rufus, a tool to create bootable USB drives, from [here](https://rufus.ie/en/).

3. **Insert USB Drive**  
   Connect your USB device to your computer.

4. **Create Bootable USB**  
   - Launch Rufus.  
   - Select your USB device under the **Device** dropdown.  
   - Click **SELECT** and choose the downloaded Ubuntu ISO file.  
   - Choose the correct **Partition Scheme** (GPT or MBR) based on your system configuration.  
   - Click **START** to begin the process. This may take some time.  
   - Once completed, your bootable USB is ready.

---

## Step 2: Boot from USB

1. **Restart Your Computer**  
   Ensure the USB is still inserted.

2. **Access BIOS/Boot Menu**  
   Press the appropriate key to enter the BIOS or Boot Menu during startup (usually `F2`, `F12`, or `DEL`).  

3. **Set USB as the First Boot Device**  
   - Locate the boot order settings.  
   - Set the USB drive as the first boot device.  
   - Save changes and exit.

4. The Ubuntu installation will launch automatically.

---

## Step 3: Install Ubuntu

1. Follow the on-screen instructions during the Ubuntu setup process.  
2. When prompted, select **Install Ubuntu alongside Windows** or manually choose the desired partition for installation.  
3. Proceed with the installation.  
4. Once completed, restart your computer. You will now have the option to choose between Ubuntu and Windows during boot.

---

Enjoy using Ubuntu alongside Windows!
