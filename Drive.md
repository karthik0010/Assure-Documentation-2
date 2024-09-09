# 💾 Drive in AssureQA

Drive is the file storage system for AssureQA, where users can upload and store files. On this page, users can attach small files and use their path in test steps. Files are listed with details such as the file name (with a copy button), last modified date, and size. Users can download, rename, and delete files by clicking the three dots.

![D-1](/images/D-1.png)

---

## 📂 Managing Files

### **Uploading a File**

To upload a file to Drive, follow these steps:

1. Click on **Upload File**.

   ![D-2](/images/D-2.png)

2. Select the file by clicking the **Upload File** button.

   ![D-3](/images/D-3.png)

   > [!TIP] 
   > You can assign a prefix to the file before uploading, though it’s optional.

3. Click on the **Upload** button.

   ![D-4](/images/D-4.png)

The uploaded file will now appear in the list on the Drive page.

   ![D-5](/images/D-5.png)

Users can **download**, **rename**, or **delete** the uploaded file by clicking on the kebab menu next to the file.

   ![D-6](/images/D-6.png)

---

### **Creating a Folder**

Users can create folders to organize their files on the Drive page.

1. Click on the **Create Folder** button.

   ![D-7](/images/D-7.png)

2. Enter the desired folder name in the dialog box.

   ![D-8](/images/D-8.png)

3. Click on the **Create** button.

   ![D-9](/images/D-9.png)

The created folder will be displayed on the Drive page.

   ![D-10](/images/D-10.png)

> [!TIP]
> You can upload files or create subfolders inside the created folder for better organization.

   ![D-11](/images/D-11.png)

Folders can be renamed or deleted by clicking on the kebab menu next to them.

   ![D-12](/images/D-12.png)

Deleted files and folders will no longer appear on the page.

   ![D-13](/images/D-13.png)

---

## 🔄 Creating a Test Step for Downloading a File

In AssureQA, the 'DownloadFile' keyword automates file downloads. You need to specify the file path where the file will be saved. Here's how you use the Drive to support file downloads:

1. **Create a New Folder**: Go 
