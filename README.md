# Zhanerke Zeilbekova

**Computer Science and Engineering · Ewha Womans University · Seoul**

I'm working toward machine learning and deep learning research and engineering.
I learn by building working systems first, then studying the mathematics and
architecture underneath them.

**Focus areas:** large language models · AI agents · natural language processing

---

## Featured project

### [university_research-agent](https://github.com/Zhanerkesha/university_research-agent)

A tool-using AI agent with a streaming web interface.

- **Agent core:** an agentic loop on the Claude API in which the model selects
  and calls tools, receives their results, and iterates until it can answer
- **Tools:** six typed Python functions, including exact arithmetic and file
  operations confined to a sandboxed workspace directory
- **Backend:** a Python HTTP server that streams each tool call and reply to the
  client as newline-delimited JSON
- **Frontend:** a responsive chat interface in HTML, CSS and JavaScript with live
  tool-activity indicators and light and dark themes
- **In progress:** retrieval over real university programme data, so
  recommendations are grounded in facts instead of model memory

Built with AI assistance. I'm studying and extending each component myself.

---

## Currently studying

| Area | Topics |
|---|---|
| **Mathematics for ML** | Vectors, dot products, matrix multiplication, partial derivatives, gradient descent |
| **Deep learning** | Neural network training, backpropagation, loss functions |
| **NLP** | Tokenization, embeddings, attention, the transformer architecture |
| **Software engineering** | Python, web fundamentals, Git workflows, API design |

---

## Roadmap

- [x] Design, build and publish a tool-using AI agent
- [ ] Add retrieval-grounded university search to the agent
- [ ] Implement a neural network from scratch with NumPy
- [ ] Reimplement a small transformer and train it on a text dataset
- [ ] Reproduce the results of a published machine learning paper

---

## Tech

- **Languages:** Python · HTML · CSS · JavaScript
- **AI:** Claude API (Anthropic SDK) · tool use · agent design
- **Workflow:** Git · GitHub
