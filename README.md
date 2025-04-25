# Instruction-Following-Benchmarks
Instruction-following benchmarks have evolved from single-task NLP sets to rich, real-world, and automated evaluations. Early datasets focused on mapping input to output on held-out tasks, giving way to instruction-tuning collections and prompt generalization. Modern evaluations incorporate human prompts, automated judges, style-control, and constraint-based tests. We also highlight recent benchmarks targeting specialized domains, evaluator robustness, and long-context stability.

## 1. Single-Task & Instruction Tuning  
Early instruction tuning aggregated diverse NLP tasks under descriptive prompts, enabling held-out-task evaluation.  
- **GPT-2 Language Modeling**: Foundations of zero-shot mapping $p(y\mid x)$ to $p(y\mid x,\text{task})$   
- **Natural Instructions**: Multi-task QA and classification   
- **TO-Eval**: Text-only prompts across tasks   
- **InstructEval**: Fine-grained held-out task splits   
- **FLAN**: Instruction-tuned on 1,800 tasks   
- **SuperNI-Test**: Held-out instruction evaluation 

## 2. Prompt Generalization  
As tuning scaled, models began handling arbitrary user prompts, moving beyond narrow task descriptions.  
- **ShareGPT**: Real user prompts from ChatGPT logs   
- **FreeDolly**: Crowdsourced web prompts   
- **OpenAssistant**: Community-driven prompt bank   
- **Chatbot Arena**: Elo-based human comparisons   

## 3. Automated Evaluation  
To reduce human labeling costs, LLMs themselves judge instruction adherence.  
- **AlpacaEval**: GPT-based pairwise scoring   
- **VicunaEval**: Multi-model automated ranking   
- **Arena Hard Auto**: Large-scale GPT-4 judging   

## 4. Style-Control  
Benchmarks disentangling style biases from content accuracy.  
- **StyleControl Arena**: Balancing verbosity and clarity   
- **Human-Length Eval**: Controlling response length   
- **Disentangling Styles**: Evaluating prompt style influence   

## 5. Constraint-Based Tests  
Absolute evaluation via rule-verifiable constraints.  
- **IfEval**: 25 rule-based prompt constraints   
- **FollowBench**: LLM-verified constraints   
- **WildBench**: Human-annotated checklists
- **CoDI-Eval**: Controllable generation under constraints 

## 6. Meta-Evaluation & Robustness  
Recent works challenge LLM evaluators and extend instruction testing to expert domains.  
- **LLMBar**: Adversarial meta-evaluation of instruction following 
- **IfIR**: Instruction-following IR in finance, law, science, healthcare 
- **DRFR**: Decomposed Requirements Following Ratio metric 
- **LIFBench**: Long-context instruction stability   
- **HREF**: Human-response guided evaluation 
- **CIF-Bench**: Chinese instruction generalizability 
- **MedS-Bench**: Clinical instruction following 
- **Knowledge-Task IF Eval**: Instruction tests over QA tasks 
---


