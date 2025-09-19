# I-Am-Poor
# I Am Poor

**I Am Poor** is a simple static iOS app that displays a piece of text and an image.  
It was inspired by the infamous *I Am Rich* app that once sold on the App Store for **$999** and only displayed a diamond and the text “I Am Rich.”  

My version flips the idea into a fun parody called **I Am Poor**, where the app shows a label and a coal image instead.

This project isn’t about complexity — it’s about learning the **full flow of app development and version control**:
- Building a basic iOS app in Xcode  
- Designing and setting up custom app icons  
- Using Git and GitHub to track and share my work  

---

## Description

The app consists of:
- A label displaying **“I Am Poor”**  
- An image view that shows a **coal PNG**  
- Custom icons generated in all required sizes for iPhone  

This is my very first iOS/Xcode project and also my first attempt at properly using Git and GitHub for version control.

---

## ️ How I Built It

### 1) Xcode Setup
- Created a new project in **Xcode**.  
- Opened the main file and added a **UILabel**, edited its text to **“I Am Poor”**.  
- Found a coal PNG image online and added it to the **Assets (Images.xcassets)** folder.  
- Added a **UIImageView** to the storyboard and set its image to the coal asset.  

### 2) App Icon
- Designed an app icon (1024×1024).  
- Used an online **App Icon Generator** to produce all required iPhone icon sizes.  
- Replaced the default Xcode icon set with the generated icons.  

### 3) Git & GitHub Workflow

Initialized a repo and made the first commit:
```bash
git init
git add .
git commit -m "Initial commit"
Configured Git with my GitHub identity (one time):

bash
Copy code
git config --global user.name "..."
git config --global user.email "@gmail.com"
Connected the remote and pushed:

bash
Copy code
git remote add origin https://github.com/hemanthgolusu/I-Am-Poor.git
git branch -M main
git push -u origin main
