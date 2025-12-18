# 🤖 LangGraph Learning Journey

Hey there! 👋 Welcome to my LangGraph learning repository. This is where I'm exploring and documenting my journey learning [LangGraph](https://langchain-ai.github.io/langgraph/) - a powerful framework for building stateful, multi-actor applications with LLMs.

## 📚 What's Inside?

This repo contains a series of Jupyter notebooks, each focusing on a specific LangGraph concept. I've built these while following along with tutorials and experiments, progressively building up from simple concepts to more complex patterns.

### Notebooks

1. **[1_simple_graph.ipynb](./1_simple_graph.ipynb)** - Baby steps! 👶  
   My first LangGraph - understanding nodes, edges, and how state flows through a graph.

2. **[2_graph_with_condition.ipynb](./2_graph_with_condition.ipynb)** - Making decisions 🤔  
   Adding conditional edges to create dynamic flows based on state.

3. **[3_chatbot.ipynb](./3_chatbot.ipynb)** - Let's chat! 💬  
   Building a basic conversational agent with message history.

4. **[4_tool_call.ipynb](./4_tool_call.ipynb)** - Tools in action 🛠️  
   Teaching the LLM to use tools - because talking is cool, but doing is better!

5. **[5_tool_call_agent.ipynb](./5_tool_call_agent.ipynb)** - Smarter agents 🧠  
   Creating agents that can decide which tools to use and when.

6. **[6_tool_call_agent_ollama.ipynb](./6_tool_call_agent_ollama.ipynb)** - Local power 💪  
   Running everything locally with Ollama - no API keys needed!

7. **[7_memory.ipynb](./7_memory.ipynb)** - Remember everything 🧠💾  
   Adding persistent memory so your agent doesn't forget your conversation.

8. **[8_langgsmith.ipynb](./8_langgsmith.ipynb)** - Debug like a pro 🔍  
   Using LangSmith for tracing and debugging your LangGraph applications.

9. **[9_human_in_the_loop.ipynb](./9_human_in_the_loop.ipynb)** - Human approval required! ✋  
   Implementing interrupts to pause execution and get human approval before critical actions.

## 🚀 Getting Started

### Prerequisites

- Python 3.10+
- [uv](https://docs.astral.sh/uv/) (recommended) or pip
- An LLM API key (OpenAI, Anthropic, etc.) OR [Ollama](https://ollama.ai/) for local models

### Installation

1. **Clone this repo:**
   ```bash
   git clone https://github.com/vishal83/langgraph-example.git
   cd langgraph-example
   ```

2. **Set up your environment:**
   
   Using `uv` (recommended):
   ```bash
   uv sync
   ```
   
   Or using pip:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up your API keys** (create a `.env` file):
   ```bash
   # For OpenAI
   OPENAI_API_KEY=your_key_here
   
   # For Anthropic
   ANTHROPIC_API_KEY=your_key_here
   
   # For LangSmith (optional, for tracing)
   LANGCHAIN_API_KEY=your_key_here
   LANGCHAIN_TRACING_V2=true
   ```

4. **Fire up Jupyter:**
   ```bash
   jupyter notebook
   ```

## 🎓 Learning Resources

I'm learning from various sources, but here are some that have been particularly helpful:

- 📺 [LangGraph Tutorial on YouTube](https://www.youtube.com/watch?v=CnXdddeZ4tQ)
- 📖 [Official LangGraph Documentation](https://langchain-ai.github.io/langgraph/)
- 🏠 [LangGraph GitHub](https://github.com/langchain-ai/langgraph)

## 🤝 Contributing

Found a bug? Have a suggestion? Feel free to open an issue or submit a pull request. This is a learning project, so I'm open to feedback and improvements!

## 📝 Notes

- Some notebooks require API keys (OpenAI, Anthropic, etc.)
- Notebook 6 uses Ollama for local LLM inference - perfect if you want to run everything offline!
- The code examples are meant to be educational and may not be production-ready

## 📜 License

Apache 2.0 - see [LICENSE](./LICENSE) file for details.

---

Happy coding! 🎉 If you find this helpful, give it a ⭐️

