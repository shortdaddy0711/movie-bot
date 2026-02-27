# 🎬 Movie Expert Agent

An intelligent, AI-driven personal movie assistant that provides details, cast information, and recommendations using the [Nomad Movies API](https://nomad-movies.nomadcoders.workers.dev) and OpenAI's `gpt-4o-mini` model.

## ✨ Features

- **Popular Movies**: Instantly get a list of trending and popular movies.
- **Movie Details**: Retrieve deep-dive information including genres, runtimes, budgets, and revenues.
- **Cast & Crew**: Find out who starred in your favorite films with image previews.
- **Similar Recommendations**: Discover new movies with AI-powered similarity matching.
- **Interactive Chat**: Talk to the movie expert directly in a dedicated Jupyter Notebook interface.

## 🚀 Getting Started

### Prerequisites

- Python 3.13+
- [uv](https://github.com/astral-sh/uv) (recommended for dependency management)
- OpenAI API Key

### Installation

1.  **Clone the repository**:

    ```bash
    git clone https://github.com/shortdaddy0711/movie-bot.git
    cd movie-bot
    ```

2.  **Set up environment variables**:
    Create a `.env` file in the root directory:

    ```bash
    touch .env
    ```

    Add your OpenAI API key to `.env`:

    ```env
    OPENAI_API_KEY="your-key-here"
    ```

3.  **Install dependencies**:
    ```bash
    uv sync
    ```

### 🖥️ Usage

1.  Open `main.ipynb` in VS Code or JupyterLab.
2.  Run the setup cells to initialize the OpenAI client and API wrapper.
3.  Use the **Interactive Chat** cell at the bottom to start asking questions!

#### Example Queries:

- _"What are some popular movies right now?"_
- _"Tell me about movie ID 550"_
- _"Who stars in Fight Club?"_

## 🛠️ Built With

- **LLM**: OpenAI `gpt-4o-mini`
- **API**: [Nomad Movies API](https://nomad-movies.nomadcoders.workers.dev)
- **Tools**: `httpx`, `openai`, `python-dotenv`, `ipykernel`

## 📝 License

This project was created as part of the AI Agents Masterclass. Credits to [Nomad Coders](https://nomadcoders.co/) for providing the Movie API.
