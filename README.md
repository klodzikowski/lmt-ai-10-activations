# Activation Functions Explorer

One neuron, four activation functions. Pick Perceptron, Sigmoid, Tanh, or ReLU, drag the input, and watch the output move along the curve. An activation function decides how a neuron responds to its weighted input—this is where non-linearity enters a neural network.

## Try it

- Live demo: https://klodzikowski.github.io/lmt-activation-functions-explorer/ (goes live once GitHub Pages is enabled)
- Or just open `index.html` in a browser—one file, no installation, no build step, no API key.

## What to notice

- The perceptron jumps from 0 to 1 with no slope in between—that hard step is why it cannot be trained with gradient descent.
- Sigmoid and tanh flatten out for large inputs. That is saturation: the gradient shrinks towards zero and learning stalls.
- ReLU keeps climbing for positive inputs and silences everything below zero—cheap, simple, and the default in modern networks.
- The challenge cards mirror the in-class quizzes: sigmoid(−2) ≈ 0.12 and tanh(−2) ≈ −0.95.

## Course context

Part of the *2 MA LMT :: Artificial Intelligence* course at the Faculty of English, AMU Poznań. Used in the neural-networks sequence alongside the activation-functions Colab and dashee87's visualisations. Rebuilt in 2026 from a vibe-coded Gemini demo used in the 2025/26 run.

## Licence

MIT—see [LICENSE](LICENSE).
