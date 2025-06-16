<p align="center">
  <img src="assets/banner_building_effective_agents.png" width="80%" alt="Building Effective AI Agents on AWS">
</p>

# 🧠 Building Effective AI Agents on AWS

Agentic AI is a game-changer. Instead of relying on a single massive model for every task, we orchestrate specialized tools, models, and workflows in modular, scalable ways. These agentic systems allow us to reason, decide, and act in cost-efficient and context-aware pipelines.

Why agents instead of plain LLMs?
- 🧠 **Smarter**: Tools + models = decision-making with memory and structure
- 💸 **Cheaper**: Use smaller models/tools only when needed (pay-as-you-go)
- 🧰 **Modular**: Add/replace tools without retraining everything
- 📊 **Traceable**: With observability tools like Langfuse
- ⚡ **Faster to Iterate**: Custom logic with better control

---

## 🌟 This Repo Is Based On:

Hands-on work from the **AWS GenAI Agents Workshop**, focusing on building, fine-tuning, and deploying **agentic AI systems** using:

- [Amazon Bedrock](https://aws.amazon.com/bedrock/)
- [Amazon SageMaker](https://aws.amazon.com/sagemaker/)
- [Strand](https://github.com/aws/strands)
- [CrewAI](https://github.com/joaomdmoura/crewai)
- [LangGraph](https://github.com/langchain-ai/langgraph)
- [Langfuse](https://www.langfuse.com/) for observability

> ⚠️ This is a **refined, simplified** version of the original [AWS workshop repo](https://github.com/aws-samples/generative-ai-on-amazon-sagemaker/tree/main/workshops/diy-agents-with-sagemaker-and-bedrock), meant for reproducibility and educational sharing.

---

## 📌 Workshop Highlights

- ✅ Fine-tuned and deployed an LLM using **SageMaker Studio**
- ✅ Used **Amazon Bedrock** to access foundation models like Claude, LLaMA 3
- ✅ Defined tools for DSL (OpenSearch, GuardDuty) and blog summarization
- ✅ Built agents using **CrewAI** and **Strands**
- ✅ Chained agents using **Evaluator-Optimizer** and **Orchestrator-Worker** patterns
- ✅ Enabled **Langfuse observability** to monitor agent behavior

---

## 🗂 Repo Sections

| Folder | Purpose |
|--------|---------|
| `0-setup-environment/` | Setup virtual environment and SageMaker Studio |
| `1-agent-inference/` | Use Bedrock and SageMaker for inference |
| `2-tools-and-integration/` | Build and register custom tools |
| `3-building-agents/` | Define simple and complex agents |
| `4-frameworks/` | Examples using CrewAI and Strands |
| `5-observability/` | Langfuse integration for API tracing |
| `special-usecases/` | Text-to-SQL, DSL with MCP server, and more |

---

## 🔧 Setup Instructions

```bash
git clone https://github.com/YOUR_USERNAME/aws-agentic-ai-workshop.git
cd aws-agentic-ai-workshop
python -m venv genai-env
source genai-env/bin/activate      # or use genai-env\Scripts\activate on Windows
pip install -r requirements.txt
jupyter lab
```

---

## 📣 Credits

Created during AWS GenAI Workshop  
Curated & restructured by [Sahar Zargarzadeh](https://github.com/SaharZargarzadeh)
