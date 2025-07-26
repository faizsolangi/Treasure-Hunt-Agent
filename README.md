# AI-Powered Streamlit Treasure Hunt Agent

## Overview
This project demonstrates an interactive, AI-driven agent designed to navigate a text-based environment to find a hidden "treasure." It showcases advanced agentic reasoning, dynamic tool utilization, and the ability of Large Language Models (LLMs) to make sequential decisions in a simulated world. The agent leverages a conceptual understanding of Reinforcement Learning principles to guide its exploration.

## Key Features
* **Intelligent Agent Navigation:** The LLM-powered agent makes decisions on movement and actions based on environment descriptions.
* **Custom Tool Integration:** Demonstrates how to create and equip an agent with specialized tools (e.g., for moving, interacting with objects).
* **Memory Management:** The agent maintains context of its environment and past actions.
* **Interactive Streamlit UI:** Provides a user-friendly web interface to observe the agent's progress and the environment state in real-time.
* **LLM as RL Agent Concepts:** Illustrates how LLMs can be designed to learn and act in environments, drawing parallels with Reinforcement Learning.

## Technologies Used
* Python
* LangChain (Agents, Tools, Memory)
* Streamlit
* OpenAI API (for LLM)

## Setup and Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/treasure-hunt-agent.git](https://github.com/your-username/treasure-hunt-agent.git)
    cd treasure-hunt-agent
    ```

2.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: `venv\Scripts\activate`
    ```

3.  **Install dependencies:**
    ```bash
    pip install langchain-openai streamlit
    # Add any other specific libraries you used, e.g., if you used a specific tool library
    ```

4.  **Set up API Keys:**
    Obtain your OpenAI API Key.
    Set it as an environment variable (recommended):
    ```bash
    export OPENAI_API_KEY='your_openai_api_key_here'
    ```
    Alternatively, you can place it directly in your Streamlit app or prompt for it in the sidebar.

5.  **Place your Streamlit application code:**
    Ensure your main Streamlit application code (e.g., `app.py`) is in the root of the repository.

## Usage

1.  **Run the Streamlit application:**
    ```bash
    streamlit run app.py
    ```

2.  **Interact:** Open your browser to the local URL provided by Streamlit (usually `http://localhost:8501`). Follow the instructions in the UI to start the agent and observe its exploration.

## Future Enhancements
* More complex environments with diverse obstacles and interactions.
* Integration with a proper RL framework for explicit policy learning.
* Advanced memory management techniques for long-running explorations.

## License MIT License

## Contact
* LinkedIn: https://www.linkedin.com/in/faiz-ahmad-6aa46b102/
