# 🥁 Drum Kit

An interactive drum kit built with JavaScript, HTML, and CSS. Click the buttons or press corresponding keys on your keyboard to play different drum sounds in real time!

## 🚀 Features

- 🖱️ Clickable buttons for each drum part
- ⌨️ Keyboard support for intuitive play
- 🔊 Realistic drum sounds using `.mp3` audio files
- 🎞️ Visual button animation on interaction

## 🎹 Key Bindings

| Key | Sound        |
|-----|--------------|
| W   | Tom 1        |
| A   | Tom 2        |
| S   | Tom 3        |
| D   | Tom 4        |
| J   | Snare        |
| K   | Crash Cymbal |
| L   | Kick Bass    |


## 🧠 How It Works

1. JavaScript adds click event listeners to all elements with the `.drum` class.
2. A `keydown` listener also maps keys (`w`, `a`, `s`, `d`, `j`, `k`, `l`) to sounds.
3. When a key/button is pressed:
   - A matching `.mp3` file is played.
   - A short animation effect is triggered by adding a CSS class.

## 🛠️ Technologies Used

- HTML
- CSS
- JavaScript (Vanilla)

## 📸 Preview

<img src="https://github.com/user-attachments/assets/f8f307a7-64aa-4ec2-ad3a-e0e76142fd93" alt="Drum Kit app interface with buttons for each drum sound" width="100%" />

## 🌐 Live Demo

👉 [Click here to play the Drum Kit live](https://szgeri25.github.io/drum-kit/)
