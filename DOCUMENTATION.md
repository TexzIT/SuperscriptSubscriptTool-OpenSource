# 🧾 SuperSubLy Help File

**Workbook App Name**: SuperSubLy  
**Version**: 1.0.0  
**Author**: TexzIT  
**Last Updated**: July 21, 2025  

---

## 📚 Table of Contents

- [📌 What SuperSubLy Does](#-what-supersubly-does)
- [🎯 Who Should Use It](#-who-should-use-it)
- [🖥️ System Requirements](#️-system-requirements)
- [⚙️ Setup](#️-setup)
  - [🔓 Unblock the App](#-unblock-the-app)
  - [🛡️ Enable Content & Macros](#️-enable-content--macros)
  - [✅ Trusted Location (Recommended)](#-trusted-location-recommended)
- [🚀 How to Use It](#-how-to-use-it)
  - [🪟 Userform Method (Full Features)](#-userform-method-full-features)
  - [⌨️ Shortcut Method (Quick Access)](#️-shortcut-method-quick-access)
- [🆘 Need Help?](#-need-help)
- [🧯 Troubleshooting](#-troubleshooting)
- [❓ FAQs](#-faqs)

---

## 📌 What SuperSubLy Does

SuperSubLy is an Excel-based tool that allows you to selectively convert letters (e.g., those used for mean separation in tables) into superscripts or subscripts automatically—without affecting numbers or symbols. It also lets you:

- Customize font size, style, bold, italic, and strikethrough.
- Automatically resize cells to fit updated content.
- Use keyboard shortcuts for fast formatting.

---

## 🎯 Who Should Use It

👨‍🔬 **Academic Researchers, Scientists, and Academics**  
*Use Case: Formatting statistical tables for publication*
Researchers often need to display mean separation using letters as superscripts (e.g., a, b, ab) in tables. SuperSubLy allows them to convert these letters into superscripts without affecting numeric data, making it easier to meet journal and academic formatting standards efficiently.

🧑‍🏫 **Educators & Students**  
*Use Case: Preparing clean assignments, theses, or reports*
Teachers and students working on reports can clean up their tables and data with fast superscript/subscript formatting, making the content look more professional before submission or printing.

🧑‍💻 **Data Analysts & Excel Power Users**  
*Use Case: Enhancing readability in dense Excel reports*
Analysts presenting tabular summaries or data can apply script formatting to annotations or footnotes for a cleaner, more scannable layout—without needing to manually format each cell.

🧾 **Government & NGO Researchers**  
*Use Case: Cleaning long, copy-pasted Word tables*
SuperSubLy can save hours when preparing documentation for grants, reports, or inter-agency publications.

🛠️ **Publishers**  
*Use Case: One-click formatting for print-ready publications*
Editors and layout professionals preparing books, journals, or manuals can apply superscript or subscript formatting in seconds. SuperSubLy ensures consistent styling without manual tweaking.

---

## 🖥️ System Requirements

- 🪟 **Windows Only**
- 📊 Microsoft Excel 2007 or newer
- 🧩 Macros must be enabled

---

## ⚙️ Setup

⚠️ Please extract the ZIP file before opening `SuperSubLy_v1.0.0_SSL.xlsx`  

🔐 Please open the app file `SuperSubLy_v1.0.0_SSL.xlsx` only on the computer you intend to use it. This app is licensed for a single user.

⚠️ Open the file named `SuperSubLy_v1.0.0_SSL.xlsx` first before attempting to rename it, if you wish to.

### 🔓 Unblock the App
Before you open it (make sure the app is closed if it’s already open):

Navigate to the app file (SuperSubLy_v1.0.0_SSL) location—that is, where it’s stored on your computer.
1. Right-click the `.xlsm` file.
2. Select **Properties**.
3. In the **General** tab, look for a message:
   > "This file came from another computer..."
4. Check **Unblock**, then click **Apply** and **OK**.

### 🛡️ Enable Content & Macros

- If you open the workbook app file (SuperSubLy_v1.0.0_SSL) and see a yellow security warning stating that macros have been disabled, simply click **Enable Content** in the warning bar.
- If a Microsoft Excel Security Notice window appears when you open the file, click **Enable Macros**.

### ✅ Avoid These Warnings and Issues by Using a Trusted Location (Recommended)

To avoid the above issues each time you open the file, you can add a Trusted Location:

How to Set Up a Trusted Location
1. Open Excel → `File > Options > Trust Center > Trust Center Settings...`
2. Click **Trusted Locations** → **Add new location...**
3. Browse to the folder containing SuperSubLy
4. Check “Subfolders of this location are also trusted” (optional)
5. Click **OK**
6. 
After completing this setup, you can move the app file ('SuperSubLy_v1.0.0_SSL') into the folder you just designated as a Trusted Location.


## 🚀 How to Use It

1. Open the app file (`SuperSubLy_v1.0.0_SSL.xlsx`)

There are **two ways** to use the app:

### 🪟 Userform Method (Full Features)
This method provides access to all formatting options.

How to Use:
- Click the **SuperSubLy** tab on the Excel ribbon
- Click **Script Operations** iocn in the **Main** group
    A form (the SuperSubLy window) appears on the right side of your screen.
    An input box appears on the left, which automatically fills once you select      a range of cell(s) on the worksheet. 
- Select your cell range → Click **OK** in the input box
- In the Script Operations section of the SuperSubLy window, apply a script operation:
* Click **Apply Superscript** or **Apply Subscript**.
* To reverse, click **Undo Superscript** or **Undo Subscript**.
Here’s a polished, grammatically correct, and clearer version of your text:

---

### Font Formatting

To adjust the appearance of your scripts, go to the **Font Settings** section.

You can change the font name and size, make text bold, italicize it, or apply strikethrough formatting to your scripts.

---

### How to Use the Font Settings Section

1. Select a range of cells.
2. In the **Font Settings** section, choose your preferred font options.
3. Then, return to the **Script Operations** section and click the operation you want to apply.

*Note:* Your font customizations will only take effect once you click an option in the **Script Operations** section.

---

### Additional Details

* The default font is **Arial** with a size of **12**. These defaults can change based on the first letter’s font name and size in your selected range.
* Some common and useful fonts are preloaded in the rectangular font selection box to get you started. However, the box will reflect the font name of the first letter encountered in your selection.
* The font size ranges from a minimum of **8** to a maximum of **36**, chosen for practical reasons. These limits cannot be exceeded by the first letter’s font size in your selection.

---

### Resizing Cells to Fit Text

To help your text fit well, check the **Resize to fit** option before applying the script operation. While not perfect, this works well in certain cases, such as when cells are excessively large.

*Note:* Resizing is based on the cell with the highest number of characters in your selection, so it may not always be perfectly efficient.

---

### ⌨️ Shortcut Method (Quick Access)

This method allows you to work even without the SuperSubLy window being visible. Use it when working across multiple workbooks. Just make sure the SuperSubLy workbook stays open in the background for everything shortcut to function properly.

| Action              | Shortcut             |
|---------------------|----------------------|
| Apply Superscript   | `Ctrl + Shift + K`   |
| Undo Superscript    | `Ctrl + Shift + J`   |
| Apply Subscript     | `Ctrl + Shift + B`   |
| Undo Subscript      | `Ctrl + Shift + V`   |

To use these shortcuts, simply select a range of cells and press any of the shortcuts listed above.

You can also combine this shortcut method with the SuperSubLy window method. For example, select a range of cells using the SuperSubLy window and apply a script operation. Then, select a different range of cells and use a shortcut to apply another operation.

If the SuperSubLy window is still open while you're using the shortcut method, it will apply the font settings currently active in the window. To avoid this carry-over effect, just close the SuperSubLy window before using shortcuts.

Note: The shortcut method does not allow font customization like the SuperSubLy window. It simply applies script operations to letters as they are. For example, if a letter is in Arial font in one cell and another is in Calibri in a different cell, both will retain their original fonts.

---

## 🆘 Need Help?

Click the **"Need Help?"** button in the SuperSubLy window to access the built-in help center.

### Help Window Features

- 📄 **Offline Help**: Click the **Open local help file** button to access the offline PDF help document. This is a great starting point for finding relevant information quickly.  
- 🌐 **Online Help**: For more detailed instructions and tips, click the **Get more help online** button. This will open the current help page in your browser. An active internet connection is required.
- 📬 **Contact Support**: You can reach out to us via the email provided in the Contact Support section of the Help window. Simply click the email service you want to use (Gmail, Yahoo, Outlook/Hotmail/Live, Zoho, or your desktop email client) — provided you're logged in — and then click the **Compose email** button. With an internet connection, this will open a pre-filled email in your selected service. Just type your message and send.
Please do not change the version info in the subject line — it helps us identify your installation for better support. But you can add to it.
- 📋 **Copy Email Address**: For manual emailing. If the automatic method doesn’t work, click the **Copy email address** button. This copies the displayed email address to your clipboard so you can manually paste it into your preferred email service.  
- 🧾 **Copy Log File Location**: For diagnostics and troubleshooting, you may be asked to send a log file. Click the **Copy log file location** button to copy the folder path. Then paste it in your File Explorer to open the folder. Attach the log file found there to your email.  
- 🐞 **Report a Bug**: Click this button to open a web page where you can report any issues that need our attention. An internet connection is required.  
- 🌍 **Visit Here**: Click this to explore more about SuperSubLy and other products from us. This also requires an internet connection.  
- ❌ **Remove App**: If you choose to uninstall the app (though we hope you don’t!), click this red **Remove app** button. After confirming your decision, the app will delete its related files and folders. You will then be guided to where you can delete the app itself.

---

## 🧯 Troubleshooting

1. **File Blocked?**  
   Right-click the downloaded file → click Properties → check **Unblock** → Apply → OK.

2. **Security Warning (Yellow Bar)?**  
   Click **Enable Content** If you open the workbook app and see a yellow Security Warning bar telling you that macros have been disabled, just click **Enable Content** in that same bar.

3. **Enable Macros Prompt?**  
   When opening the app, you may see a Microsoft Excel Security Notice window. If it appears, click **Enable Macros** to allow the app to function correctly. 

4. **Access Denied?**  
   Make sure you have write permissions to folders. The app may create background error logs.

5. **Shortcuts Not Working?**  
   Close and reopen SuperSubLy workbook app. 

---

## ❓ FAQs

**Can I move the workbook app file to my preferred location?**  
✅ Yes, you can place this workbook app anywhere on your computer. It doesn't depend on a specific folder to function properly. 

**Will this app be updated?**  
🆕 Yes, some selected updates will be provided free of charge to licensed users who supply their email address. 

**Can I use this on multiple devices?**  
🚫 No, each copy comes with a single-user license. If you need to use it on another device, a separate license (another copy) will be required.

**Is this your only product?**  
📦 No, we’re currently developing more useful tools. You’ll be notified via email when new products are ready, so you can be among the first to explore them (watch your inbox!)

**Can this tool format normal letters too?**  
Yes, you’ll notice that the app can apply font formatting to letters, whether they are superscripts or subscripts. While this wasn’t a primary feature, it’s a helpful added benefit.

---
