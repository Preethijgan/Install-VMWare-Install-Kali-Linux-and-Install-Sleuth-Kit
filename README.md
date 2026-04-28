# Install-VMWare-Install-Kali-Linux-and-Install-Sleuth-Kit
### Name: Preethi J
### Reg No: 212223220080
## AIM:

To install VMware, set up Kali Linux as a virtual machine, and install Sleuth Kit for digital forensic analysis.

## **Design Steps:**

### **Step 1: Install  VirtualBox**

### **Installation Steps:**
1. Download the **Windows hosts** `.exe` file from the official VirtualBox website.  
2. Run the installer and follow the on-screen instructions.  
3. Once installed, launch VirtualBox to verify the installation.




### **Step 2: Install Kali Linux on VirtualBox**
🔗 **Download Kali Linux VM**: [Click Here](https://www.kali.org/get-kali/#kali-virtual-machines)  

### **Installation Steps:**
1. Download the Kali Linux ISO file.Open VirtualBox, click New, enter "Kali Linux", select Type: Linux and Version: Debian (64-bit).  
2. Set RAM to at least 4GB ,Set disk storage to at least 30GB, choose Dynamically Allocated or Fixed Size, and create the VM. 
3. Go to Settings > Storage, click Empty under Controller: IDE. 
4. Select Graphical Install, follow the prompts to set language, location, username, and password.
5. Choose Partitioning Method (Guided - Use Entire Disk) and wait for installation to complete.


### **Step 3: Install Sleuth Kit (CLI-based Forensic Tools)**
🔗 **Download Sleuth Kit**: [Click Here](https://sleuthkit.org/download.php)  

### **Installation Steps:**
1. Download the **Windows ZIP package** from the official website.  
2. Extract the ZIP folder and move it to a suitable directory (e.g., `C:\sleuthkit`).  
3. Add the **bin folder** to Windows PATH:
   - Open **Control Panel** → **System** → **Advanced System Settings**.  
   - Click **Environment Variables** → Edit **Path**.  
   - Add the Sleuth Kit `bin` folder path and save changes.  
4. Verify installation by running:
   ```sh
   fls -version


## OUTPUT:
**VIRTUAL BOX:**
<img width="1920" height="1080" alt="Screenshot (216)" src="https://github.com/user-attachments/assets/308ceb73-c65e-4391-b9e0-b03f384bebed" />

<img width="1920" height="456" alt="Screenshot (219)" src="https://github.com/user-attachments/assets/a65df7ca-170f-4c1e-97a1-df3cc7a3a488" />

<img width="1920" height="1080" alt="Screenshot (221)" src="https://github.com/user-attachments/assets/21d2be4d-9dab-43bf-8f55-76bf7dd76449" />

<img width="1920" height="1080" alt="Screenshot (222)" src="https://github.com/user-attachments/assets/67c31757-a2fc-4390-88bd-72eca6a2d96c" />

<img width="1920" height="1080" alt="Screenshot (223)" src="https://github.com/user-attachments/assets/bc435a95-1977-4102-944a-9a1c04f52021" />

<img width="1920" height="1080" alt="Screenshot (224)" src="https://github.com/user-attachments/assets/5cd4dc67-42cb-45ee-874c-f9ad4ff50c39" />




**KALI LINUX:**



**SLEUTH-KIT:**



## RESULT:
The setup and installation of VMware, Kali Linux, and Sleuth Kit was completed successfully.
