# Ex.No.3 – Scenario-Based Report Development Utilizing Diverse Prompting Techniques

### DATE: 3.09.26
### REGISTER NUMBER: 2122223240185

---

## Aim
To write prompts for the following prompt types and evaluate them using one evaluation method (rubric-based scoring):
1. Straightforward Prompts
2. Tabular Format Prompting
3. Preceding Question Prompting
4. Missing Word Prompting

---

## Explanation
**Use Case (Unit 5): AI in Healthcare – Patient Education Chatbot**

A hospital wants to use a generative AI chatbot to teach patients about common health topics such as diabetes, vaccines, nutrition and hygiene. The answers must be accurate, simple and well structured. This report tests four prompt types (from Unit 2) on this scenario. It then compares the AI outputs using a rubric.

**Evaluation Method:** Each output is scored from 1 to 5 on four criteria:

| Criterion | Description |
|-----------|-------------|
| Accuracy | Is the information factually correct? |
| Relevance | Does it answer exactly what was asked? |
| Clarity | Is it easy for a patient to understand? |
| Structure | Is the format suitable for the prompt type? |

---

## Procedure

### 1. Straightforward Prompts
A straightforward prompt is a direct, clear instruction with no extra context. It works best for short, factual answers.

**Prompt 1:** *"Define photosynthesis in one sentence."*

> **Output:** Photosynthesis is the process by which green plants use sunlight, water and carbon dioxide to produce glucose and release oxygen.

**Prompt 2:** *"List three advantages of electric vehicles."*

> **Output:**
> 1. Zero tailpipe emissions, which reduces air pollution.
> 2. Lower running and maintenance costs than petrol/diesel vehicles.
> 3. Quiet operation and instant torque for smooth acceleration.

**Use-case Prompt:** *"Define Type 2 diabetes in one sentence."*

> **Output:** Type 2 diabetes is a long-term condition in which the body does not use insulin properly, causing high blood sugar levels.

---

### 2. Tabular Format Prompting
A tabular prompt asks the model to arrange information in rows and columns. This makes comparisons easy to read.

**Prompt 1:** *"Compare and contrast AC and DC current in a table."*

> **Output:**
>
> | Feature | AC (Alternating Current) | DC (Direct Current) |
> |---------|--------------------------|---------------------|
> | Direction of flow | Changes direction periodically | Flows in one direction |
> | Frequency | 50 Hz / 60 Hz | 0 Hz |
> | Source | Generators, power grid | Batteries, solar cells |
> | Transmission | Efficient over long distances | Losses over long distances (except HVDC) |
> | Applications | Home appliances, industries | Electronics, mobile phones, EVs |

**Prompt 2:** *"Provide a table listing five programming languages, their paradigms, and one use case each."*

> **Output:**
>
> | Language | Paradigm | Use Case |
> |----------|----------|----------|
> | Python | Multi-paradigm (OOP, functional, procedural) | Data science and AI |
> | Java | Object-oriented | Enterprise and Android apps |
> | C | Procedural | Operating systems, embedded systems |
> | JavaScript | Event-driven, functional, OOP | Web development |
> | Haskell | Purely functional | Research and compilers |

**Use-case Prompt:** *"Compare Type 1 and Type 2 diabetes in a table."*

> **Output:**
>
> | Feature | Type 1 Diabetes | Type 2 Diabetes |
> |---------|-----------------|-----------------|
> | Cause | Autoimmune destruction of insulin cells | Insulin resistance |
> | Common age of onset | Childhood / young adults | Adults (increasingly in youth) |
> | Treatment | Insulin injections | Lifestyle changes, oral drugs, sometimes insulin |
> | Prevention | Not preventable | Often preventable with diet and exercise |

---

### 3. Preceding Question Prompting
A preceding question comes before the main instruction. It sets up the context so the model reasons first and then explains in more depth.

**Prompt 1:** *"Why is climate change a global concern? Explain how greenhouse gases contribute to global warming."*

> **Output:** Climate change is a global concern because it affects every country. It brings rising sea levels, extreme weather, food shortages and loss of biodiversity. Greenhouse gases such as carbon dioxide, methane and nitrous oxide trap heat in the atmosphere. Sunlight warms the Earth's surface, and the Earth radiates this heat back as infrared energy. The gases absorb and re-emit that energy, so less heat escapes to space. Human activities like burning fossil fuels and deforestation increase these gases, which strengthens the effect and raises global temperatures.

**Prompt 2:** *"How do vaccines work? Describe the process of immunization in simple terms."*

> **Output:** Vaccines work by training the immune system to recognise a germ without causing the disease. A vaccine contains a weakened, inactivated or partial form of the germ, or instructions (like mRNA) to make a harmless piece of it. The body responds by making antibodies and memory cells. If the real germ enters later, the immune system recognises it quickly and fights it off before it causes serious illness. This protection is called immunity.

**Use-case Prompt:** *"Why is blood sugar control important for diabetic patients? Explain how diet helps manage diabetes."*

> **Output:** High blood sugar over time damages blood vessels and nerves. This leads to heart disease, kidney failure, vision loss and slow wound healing. Diet helps by controlling how much glucose enters the blood. Eating fibre-rich foods, whole grains and vegetables, and limiting sugar and refined carbohydrates, keeps glucose levels steady. Regular meal timing and portion control also prevent sudden spikes.

---

### 4. Missing Word Prompting
Missing word (fill-in-the-blank) prompting gives a sentence with a gap for the model to complete. It is useful for testing factual recall and for quizzes.

**Prompt 1:** *"The capital of France is ____."*

> **Output:** Paris

**Prompt 2:** *"In photosynthesis, plants absorb sunlight to produce ____."*

> **Output:** glucose (food) and oxygen

**Use-case Prompt:** *"The hormone that regulates blood sugar levels in the body is ____."*

> **Output:** insulin

---

## Evaluation (Rubric Scores out of 5)

| Prompt Type | Accuracy | Relevance | Clarity | Structure | Total (/20) |
|-------------|:--------:|:---------:|:-------:|:---------:|:-----------:|
| Straightforward | 5 | 5 | 5 | 4 | 19 |
| Tabular Format | 5 | 5 | 5 | 5 | 20 |
| Preceding Question | 5 | 5 | 4 | 4 | 18 |
| Missing Word | 5 | 5 | 5 | 3 | 18 |

**Observations:**
- **Straightforward prompts** gave short, precise answers. They are ideal for quick definitions for patients.
- **Tabular prompts** gave the most organised output. They are best for comparing conditions or treatments.
- **Preceding question prompts** gave deeper, reasoned explanations. They are good for educating patients on the *why* behind medical advice.
- **Missing word prompts** were accurate but gave very little detail. They suit quizzes and knowledge checks more than explanations.

---

## Conclusion
Each prompt type shapes the AI's response in a different way. For the healthcare patient-education chatbot:
- Straightforward prompts suit quick facts.
- Tabular prompts suit comparisons.
- Preceding question prompts suit detailed explanations.
- Missing word prompts suit interactive quizzes.

Choosing the right prompting technique for each task improves the accuracy, clarity and usefulness of AI-generated content.

---

## Result
The various types of prompts were executed successfully and the report was generated.

**Thus, the prompts were executed successfully.**
