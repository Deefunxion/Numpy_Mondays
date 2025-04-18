# 🧠 Context Map — Playground Setup for Layer 6 Prompt Reasoning

## 🔍 Purpose
To simulate real-time heuristic decision-making in a structured, low-resource context, using a Layer 6 cognitive scaffold applied to administrative law cases.

---

## ⚙️ Environment

- **Platform:** OpenAI Playground
- **Model:** GPT-4
- **Mode:** Assistants (Function + Retrieval)
- **Memory:** Off
- **Tools Activated:** Files + Vector Store
- **Embedding:** text-embedding-3-small (OpenAI)

---

## 🧱 Input Materials

### 📂 Vector Store Files
- `Layer6_Prompt_Collection.md`: primary heuristic scaffold source

### 🗒 User Prompt Example
Compare two administrative choices regarding a citizen with a newly certified 80% disability who applied for a public transport disability card three days after the official distribution deadline. Apply the Take-the-Best Rule from the Layer 6 scaffold.

pgsql
Αντιγραφή
Επεξεργασία

---

## 🧠 System Prompt
```plaintext
You are a heuristic decision agent trained on Layer 6 fast-and-frugal logic. Always select the first valid cue that discriminates between options. Apply stop rule after the cue. Use outcome validity, legal proportionality, and ethical discretion as prioritization order.
