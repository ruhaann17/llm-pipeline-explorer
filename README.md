# LLM Pipeline Explorer 🚀

An interactive visual deep-dive showing how Large Language Models (LLMs) turn everyday sentences into tokens, vector coordinates, multi-head attention maps, 3D semantic space, and generated text.

Built with **pure HTML, CSS, and Vanilla JavaScript** in a single standalone file. Zero frameworks, zero npm, zero build tools, zero API keys required.

---

## 🌟 Features Across the 5 Pipeline Stages

1. **Stage 1: Tokenization & Subwords (BPE)**
   - Custom vocabulary builder from training corpus
   - Subword splitting with `##` prefix
   - Dynamic vocabulary capacity slider demonstrating out-of-vocabulary subword fragmentation
   - Character count, token count, and compression ratio metrics
   - Interactive token chips with Token IDs

2. **Stage 2: Dense Vector Embeddings & Positional Encoding**
   - High-dimensional vector lookup heatmap
   - Sinusoidal Positional Encoding toggle ($PE_{(pos, 2i)} = \sin(pos / 10000^{2i/d})$)
   - Dynamic color gradient visualizing vector coordinate magnitudes

3. **Stage 3: Multi-Head Self-Attention Core**
   - Curved SVG connection arcs illustrating Query-Key token affinities
   - Interactive hover beam highlighting
   - Full Query × Key attention heatmap matrix with softmax weights
   - Pre-configured attention riddles (e.g. pronoun resolution: *"The animal didn't cross the street because it was tired"*)

4. **Stage 4: 3D Semantic Vector Space (PCA)**
   - 64-dimensional semantic embedding engine with topic clustering (Space, Coffee, Nature, Tech)
   - Dimensionality reduction via Principal Component Analysis (PCA)
   - Interactive 3D WebGL scatter plot using Plotly (rotate, pan, zoom)
   - Cosine similarity ranking table with animated match bars
   - Custom sentence injection: plots custom sentences as glowing diamond markers with 3 nearest neighbors

5. **Stage 5: Next-Token Probabilities & Autoregressive Loop**
   - Softmax next-token distribution with live probability bar charts
   - Interactive **Temperature** slider (0.1 deterministic to 1.5 creative)
   - **Top-K** candidate pool filter
   - Single-step token generator & 5-step automated generation streamer

---

## 🚀 Live Demo / GitHub Pages

To view locally:
Simply open `index.html` in any web browser!

---

## 🛠️ Tech Stack
- Vanilla HTML5 / CSS3 / JavaScript
- [Plotly.js](https://plot.ly/javascript/) (via CDN) for 3D vector space visualization
- Single-file architecture
