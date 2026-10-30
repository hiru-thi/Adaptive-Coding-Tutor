# Coutor – Adaptive Coding Tutor

An AI-powered adaptive coding tutor that personalizes programming education based on each learner's skill level, knowledge, and learning progress.

## Overview

Coutor is an intelligent coding tutor designed to make programming education more personalized and effective. It uses AI and adaptive learning techniques to generate coding exercises, evaluate answers, provide instant feedback, and dynamically adjust question difficulty based on learner performance.

## Key Features

- **Personalized Learning:** Adapts programming content to individual skill levels.
- **AI-Powered Assistance:** Provides contextual coding explanations and guidance.
- **Adaptive Question Generation:** Generates relevant coding exercises based on learning progress.
- **Instant Feedback:** Evaluates answers and provides corrections and explanations.
- **Performance Tracking:** Identifies strengths and areas for improvement.
- **Dynamic Difficulty Adjustment:** Adjusts question complexity according to learner performance.

## Technology Stack

| Category | Technologies |
|---|---|
| Backend | Python, FastAPI, Uvicorn |
| AI & LLM | OpenAI API |
| NLP & Embeddings | Sentence Transformers |
| Semantic Search | FAISS |
| Machine Learning | PyTorch, Transformers |
| Model Integration | Hugging Face |
| Testing | Pytest |

## Installation and Setup

### 1. Clone the Repository

```bash
git clone <YOUR_REPOSITORY_URL>
cd Coutor
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

Activate the environment:

**Windows**
```bash
venv\Scripts\activate
```

**Linux / macOS**
```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables

Create a `.env` file in the project root:

```env
OPENAI_API_KEY=your_api_key_here
```

### 5. Run the Application

```bash
uvicorn main:app --reload
```

Replace `main` with your actual Python module name if different.

## Project Objective

To create an intelligent and adaptive programming learning environment that improves coding skills through personalized exercises, AI-driven feedback, and continuous performance evaluation.

## Future Enhancements

- Support for additional programming languages.
- Advanced learner performance analytics.
- Personalized learning paths.
- More interactive coding challenges.
- Improved adaptive recommendation mechanisms.

## Developed By

**Coutor – Adaptive Coding Tutor**

An AI-driven approach to making programming education smarter, more accessible, and personalized.

---

If you find this project useful, consider giving the repository a star.
