# prompt-engineering-techniques-gpt4o
Explore and compare various prompt engineering techniques (zero-shot, few-shot, chain-of-thought, etc.) across GPT-4o-mini and GPT-4o models using real-world tasks to evaluate response quality, coherence, and performance. This project highlights the strengths and limitations of each prompting approach and model.
---
# 🧠 Prompt Engineering Techniques Comparison using GPT-4o and GPT-4o-mini

This project provides an in-depth comparison of different **prompt engineering techniques** applied on **GPT-4o** and **GPT-4o-mini** models. It showcases how various methods like Zero-shot, Few-shot, Chain-of-Thought (CoT), ReAct, and Tree of Thoughts influence model outputs on real-world tasks like sentiment analysis, reasoning, math, classification, and more.

---

## 📌 Project Goal

To compare the output, efficiency, and reasoning capability of GPT-4o vs GPT-4o-mini using various structured prompting techniques and document the pros, cons, and ideal use cases for each.

---

## 📂 Prompt Techniques Covered

| Technique         | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| Zero-shot        | No examples provided; model responds based on general knowledge.            |
| Few-shot         | A few task-specific examples are given before asking the final query.       |
| Chain-of-Thought | Encourages step-by-step reasoning in answers.                               |
| ReAct            | Combines reasoning and action (API calls, tools) in model outputs.          |
| Tree of Thoughts | Encourages the model to explore multiple solution paths.                    |

---

## 🧪 Evaluation Metrics

- ✅ Accuracy  
- 📚 Reasoning Quality  
- ⏱️ Response Time  
- 🎯 Use-case Fit  
- 🤖 Model Understanding Level  

---

## 🧠 Models Used

- 🔹 **GPT-4o-mini** (lightweight, faster version)  
- 🔸 **GPT-4o** (full capability, higher reasoning performance)  

---

## 💻 Tech Stack

- **Python** – prompt orchestration & scripting  
- **OpenAI API** – LLM interactions  
- **Jupyter Notebook** – experiments and analysis  
- **Matplotlib / Seaborn** – result visualization  
- **Pandas** – tabular data handling  

---

## 📊 Results Snapshot

- ✅ **GPT-4o** consistently outperformed **GPT-4o-mini** in Chain-of-Thought and Tree of Thoughts tasks.  
- ✅ **GPT-4o-mini** performed well on Zero-shot and Few-shot tasks with faster response times.  
- ✅ Techniques like ReAct and Tree of Thoughts are best suited for **GPT-4o** due to its reasoning capabilities.  

---

## 🎓 Skills Gained

Through this hands-on project, I learned and applied:

- ✨ Prompt engineering strategies: zero-shot, few-shot, CoT, ReAct, Tree of Thoughts  
- ✨ Using OpenAI’s GPT-4o and GPT-4o-mini via API for evaluation  
- ✨ Structuring and testing LLM performance on real-world tasks  
- ✨ Evaluating LLM output quality and organizing result comparison  
- ✨ Data visualization to compare models & techniques effectively  
- ✨ Experimentation documentation for reproducibility  
- ✨ Applying GenAI to reasoning-based problem solving  

---
## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/GovindaTak/prompt-engineering-techniques-gpt4o.git
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure your OpenAI API key**  :
   use google colab secret ket protector feature .

4. **Run Experiments:**  
   Open the Jupyter notebook inside `/notebooks` and run the cells to reproduce results.

---

## 📮 Feedback & Contributions

Have an idea to improve the prompts? Found better ways to compare models?  
Feel free to fork the repo, submit a pull request, or open an issue!

---

## 📌 License

This project is licensed under the MIT License.
