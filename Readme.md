# 🎵 Song Runner CLI Tool for Windows

Easily play or download your favorite YouTube songs right from your terminal using a single command!

---

## 📥 Step 1: Download the Tool

Click the link below to download the latest `.zip` file:

```
https://github.com/visheshj2005/song_exe/releases/download/Song_Runner_CLI_Tool/song.zip
```

Or run this in PowerShell or CMD:

```CMD
curl -L -o song.zip https://github.com/visheshj2005/song_exe/releases/download/Song_Runner_CLI_Tool/song.zip
```

## ⚙️ Step 2: Add to System PATH (Optional but Recommended)

To use `song <song_name>` from any directory:

1. Open **System Properties** → **Environment Variables**
2. Under **System variables**, find and select `Path`, then click **Edit**
3. Click **New** and add the full path to the `song` folder
4. Click OK to save and apply

---

## ▶️ Step 3: Run the Command

Now you're ready to use the CLI! Open **CMD** or **PowerShell** and type:

```bash
song panchayat title track
```

The tool will:
- Search YouTube for the best match
- Download the audio
- Convert it to MP3 using the included `ffmpeg`

---

## 📌 Notes

- No need to install Python or yt-dlp separately.
- All dependencies are included in the zip file.
- Requires an active internet connection.

---

## 📬 Credits

Created with ❤️ by [Vishesh Jain](https://github.com/visheshj2005)  
Powered by [yt-dlp](https://github.com/yt-dlp/yt-dlp) and FFmpeg
