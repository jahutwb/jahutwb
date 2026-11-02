# Hi, I'm Jan

I build software that connects language, machine learning, and interactive products. My work spans Python backends, NLP pipelines, React/TypeScript interfaces, and earlier computer-vision research with PyTorch.

## Selected work

### Przesłowo — reading across languages

[Try Przesłowo](https://przeslowo.pl)

A Polish–Czech reading experience that gradually introduces original-language text into a translation. The project connects text alignment, structured editorial data, and an interactive reader with token-level explanations, notes, and saved reading progress.

The current product's source is private. A [historical React/TypeScript reader](https://github.com/jahutwb/szwejk-reader) is public, with its own fixtures and automated tests. It documents an earlier stage of the project.

### TachyonAI — experimental interactive application

A Python/FastAPI application exploring visual choices, image embeddings, similarity search, and an evolutionary image-selection workflow. The engineering includes API endpoints, persistence, session/round state, and automated tests. The current codebase is private; this project is experimental, with no claim of validated market-prediction performance.

### Computer vision — biological dosimetry

[View the research snapshot](https://github.com/jahutwb/DL_dosimetry)

Earlier work on chromosome detection and segmentation for biological dosimetry, adapting Facebook Research's `maskrcnn-benchmark` to a chromosome dataset. My project-specific work includes dataset integration, COCO-style segmentation handling, and training configuration. The repository preserves the 2019 research snapshot and credits the upstream framework.

## Code to review

Start with [szwejk-reader](https://github.com/jahutwb/szwejk-reader): a runnable historical React/TypeScript application with Vitest tests. The candidate-selection logic in [selection.ts](https://github.com/jahutwb/szwejk-reader/blob/master/src/domain/selection.ts) is a compact entry point; [selection.test.ts](https://github.com/jahutwb/szwejk-reader/blob/master/src/domain/selection.test.ts) shows the behavior it protects.

I use AI coding tools as part of development, alongside explicit data contracts, tests, and review of the resulting behavior.
