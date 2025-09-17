# 🎓 EduTutor AI - Personalized Learning Assistant

An intelligent educational assistant powered by **IBM's Granite 3.2-2B Instruct model**, designed to help students learn more effectively through AI-driven explanations, quizzes, study planning, and problem-solving.

---

## ✨ Features

- 📚 **Concept Explanation**  
  Get detailed explanations of any topic with real-world examples.

- ❓ **Quiz Generator**  
  Generate comprehensive quizzes with multiple question types:  
  - Multiple Choice (MCQ)  
  - True/False  
  - Short Answer

- 📅 **Study Planner**  
  Create personalized study schedules with daily goals and key topics.

- 🧮 **Problem Solver**  
  Step-by-step solutions for math problems and other academic challenges.

---

## 🚀 Quick Start

### ✅ Running in Google Colab (Recommended)

1. Open [Google Colab](https://colab.research.google.com/)
2. Create a new notebook.
3. Copy and paste the entire code from this repository.
4. Run all cells.
5. Click the generated **Gradio** link to access the web interface.

### 🖥️ Local Installation


# Install dependencies
pip install transformers torch gradio

# Run the script
python edututor_ai.py


## 🔧 Configuration

The application uses the following default settings:

* **Model:** IBM Granite 3.2-2B Instruct
* **Max Tokens:** 1024
* **Temperature:** 0.7 (balanced creativity/accuracy)
* **GPU Support:** Automatic detection and optimization

---

## 📋 System Requirements

### Minimum Requirements

* Python 3.7+
* 4GB RAM
* 8GB free disk space

### Recommended for Optimal Performance

* Google Colab Pro (GPU access)
* 16GB+ RAM for local deployment
* CUDA-compatible GPU (optional but recommended)

---

## 🎯 Usage Examples

### 📚 Concept Explanation

**Input:**

```
"Machine Learning"
```

**Output:**
Detailed explanation with real-world applications, common algorithms, and illustrative examples.

---

### ❓ Quiz Generation

**Input:**

```
"Photosynthesis"
```

**Output:**
5 varied questions (MCQ, True/False, Short Answer) covering the topic with complete answers.

---

### 📅 Study Planning

**Input:**

```
Subject="Data Science", Duration="3 weeks"
```

**Output:**
Structured 21-day learning roadmap with daily objectives and milestones.

---

### 🧮 Problem Solving

**Input:**

```
"Solve: 2x + 5 = 15"
```

**Output:**
Step-by-step mathematical solution with clear explanations at each stage.

---

## 🛠️ Technical Details

### 🧠 Model Information

* **Base Model:** IBM Granite 3.2-2B Instruct
* **Architecture:** Transformer-based causal language model
* **Precision:** FP16 (GPU) / FP32 (CPU)
* **Context Length:**

  * Input: 512 tokens
  * Output: 1024 tokens

---

### ⚙️ Performance Optimizations

* Automatic GPU detection and utilization
* Dynamic device mapping
* Memory-efficient `torch` operations
* Lightweight Gradio interface with:

  * Copy buttons for easy content sharing
  * Responsive layout for mobile and desktop

---

## 🔒 Privacy & Security

* All processing happens **locally** or within your **Google Colab** environment.
* **No data is stored or transmitted** to any external servers.
* Model responses are generated in real-time.
* There is **no logging** or saving of user input/output.

---

## 🤝 Contributing

This is an **educational project**, and contributions are welcome!
You can:

* Modify model parameters for different educational levels
* Add new features (e.g., flashcards, diagrams, voice input)
* Optimize performance for specific hardware
* Enhance the user interface and UX design
* Translate for multilingual support

> **To contribute**, please fork the repo and submit a pull request.

---

## 📄 License

This project uses the **IBM Granite model** under its respective license terms.
Please review **IBM's licensing requirements** before using the model for any **commercial** or **enterprise** applications.

---

## ⚠️ Limitations

* AI-generated responses may contain **inaccuracies or outdated information**.
* Designed for **educational assistance only** — not suitable for:

  * Medical, legal, or professional advice
* Performance varies depending on available **computational resources**
* **Internet connection** is required for the **initial model download**

---

## 🚀 Getting Started by Role

| User Type       | Recommendation                                          |
| --------------- | ------------------------------------------------------- |
| 🎓 Beginners    | Use Google Colab — easiest way to get started           |
| 💻 Developers   | Clone the repo and customize locally for your own needs |
| 👩‍🏫 Educators | Integrate with existing LMS or digital classroom tools  |

---

> Built with ❤️ using IBM Granite AI
> 🌐 Optimized for Google Colab | 📚 Focused on accessible, AI-powered education
