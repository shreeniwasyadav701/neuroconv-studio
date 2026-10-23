# NeuroConv Studio

An interactive, client-side Convolutional Neural Network (CNN) research and visualization web application.

## Key Features

1. **Interactive Canvas & Inference**:
   - Real-time handwritten digit / sketch recognition.
   - Touch & mouse drawing support with custom brush thickness and eraser.
   - Real-time softmax probability distribution and Shannon entropy metric.
   - Quick-load digit archetypes (0-9).

2. **2D Convolution Math Sandbox**:
   - Step-by-step sliding window arithmetic visualizer.
   - Element-wise dot product breakdown: $\sum [Input(i+u, j+v) \times Kernel(u, v)] + Bias$.
   - Interactive $3 \times 3$ kernel matrix editor with presets: Sobel X/Y, Ridge/Laplacian, Sharpen, Gaussian Blur, Identity.
   - Auto-slide play/pause animation and manual step controls.

3. **Feature Maps & Activation Inspector**:
   - Multi-layer activation views: Conv1 ($26 \times 26 \times 8$), MaxPool1 ($13 \times 13 \times 8$), Conv2 ($11 \times 11 \times 16$).
   - Multiple scientific color palettes: Turbo, Viridis, Magma, Grayscale, Cyber Neon.
   - Grad-CAM (Gradient-weighted Class Activation Mapping) saliency heatmaps showing explanatory attribution overlays.

4. **Dynamic CNN Architecture Builder & Code Exporter**:
   - Add/Remove/Customize layers (Conv2D, MaxPool2D, Dense).
   - Real-time layer shape propagation, output dimensions, and total parameter calculation.
   - Export production-ready model code in **PyTorch** (`nn.Module`) and **TensorFlow / Keras** (`Sequential`).

## Getting Started

Open [`index.html`](file:///data/user/0/com.agy/files/.gemini/antigravity-app/scratch/cnn-studio/index.html) in any modern browser. Zero build steps or external dependencies required.
