

A simple and interactive **Drum Kit** built using **HTML, CSS, and JavaScript**.
Press the keys **A, S, D, F, G, H, J, K, L** on your keyboard to play different drum sounds.
This project demonstrates DOM manipulation, event handling, and audio playback in JavaScript.

Features

* Play drums using keyboard keys
* Real-time audio playback using `<audio>` elements
* Smooth visual key-press animations
* Lightweight and beginner-friendly
* No external libraries required
  

 Controls (Key Mappings)

| Key | Sound    |
| --- | -------- |
| A   | Clap     |
| S   | Hi-hat   |
| D   | Kick     |
| F   | Open Hat |
| G   | Boom     |
| H   | Ride     |
| J   | Snare    |
| K   | Tom      |
| L   | Tink     |

---

Project Structure

```
/project-folder
│── index.html
│── style.css
│── /sounds
│     ├── clap.wav
│     ├── hihat.wav
│     ├── kick.wav
│     ├── openhat.wav
│     ├── boom.wav
│     ├── ride.wav
│     ├── snare.wav
│     ├── tom.wav
│     └── tink.wav
```

---

How It Works

 **JavaScript logic**

* A `keydown` event listener detects which key is pressed.
* The corresponding `<audio>` tag is found using `data-key`.
* Audio playback is reset using `audio.currentTime = 0`.
* The `.playing` CSS class adds a visual animation.
* A `transitionend` event removes the animation effect.

---

How to Run the Project

1. Download or clone the repository:

   ```bash
   git clone https://github.com/yourusername/drum-kit.git
   ```
2. Open **index.html** in any browser (Chrome recommended).
3. Press the keys **A–L** to start playing.

---



 License

This project is open-source and available under the **MIT License**.

---

 Acknowledgements

Inspired by the **JavaScript30** challenge by *Wes Bos*.


