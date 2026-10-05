# Neural Networks: Zero to Hero (code-along)

My code-along and notes for Andrej Karpathy's
[Neural Networks: Zero to Hero](https://karpathy.ai/zero-to-hero.html) series.
I'm doing this purely to learn the material. The code follows the lectures, and
all credit goes to Andrej Karpathy and the course.

## Lectures

| # | Lecture | Folder | Status |
|---|---------|--------|--------|
| 1 | Building micrograd | [micrograd](micrograd) | ✅ |
| 2 | makemore: bigram | makemore-bigram | ⬜ |
| 3 | makemore: MLP | makemore-mlp | ⬜ |
| 4 | makemore: activations, gradients, BatchNorm | makemore-batchnorm | ⬜ |
| 5 | makemore: Backprop Ninja | makemore-backprop-ninja | ⬜ |
| 6 | makemore: WaveNet | makemore-wavenet | ⬜ |
| 7 | Let's build GPT | gpt | ⬜ |
| 8 | Let's build the GPT tokenizer | tokenizer | ⬜ |
| 9 | Let's reproduce GPT-2 (124M) | gpt2-reproduction | ⬜ |

## Setup

    python3 -m venv venv
    source venv/bin/activate
    pip install -r requirements.txt

The graph drawings in micrograd also need the Graphviz program
(`brew install graphviz` on macOS).

## Credits

All lecture material and original code by Andrej Karpathy
([micrograd](https://github.com/karpathy/micrograd),
[makemore](https://github.com/karpathy/makemore),
[nanoGPT](https://github.com/karpathy/nanoGPT),
[minbpe](https://github.com/karpathy/minbpe),
[build-nanogpt](https://github.com/karpathy/build-nanogpt)), used under the MIT License.
