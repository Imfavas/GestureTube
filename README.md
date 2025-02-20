# GestureTube 🎥🖐  
GestureTube is a virtual YouTube video player controller that allows users to control playback using hand and face gestures. Built using *MediaPipe, OpenCV, and PyAutoGUI*, this system captures real-time webcam input to recognize gestures for actions like play, pause, volume control, seeking, and fullscreen toggling.  

By combining *computer vision and gesture recognition, GestureTube enhances user interaction, offering a **touch-free and intuitive* way to navigate YouTube videos.  

## Features  
- *Control YouTube videos using hand and face gestures*  
- *Supports play, pause, volume control, seeking, fullscreen, and more*  
- *Real-time gesture recognition with a webcam*  
- *Hands-free interaction using computer vision*  
## 🎮 Gesture Guide  
### *🖐 Right Hand Gestures*  
| Gesture | Action |
|---------|--------|
| ✊ Rock symbol | Mute |
| 🖐 Open hand | Play/Pause |
| ☝ Index finger | Reduce playback speed |
| 🤟 Pinky | Increase playback speed |
| 🖖 Last three fingers (middle, ring, pinky) | Scroll up |
| ✌ Index + Middle finger | Volume down |
| 🤘 Index + Middle + Ring finger | Volume up |
| 👍 Thumb open | Previous video |

### *🖐 Left Hand Gestures*  
| Gesture | Action |
|---------|--------|
| 🖖 Last three fingers (middle, ring, pinky) | Scroll up |
| 🖐 Open hand | Escape (Exit Fullscreen) |
| 👆 "L" shape (Index + Thumb) | Fullscreen |
| 🤙 Pinky | Minimize |
| 👍 Thumb open | Next video |

### *🤷 Head Gestures*  
| Gesture | Action |
|---------|--------|
| 🤷 Tilt right | Skip 10 seconds |
| 🤷‍♂ Tilt left | Rewind 10 seconds |

## Installation  
### Prerequisites  
Make sure you have Python installed. Then, install the required dependencies:  

```bash
pip install mediapipe opencv-python pyautogui numpy
