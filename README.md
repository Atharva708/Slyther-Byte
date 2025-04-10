# 🐍 SwiftSnake

A smooth, modern, and theme-rich Snake game built entirely in **SwiftUI** for iOS/macOS – fully offline and perfect for Swift Playgrounds or Xcode.

---

## 🎮 Features

- ✅ **Smooth & flicker-free snake movement**
- 🎨 **10 Unique Themes** – Including *Cyberpunk*, *Matrix*, *Retro*, *Sunset*, *Neon*, and more!
- 🚀 **Dynamic Speed** – The snake starts slow and gradually gets faster with every food eaten
- 🍎 **Food System** – Spawns randomly on the grid, rewarding precision and timing
- 💥 **Wall Collision** – Optional grid walls that end the game if touched
- 📈 **Score Tracking** – Live score + High Score stored using `UserDefaults`
- 🎵 **Sound Effects** – Move, eat, and game over sounds for a complete retro vibe
- 🧱 **Clean Grid Layout** – Built using SwiftUI's native `VStack` and `HStack` system
- 🌙 **Offline & Swift Playgrounds Compatible** – No backend or dependencies

---

## 🧱 How It Works

The game uses a `Timer` to move the snake periodically. With each apple eaten:
- Score increases
- Snake grows in length
- Timer interval and animation duration decrease (speeding up the snake)

No external libraries or backend services required.

---

## 📸 Preview
🎥 Demo



📺 Click the image above to watch a live demo of SwiftSnake in action!
<img src="https://github.com/user-attachments/assets/c3061b07-fc84-4a56-9513-f1f2360a58b0" width="250" />
<img src="https://github.com/user-attachments/assets/a72ff382-1c77-43fd-a1ba-1853f7f6d187" width="250" />
<img src="https://github.com/user-attachments/assets/19d18b83-5cfb-4c14-ba75-792ab62b61ff" width="250" />
<img src="https://github.com/user-attachments/assets/9ed3b1e5-d7f1-4900-ba24-67d2f2575a5d" width="250" />


---



## 🧩 Themes

| Name       | Snake Color | Food Color | Background    |
|------------|-------------|------------|---------------|
| Classic    | Green       | Red        | Black         |
| Neon       | Cyan        | Pink       | Black         |
| Matrix     | Green       | Light Green | Dark Green    |
| Sunset     | Red         | Yellow     | Gradient      |
| Cyberpunk  | Pink        | Yellow     | Deep Purple   |
| Lava       | Orange      | Red        | Dark Red      |
| Ice        | Blue        | White      | Frost Blue    |
| Forest     | Green       | Brown      | Soft Green    |
| Pastel     | Light Purple| Light Orange | White       |
| Retro      | Dark Green  | Brick Red  | Vintage Green |

---



Crafted with ❤️ by Atharva Gour – designer, developer, and Swift enthusiast.

📄 License

MIT License

Copyright (c) 2025 Atharva Gour

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED,
INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE
AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM,
DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
