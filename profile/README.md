# Erasmus-CTM

Open-source [Quarto](https://quarto.org) extensions and materials built for the Erasmus+ project **"Computational Thinking makes sense of Mathematics"** (2023-1-NO01-KA220-HED-000166744). Everything here runs interactive Python/math exercises directly in the browser — no server, no notebook kernel — via [Pyodide](https://pyodide.org) (Python compiled to WebAssembly).

## Extensions

- **[math-exercise](https://github.com/Erasmus-CTM/math-exercise)** — Interactive math exercises with symbolic answer checking (via [SymPy](https://www.sympy.org)), multiple check modes (equivalence, exact form, numeric tolerance, sets), and optional AI-generated hints.
- **[py-exercise](https://github.com/Erasmus-CTM/py-exercise)** — Interactive Python coding exercises with hidden unit tests, forbidden-construct checks, and optional submission export.
- **[pyodide-interaktiv](https://github.com/Erasmus-CTM/pyodide-interaktiv)** — General-purpose interactive Python cells for Quarto, running in a Web Worker so the page stays responsive, with built-in AI feedback and interactive matplotlib plots.
- **[Quarto-Tutorial](https://github.com/Erasmus-CTM/Quarto-Tutorial)** — A tutorial site for learning Quarto itself, at beginner, intermediate, and advanced levels.

## Design goals

- **Client-side only** — no backend, no student data leaves the browser.
- **Multilingual UI** — English and German at minimum, several extensions support more.
- **Optional AI feedback** — works with any OpenAI-compatible API (OpenRouter, Cerebras, Groq, OpenAI, Ollama, …), never required.

## License

Extensions are licensed under [AGPL-3.0](https://www.gnu.org/licenses/agpl-3.0.html) unless noted otherwise in the individual repository. See each repository's `LICENSE` and README for details, including third-party code they build on.
