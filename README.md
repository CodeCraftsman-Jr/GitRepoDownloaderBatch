# GitHub Bulk Repository Downloader

**GitHub Bulk Repository Downloader** is a command-line tool designed to simplify the process of downloading repositories containing a large number of folders and files. If you've ever encountered problems while cloning large repositories due to their size or structure, this tool is made for you.

## 🔧 Features

- ✅ **Download each folder individually** from a GitHub repository  
- 🚀 **Multi-threaded processing** for faster downloads  
- 🔄 **Resume support** – continues downloading from where it left off  
- 🔍 **Checks for already downloaded folders/files**  
- 🧠 **Skips already downloaded data** to save time and bandwidth  
- 📁 Maintains the **original structure** of the repository

## 📌 Use Case

This tool was initially developed to overcome the difficulties faced when cloning repositories with a massive number of folders. GitHub’s default cloning method may fail or take excessive time in such cases. With this tool, you can selectively or entirely download a repository in a more efficient and controlled manner.

## 🖥️ How It Works

1. Run the tool via the command line
2. Provide the GitHub repository link
3. The tool parses the repository structure
4. Each folder is downloaded individually using multi-threading
5. Downloads can be resumed if interrupted

## 💡 Example Command

```bash
python bulk_downloader.py --repo https://github.com/user/large-repo
