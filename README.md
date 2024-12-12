# 📂 **Creating a One-Time Backup in Server 2012**

This guide walks you through the steps to create a one-time backup on Windows Server 2012 using built-in tools. By following this process, you can ensure that your critical data is protected in case of system failure.

---

## ⚙️ **Step 1: Open Windows Server Backup**

1. **Access Server Manager**:  
   - Click the **Start** button and open **Server Manager**.
   
2. **Navigate to Windows Server Backup**:  
   - In the **Server Manager**, click on **Tools** in the top-right corner and select **Windows Server Backup** from the dropdown menu.

---

## 📝 **Step 2: Select Backup Option**

1. **Open Backup Wizard**:  
   - In the **Windows Server Backup** window, click on **Backup Once...** from the right-hand panel.

2. **Choose Backup Type**:  
   - A new window will appear, prompting you to choose the type of backup. Select **Custom** and click **Next** to proceed.

---

## 💾 **Step 3: Choose Backup Destination**

1. **Select Backup Destination**:  
   - You will now be asked where to store the backup. Choose between:
     - **Local drives**: If you want to save the backup on a local hard drive.
     - **Remote shared folder**: To store the backup on a network share.

2. **Click Next**:  
   - After selecting your preferred destination, click **Next** to proceed.

---

## 🛠️ **Step 4: Select Items to Backup**

1. **Choose What to Backup**:  
   - The next screen will ask what you want to back up. You can select from:
     - **System State**: Includes OS and critical system files.
     - **Full Server**: Backs up all data on the server.
     - **Specific Folders**: Choose particular folders or files to back up.

2. **Click Next**:  
   - Once you've selected the data to back up, click **Next**.

---

## ⏳ **Step 5: Confirm Backup Settings**

1. **Review Settings**:  
   - Review the backup configuration settings to ensure everything is correct.
   - If everything is as expected, click **Backup** to begin the process.

2. **Monitor the Backup Progress**:  
   - The backup process will begin. You can monitor the progress in the **Windows Server Backup** window. Depending on the size of the data, this may take some time.

---

## ✅ **Step 6: Backup Completion**

1. **Backup Success**:  
   - Once the backup is completed, you will see a confirmation message stating that the backup was successful.

2. **Close the Backup Window**:  
   - Click **Close** to exit the backup wizard.

---

## 🚨 **Step 7: Verify the Backup**

1. **Verify the Backup**:  
   - To ensure the backup is successful, navigate to the backup location and verify that the backup files are present.

---

# 🔚 **End of Guide**

---

### 📑 **Additional Tips**

- **Regular Backups**: While this guide walks you through a one-time backup, it’s recommended to set up regular backups to ensure your data is consistently protected.
- **Test the Backup**: Regularly test your backup to ensure that it can be restored successfully in case of disaster recovery.

---

### 🚪 **Ending Bar**

---
