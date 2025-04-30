# 🖐️ Hand Drawing Canvas

A gesture-controlled virtual drawing board using **OpenCV**, **MediaPipe** in Python. This application lets you draw on a canvas using hand gestures tracked through your webcam.

---

## 📌 Features

- ✍️ **Gesture-based Drawing** using index finger.
- 🧽 **Gesture-based Erasing** using index + middle finger.
- 🎨 **Multiple Brush Styles**: Normal, Spray, and Rainbow.
- 🔲 **Shape Drawing Mode**: Circle, Rectangle, and Triangle.
- 🖼️ **Sketch Filter** to stylize the canvas.
- 💾 **Save Canvas** as PNG with timestamp.
- ↩️ **Undo Last Action** with canvas history.
- 🧹 **Clear Canvas** or Clear Annotations easily.

---

## 🎮 Controls

### ✋ Gesture Controls
| Gesture                        | Action         |
|-------------------------------|----------------|
| Index finger up               | Draw           |
| Index + Middle fingers up     | Erase          |

### ⌨️ Keyboard Controls
| Key         | Action                        |
|-------------|-------------------------------|
| `1`         | Normal Brush                  |
| `2`         | Spray Brush                   |
| `3`         | Rainbow Brush                 |
| `4`         | Toggle Shape Mode             |
| `s`         | Save Canvas                   |
| `z`         | Undo Last Action              |
| `f`         | Apply Sketch Filter           |
| `x`         | Clear Canvas                  |
| `t`         | Start Voice Annotation        |
| `d`         | Delete Annotation Text        |
| `q`         | Quit the Application          |

### 🎨 Color Selection
| Key | Color   |
|-----|---------|
| `b` | Black   |
| `r` | Red     |
| `g` | Green   |
| `l` | Blue    |
| `y` | Yellow  |

### 🔧 Brush Size
| Key | Action             |
|-----|--------------------|
| `+` | Increase Thickness |
| `-` | Decrease Thickness |

---

## 🧰 Dependencies

Install the required libraries using pip:

```bash
pip install opencv-python mediapipe numpy SpeechRecognition pyaudio
