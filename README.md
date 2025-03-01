# 🖤 **Tyson's OSINT Tools** 🖤

In this repository, you'll find powerful and versatile **OSINT (Open Source Intelligence)** tools designed to extract valuable information from publicly available sources. These tools allow you to uncover secrets, track digital footprints, and reveal hidden details. Dive into the shadows of the web, where nothing is safe from discovery.

**The truth is out there. Will you find it?**

---

### **📡 Available OSINT Tools**:

1. **TheHarvester**  
   A tool used for gathering e-mail addresses, subdomains, and other details from public sources.  
   - **Available Commands**:
     ```bash
     theHarvester -d <domain> -b google   # Search for information using Google
     theHarvester -d <domain> -b bing     # Search for information using Bing
     ```

2. **Sherlock**  
   A tool for finding usernames across various social media platforms.  
   - **Available Command**:
     ```bash
     python3 sherlock <username>   # Search for the given username across multiple platforms
     ```

---

### **⚠️ How to Use the Tools**:

1. **Install Dependencies**:  
   Before using any OSINT tool, make sure you have the necessary dependencies installed like `python3`, `pip`, etc.
   
2. **Set up the tools**:  
   Download and set up the required tools, then run the respective commands for gathering information.

3. **Adding Your Signature**:  
   In each tool, you can add your personal touch by adding `"Tyson - [Tool Name]"` when running the tool, like:
   
   ```bash
   echo "Tyson - [Tool Name]" && [Tool Command]
