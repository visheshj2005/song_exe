# 🎵 Song Runner CLI Tool for Linux

Easily play or download your favorite YouTube songs right from your terminal using a single command!

---

## 📥 Step 1: Download the Tool

Use the following command to download the latest release as a `.zip` file:

```bash
curl -L -o song.zip https://github.com/visheshj2005/song_exe/releases/download/Song_Runner_CLI_Tool/song.zip
```

---

## 📦 Step 2: Unzip the Package

Unzip the downloaded file:

```bash
unzip song.zip
cd song_runner_linux
```

You will see the following files:

- `song` → the CLI executable
- `ffmpeg` → bundled ffmpeg binary
- `ffprobe` → bundled ffprobe binary

Make them executable:

```bash
chmod +x song ffmpeg ffprobe
```

---

## ⚙️ Step 3: Set Up Environment Variable (Optional but Recommended)

To run `song <song_name>` from **any directory**, add this folder to your PATH:

```bash
echo 'export PATH="$PATH:$(pwd)"' >> ~/.bashrc
source ~/.bashrc
```

Alternatively, move the binaries to a global path:

```bash
sudo mv song /usr/local/bin/
sudo mv ffmpeg /usr/local/bin/
sudo mv ffprobe /usr/local/bin/
```

---

## ▶️ Step 4: Run the Command

Now you're ready to use the CLI!

```bash
song panchayat title track
```

The tool will:
- Search YouTube for the best match
- Download the audio
- Convert it to MP3 using the included `ffmpeg`

---

## 📌 Notes

- No need to install Python or yt-dlp.
- All dependencies are bundled inside the zip file.
- Requires an active internet connection.


## 📬 Credits

Created with ❤️ by [Vishesh Jain](https://github.com/visheshj2005)  
Powered by [yt-dlp](https://github.com/yt-dlp/yt-dlp) and FFmpeg

---
