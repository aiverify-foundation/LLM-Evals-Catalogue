## Cataloguing LLM Evaluations

The table below provides a comprehensive catalogue of the Large Language Model (LLM) evaluation frameworks, benchmarks and papers we've surveyed in our paper, <a href = "https://aiverifyfoundation.sg/downloads/Cataloguing_LLM_Evaluations.pdf">"Cataloguing LLM Evaluations"</a>. It organizes them based on the taxonomy proposed in our paper.

The realm of LLM evaluation is advancing at an unparalleled pace. Collaboration with the broader community is pivotal to maintaining the relevance and utility of our work.

To that end, <b>we invite submissions of LLM evaluation frameworks, benchmarks, and papers for inclusion in this catalogue</b>. 

Before you [raise a PR for a new submission](https://github.com/IMDA-BTG/LLM-Evals-Catalogue/pulls), please read our [contribution guidelines](https://github.com/IMDA-BTG/LLM-Evals-Catalogue/blob/main/docs/CONTRIBUTING.md).
Submissions will be reviewed and integrated into the catalogue on a rolling basis.

For any inquiries, feel free to reach out to us at info@aiverify.sg.

<table>  
  <tr>  
    <th>Task/Attribute</th>  
    <th>Evaluation Framework/Benchmark/Paper</th>  
    <th>Testing Approach</th>  
  </tr>  
  <tr>  
    <td colspan="3"><strong>1.1. Natural Language Understanding</strong></td>  
  </tr>  
  <tr>  
    <td rowspan="3" colspan="1">Text classification</td>
    <td><a href="https://crfm.stanford.edu/helm/latest/" target="_blank">HELM</a><br><ul><li>Miscellaneous text classification</li></ul></td>  
    <td>Benchmarking</td>  
  </tr>  
  <tr>  
    <td><a href="https://github.com/google/BIG-bench/blob/main/bigbench/benchmark_tasks/keywords_to_tasks.md#context-length" target="_blank">Big-bench</a><br><ul><li>Emotional understanding</li><li>Intent recognition</li><li>Humor</li></ul></td>  
    <td>Benchmarking</td>  
  </tr>
  <tr>  
    <td><a href="https://huggingface.co/tasks" target="_blank">Hugging Face</a><br><ul><li>Text classification</li><li>Token classification</li><li>Zero-shot classification</li></ul></td>  
    <td>Benchmarking</td>  
  </tr>
  <tr>  
    <td rowspan="3" colspan="1">Sentiment analysis</td>
    <td><a href="https://crfm.stanford.edu/helm/latest/" target="_blank">HELM</a><br><ul><li>Sentiment analysis</li></ul></td>  
    <td>Benchmarking</td>  
  </tr>
  <tr>  
    <td><a href="https://github.com/EleutherAI/lm-evaluation-harness/tree/master" target="_blank">Evaluation Harness</a><br><ul><li>GLUE</li></ul></td>  
    <td>Benchmarking</td>  
  </tr>
  <tr>
    <td><a href="https://github.com/google/BIG-bench/blob/main/bigbench/benchmark_tasks/keywords_to_tasks.md#context-length" target="_blank">Big-bench</a><br><ul><li>Emotional understanding</li></ul></td>  
    <td>Benchmarking</td>  
  </tr>
  <tr>  
    <td rowspan="3" colspan="1">Toxicity detection</td>
    <td><a href="https://crfm.stanford.edu/helm/latest/" target="_blank">HELM</a><br><ul><li>Toxicity detection</li></ul></td>  
    <td>Benchmarking</td>  
  </tr>
  <tr>  
    <td><a href="https://github.com/EleutherAI/lm-evaluation-harness/tree/master" target="_blank">Evaluation Harness</a><br><ul><li>ToxiGen</li></ul></td>  
    <td>Benchmarking</td>  
  </tr>
  <tr>
    <td><a href="https://github.com/google/BIG-bench/blob/main/bigbench/benchmark_tasks/keywords_to_tasks.md#context-length" target="_blank">Big-bench</a><br><ul><li>Toxicity</li></ul></td>  
    <td>Benchmarking</td>  
  </tr>
  <tr>  
    <td rowspan="1" colspan="1">Information retrieval</td>
    <td><a href="https://crfm.stanford.edu/helm/latest/" target="_blank">HELM</a><br><ul><li>Information retrieval</li></ul></td>  
    <td>Benchmarking</td>  
  </tr>
  <tr>  
    <td rowspan="2" colspan="1">Sufficient information</td>
    <td><a href="https://github.com/google/BIG-bench/blob/main/bigbench/benchmark_tasks/keywords_to_tasks.md#context-length" target="_blank">Big-bench</a><br><ul><li>Sufficient information</li></ul></td>  
    <td>Benchmarking</td>  
  </tr>
  <tr>
    <td><a href="https://github.com/kaistAI/FLASK" target="_blank">FLASK</a><br><ul><li>Metacognition</li></ul></td>  
    <td>Benchmarking (with human and model scoring)</td>  
  </tr>
  <tr>  
    <td rowspan="2" colspan="1">Natural language inference</td>
    <td><a href="https://github.com/google/BIG-bench/blob/main/bigbench/benchmark_tasks/keywords_to_tasks.md#context-length" target="_blank" target="_blank">Big-bench</a><br><ul><li>Analytic entailment (specific task)</li><li>Formal fallacies and syllogisms with negation (specific task)</li><li>Entailed polarity (specific task)</li></ul></td>  
    <td>Benchmarking</td>
  <tr>
    <td><a href="https://github.com/EleutherAI/lm-evaluation-harness/tree/master" target="_blank">Evaluation Harness</a><br><ul><li>GLUE</li></ul></td>  
    <td>Benchmarking</td>  
  </tr>
  <tr>  
    <td rowspan="4" colspan="1">General English understanding</td>
    <td><a href="https://crfm.stanford.edu/helm/latest/" target="_blank">HELM</a><br><ul><li>Language</li></ul></td>  
    <td>Benchmarking</td>  
  </tr>
  <tr>
    <td><a href="https://github.com/google/BIG-bench/blob/main/bigbench/benchmark_tasks/keywords_to_tasks.md#context-length" target="_blank">Big-bench</a><br><ul><li>Morphology</li><li>Grammar</li><li>Syntax</li></ul></td>  
    <td>Benchmarking</td>  
  </tr>
  <tr>
    <td><a href="https://github.com/EleutherAI/lm-evaluation-harness/tree/master" target="_blank">Evaluation Harness</a><br><ul><li>BLiMP</li></ul></td>  
    <td>Benchmarking</td>  
  </tr>
  <tr>
    <td><a href="https://www.mosaicml.com/llm-evaluation" target="_blank">Eval Gauntlet</a><br><ul><li>Language Understanding</li></ul></td>  
    <td>Benchmarking</td>  
  </tr>
  <tr>  
    <td colspan="3"><strong>1.2. Natural Language Generation</strong></td>  
  </tr>
  <tr>  
    <td rowspan="4" colspan="1">Summarization</td>
    <td><a href="https://crfm.stanford.edu/helm/latest/" target="_blank">HELM</a><br><ul><li>Summarization</li></ul></td>  
    <td>Benchmarking</td>
  <tr>  
    <td><a href="https://github.com/google/BIG-bench/blob/main/bigbench/benchmark_tasks/keywords_to_tasks.md#context-length" target="_blank">Big-bench</a><br><ul><li>Summarization</li></ul></td>  
    <td>Benchmarking</td>  
  </tr>
  <tr>
    <td><a href="https://github.com/EleutherAI/lm-evaluation-harness/tree/master" target="_blank">Evaluation Harness</a><br><ul><li>BLiMP</li></ul></td>  
    <td>Benchmarking</td>  
  </tr>
  <tr>  
    <td><a href="https://huggingface.co/tasks" target="_blank">Hugging Face</a><br><ul><li>Summarization</li></ul></td>  
    <td>Benchmarking</td>  
  </tr>
  <tr>  
    <td rowspan="6" colspan="1">Question generation and answering</td>
    <td><a href="https://crfm.stanford.edu/helm/latest/" target="_blank">HELM</a><br><ul><li>Question answering</li></ul></td>  
    <td>Benchmarking</td>
  </tr>
  <tr>  
    <td><a href="https://github.com/google/BIG-bench/blob/main/bigbench/benchmark_tasks/keywords_to_tasks.md#context-length" target="_blank">Big-bench</a><br><ul><li>Contextual question answering</li><li>Reading comprehension</li><li>Question generation</li></ul></td>  
    <td>Benchmarking</td>  
  </tr>
  <tr>
    <td><a href="https://github.com/EleutherAI/lm-evaluation-harness/tree/master" target="_blank">Evaluation Harness</a><br><ul><li>CoQA</li><li>ARC</li></ul></td>  
    <td>Benchmarking</td>  
  </tr>
  <tr>
    <td><a href="https://github.com/kaistAI/FLASK" target="_blank">FLASK</a><br><ul><li>Logical correctness</li><li>Logical robustness</li><li>Logical efficiency</li><li>Comprehension</li><li>Completeness</li></ul></td>  
    <td>Benchmarking (with human and model scoring)</td>  
  </tr>
  <tr>  
    <td><a href="https://huggingface.co/tasks" target="_blank">Hugging Face</a><br><ul><li>Question answering</li></ul></td>  
    <td>Benchmarking</td>  
  </tr>
  <tr>
    <td><a href="https://www.mosaicml.com/llm-evaluation" target="_blank">Eval Gauntlet</a><br><ul><li>Reading comprehension</li></ul></td>  
    <td>Benchmarking</td>  
  </tr>
  <tr>  
    <td rowspan="3" colspan="1">Conversations and dialogue</td>
    <td><a href="https://arxiv.org/abs/2306.05685" target="_blank">MT-bench</a></td>  
    <td>Benchmarking (with human and model scoring)</td>
  </tr>
    <tr>
    <td><a href="https://github.com/EleutherAI/lm-evaluation-harness/tree/master" target="_blank">Evaluation Harness</a><br><ul><li>MuTual</li></td>  
    <td>Benchmarking</td>  
  </tr>
  <tr>  
    <td><a href="https://huggingface.co/tasks" target="_blank">Hugging Face</a><br><ul><li>Conversational</li></ul></td>  
    <td>Benchmarking</td>  
  </tr>
  <tr>  
    <td rowspan="1" colspan="1">Paraphrasing</td>
    <td><a href="https://github.com/google/BIG-bench/blob/main/bigbench/benchmark_tasks/keywords_to_tasks.md#context-length" target="_blank">Big-bench</a><br><ul><li>Paraphrase</li></ul></td>  
    <td>Benchmarking</td>  
  </tr>
  <tr>  
    <td rowspan="3" colspan="1">Other response qualities</td>
    <td><a href="https://github.com/kaistAI/FLASK" target="_blank">FLASK</a><br><ul><li>Readability</li><li>Conciseness</li><li>Insightfulness</li></ul></td>  
    <td>Benchmarking (with human and model scoring)</td>
  </tr>
    <tr>
    <td><a href="https://github.com/google/BIG-bench/blob/main/bigbench/benchmark_tasks/keywords_to_tasks.md#context-length" target="_blank">Big-bench</a><br><ul><li>Creativity</li></td>  
    <td>Benchmarking</td>  
  </tr>
  <tr>  
    <td><a href="https://arxiv.org/abs/2206.08932" target="_blank">Putting GPT-3's Creativity to the (Alternative Uses) Test</a></td>  
    <td>Benchmarking (with human scoring)</td>  
  </tr>
  <tr>  
    <td rowspan="1" colspan="1">Miscellaneous text generation</td>
    <td><a href="https://huggingface.co/tasks" target="_blank">Hugging Face</a><br><ul><li>Fill-mask</li><li>Text generation</li></ul></td>  
    <td>Benchmarking</td>  
  </tr>
<tr>  
    <td rowspan="4" colspan="1"><strong>1.3. Reasoning</strong></td>
    <td><a href="https://crfm.stanford.edu/helm/latest/" target="_blank">HELM</a><br><ul><li>Reasoning</ul></td>  
    <td>Benchmarking</td>
  </tr>
      <tr>
    <td><a href="https://github.com/google/BIG-bench/blob/main/bigbench/benchmark_tasks/keywords_to_tasks.md#context-length" target="_blank">Big-bench</a><br>
<ul>
    <li>Algorithms</li>
    <li>Logical reasoning</li>
    <li>Implicit reasoning</li>
    <li>Mathematics</li>
    <li>Arithmetic</li>
    <li>Algebra</li>
    <li>Mathematical proof</li>
    <li>Fallacy</li>
    <li>Negation</li>
    <li>Computer code</li>
    <li>Probabilistic reasoning</li>
    <li>Social reasoning</li>
    <li>Analogical reasoning</li>
    <li>Multi-step</li>
    <li>Understanding the World</li>
</ul>
</td>
    <td>Benchmarking</td>  
  </tr>
    <tr>
    <td><a href="https://github.com/EleutherAI/lm-evaluation-harness/tree/master" target="_blank">Evaluation Harness</a><br>
<ul>
    <li>PIQA, PROST - Physical reasoning</li>
    <li>MC-TACO - Temporal reasoning</li>
    <li>MathQA - Mathematical reasoning</li>
    <li>LogiQA - Logical reasoning</li>
    <li>SAT Analogy Questions - Similarity of semantic relations</li>
    <li>DROP, MuTual – Multi-step reasoning</li>
</ul>
</td>
    <td>Benchmarking</td>  
  </tr>
  <tr>
    <td><a href="https://www.mosaicml.com/llm-evaluation" target="_blank">Eval Gauntlet</a><br><ul><li>Commonsense reasoning</li><li>Symbolic problem solving</li><li>Programming</li></ul></td>  
    <td>Benchmarking</td>  
  </tr>
<tr>  
    <td rowspan="5" colspan="1"><strong>1.4. Knowledge and factuality</strong></td>
    <td><a href="https://crfm.stanford.edu/helm/latest/" target="_blank">HELM</a><br><ul><li>Knowledge</ul></td>  
    <td>Benchmarking</td>
  </tr>
    <tr>  
    <td><a href="https://github.com/google/BIG-bench/blob/main/bigbench/benchmark_tasks/keywords_to_tasks.md#context-length" target="_blank">Big-bench</a><br><ul><li>Context Free Question Answering</li></ul></td>  
    <td>Benchmarking</td>  
  </tr>
    <tr>
    <td><a href="https://github.com/EleutherAI/lm-evaluation-harness/tree/master" target="_blank">Evaluation Harness</a><br>
<ul>
    <li>HellaSwag, OpenBookQA - General commonsense knowledge</li>
    <li>TruthfulQA - Factuality of knowledge</li>
</ul>
</td>
    <td>Benchmarking</td>  
  </tr>
  <tr>
    <td><a href="https://github.com/kaistAI/FLASK" target="_blank">FLASK</a><br><ul><li>Background Knowledge</li></ul></td>  
    <td>Benchmarking (with human and model scoring)</td>  
  </tr>
  <tr>
    <td><a href="https://www.mosaicml.com/llm-evaluation" target="_blank">Eval Gauntlet</a><br><ul><li>World Knowledge</li></ul></td>  
    <td>Benchmarking</td>  
  </tr>
<tr>
    <td rowspan="4" colspan="1"><strong>1.5. Effectiveness of tool use</strong></td>
    <td><a href="https://arxiv.org/abs/2303.17580" target="_blank">HuggingGPT</a></td>
    <td>Benchmarking (with human and model scoring)</td>
</tr>
<tr>
    <td><a href="https://arxiv.org/abs/2205.12255" target="_blank">TALM</a></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td><a href="https://arxiv.org/abs/2302.04761" target="_blank">Toolformer</a></td>
    <td>Benchmarking (with human scoring)</td>
</tr>
<tr>
    <td><a href="https://arxiv.org/abs/2307.16789" target="_blank">ToolLLM</a></td>
    <td>Benchmarking (with model scoring)</td>
</tr>
<tr>
    <td rowspan="6" colspan="1"><strong>1.6. Multilingualism</strong></td>
    <td><a href="https://github.com/google/BIG-bench/blob/main/bigbench/benchmark_tasks/keywords_to_tasks.md#context-length" target="_blank">Big-bench</a><br><ul><li>Low-resource language</li><li>Non-English</li><li>Translation</li></ul></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td><a href="https://github.com/EleutherAI/lm-evaluation-harness/tree/master" target="_blank">Evaluation Harness</a><br><ul><li>C-Eval (<i>Chinese evaluation suite</i>)</li><li>MGSM</li><li>Translation</li></ul></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td><a href="https://arxiv.org/abs/2308.16884">BELEBELE</a></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td><a href="https://arxiv.org/abs/2204.08582">MASSIVE</a></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td><a href="https://crfm.stanford.edu/helm/latest/" target="_blank">HELM</a><br><ul><li>Language (Twitter AAE)</li></ul></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td><a href="https://www.mosaicml.com/llm-evaluation" target="_blank">Eval Gauntlet</a><br><ul><li>Language Understanding</li></ul></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td rowspan="2" colspan="1"><strong>1.7. Context length</strong></td>
    <td><a href="https://github.com/google/BIG-bench/blob/main/bigbench/benchmark_tasks/keywords_to_tasks.md#context-length" target="_blank">Big-bench</a><br><ul><li>Context length</li></ul></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td><a href="https://github.com/EleutherAI/lm-evaluation-harness/tree/master" target="_blank">Evaluation Harness</a><br><ul><li>SCROLLS</li></ul></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td rowspan="1" colspan="1"><strong>2.1. Law</strong></td>
    <td><a href="https://arxiv.org/pdf/2308.11462.pdf" target="_blank">LegalBench</a></td>
    <td>Benchmarking (with algorithmic and human scoring)</td>
</tr>
<tr>
    <td rowspan="2" colspan="1"><strong>2.2. Medicine</strong></td>
    <td><a href="https://arxiv.org/abs/2212.13138" target="_blank">Large Language Models Encode Clinical Knowledge</a></td>
    <td>Benchmarking (with human scoring)</td>
</tr>
<tr>
    <td><a href="https://arxiv.org/abs/2307.14334" target="_blank">Towards Generalist Biomedical AI</a></td>
    <td>Benchmarking (with human scoring)</td>
</tr>
<tr>
    <td rowspan="1" colspan="1"><strong>2.3. Finance</strong></td>
    <td><a href="https://arxiv.org/abs/2303.17564" target="_blank">BloombergGPT</a></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td rowspan="4" colspan="1"><strong>3.1. Toxicity generation</strong></td>
    <td><a href="https://crfm.stanford.edu/helm/latest/" target="_blank">HELM</a><br><ul><li>Toxicity</li></ul></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td><a href="https://decodingtrust.github.io/" target="_blank">DecodingTrust</a><br><ul><li>Toxicity</li></ul></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td><a href="https://arxiv.org/abs/2209.07858" target="_blank">Red Teaming Language Models to Reduce Harms</a></td>
    <td>Manual Red Teaming</td>
</tr>
<tr>
    <td><a href="https://arxiv.org/abs/2202.03286" target="_blank">Red Teaming Language Models with Language Models</a></td>
    <td>Automated Red Teaming</td>
</tr>
  <tr>  
    <td colspan="3" rowspan="1"><strong>3.2. Bias</strong></td>  
  </tr>
<tr>
    <td rowspan="2" colspan="1">Demographical representation</td>
    <td><a href="https://crfm.stanford.edu/helm/latest/" target="_blank">HELM</a></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td><a href="https://arxiv.org/abs/2205.09209" target="_blank">Finding New Biases in Language Models with a Holistic Descriptor Dataset</a></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td rowspan="5" colspan="1">Stereotype bias</td>
    <td><a href="https://crfm.stanford.edu/helm/latest/" target="_blank">HELM</a><br><ul><li>Bias</li></ul></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td><a href="https://decodingtrust.github.io/" target="_blank">DecodingTrust</a><br><ul><li>Stereotype Bias</li></ul></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td><a href="https://github.com/google/BIG-bench/blob/main/bigbench/benchmark_tasks/keywords_to_tasks.md#context-length" target="_blank">Big-bench</a><br><ul><li>Social bias</li><li>Racial bias</li><li>Gender bias</li><li>Religious bias</li></ul></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td><a href="https://github.com/EleutherAI/lm-evaluation-harness/tree/master" target="_blank">Evaluation Harness</a><br><ul><li>CrowS-Pairs</li></ul></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td><a href="https://arxiv.org/abs/2209.07858" target="_blank">Red Teaming Language Models to Reduce Harms</a></td>
    <td>Manual Red Teaming</td>
</tr>
<tr>
    <td>Fairness</td>
    <td><a href="https://decodingtrust.github.io/" target="_blank">DecodingTrust</a><br><ul><li>Fairness</li></ul></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td>Distributional bias</td>
    <td><a href="https://arxiv.org/abs/2202.03286" target="_blank">Red Teaming Language Models with Language Models</a></td>
    <td>Automated Red Teaming</td>
</tr>
<tr>
    <td>Representation of subjective opinions</td>
    <td><a href="https://arxiv.org/abs/2306.16388" target="_blank">Towards Measuring the Representation of Subjective Global Opinions in Language Models</a></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td rowspan="2" colspan="1">Political bias</td>
    <td><a href="https://arxiv.org/abs/2305.08283" target="_blank">From Pretraining Data to Language Models to Downstream Tasks: Tracking the Trails of Political Biases Leading to Unfair NLP Models</a></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td><a href="https://arxiv.org/abs/2304.07333" target="_blank">The Self-Perception and Political Biases of ChatGPT</a></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td>Capability fairness</td>
    <td><a href="https://crfm.stanford.edu/helm/latest/" target="_blank">HELM</a><br><ul><li>Language (Twitter AAE)</li></ul></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td rowspan="2" colspan="1"><strong>3.3. Machine ethics</strong></td>
    <td><a href="https://decodingtrust.github.io/" target="_blank">DecodingTrust</a><br><ul><li>Machine Ethics</li></ul></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td><a href="https://github.com/EleutherAI/lm-evaluation-harness/tree/master" target="_blank">Evaluation Harness</a><br><ul><li>ETHICS</li></ul></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td rowspan="3" colspan="1"><strong>3.4. Psychological traits</strong></td>
    <td><a href="https://arxiv.org/abs/2212.10529" target="_blank">Does GPT-3 Demonstrate Psychopathy?</a></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td><a href="https://arxiv.org/abs/2204.12000" target="_blank">Estimating the Personality of White-Box Language Models</a></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td><a href="https://arxiv.org/abs/2304.07333" target="_blank">The Self-Perception and Political Biases of ChatGPT</a></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td rowspan="4" colspan="1"><strong>3.5. Robustness</strong></td>
    <td><a href="https://crfm.stanford.edu/helm/latest/" target="_blank">HELM</a><br><ul><li>Robustness to contrast sets</li></ul></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td><a href="https://decodingtrust.github.io/" target="_blank">DecodingTrust</a><br><ul><li>Out-of-Distribution Robustness</li><li>Adversarial Robustness</li><li>Robustness Against Adversarial Demonstrations</li></ul></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td><a href="https://github.com/google/BIG-bench/blob/main/bigbench/benchmark_tasks/keywords_to_tasks.md#context-length" target="_blank">Big-bench</a><br><ul><li>Out-of-Distribution Robustness</li></ul></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td><a href="https://arxiv.org/abs/2303.06074" target="_blank">Susceptibility to Influence of Large Language Models</a></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td rowspan="5" colspan="1"><strong>3.6. Data governance</strong></td>
    <td><a href="https://decodingtrust.github.io/" target="_blank">DecodingTrust</a><br><ul><li>Privacy</li></ul></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td><a href="https://crfm.stanford.edu/helm/latest/" target="_blank">HELM</a><br><ul><li>Memorization and copyright</li></ul></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td><a href="https://arxiv.org/abs/2209.07858" target="_blank">Red Teaming Language Models to Reduce Harms</a></td>
    <td>Manual Red Teaming</td>
</tr>
<tr>
    <td><a href="https://arxiv.org/abs/2202.03286" target="_blank">Red Teaming Language Models with Language Models</a></td>
    <td>Automated Red Teaming</td>
</tr>
<tr>
    <td><a href="https://arxiv.org/abs/2304.08637" target="_blank">An Evaluation on Large Language Model Outputs: Discourse and Memorization</a></td>
    <td>Benchmarking (with human scoring)</td>
</tr>
<tr>  
    <td colspan="3" rowspan="1"><strong>4.1. Dangerous Capabilities</strong></td>  
  </tr>
<tr>
    <td rowspan="1" colspan="1">Offensive cyber capabilities</td>
    <td><a href="https://cdn.openai.com/papers/gpt-4-system-card.pdf" target="_blank">GPT-4 System Card</a><br><ul><li>Cybersecurity</li><ul></td>
    <td>System Card</td>
</tr>
<tr>
    <td rowspan="1" colspan="1">Weapons acquisition</td>
    <td><a href="https://cdn.openai.com/papers/gpt-4-system-card.pdf" target="_blank">GPT-4 System Card</a><br><ul><li>Proliferation of Conventional and Unconventional Weapons</li><ul></td>
    <td>System Card</td>
</tr>
<tr>
    <td rowspan="1" colspan="1">Self and situation awareness</td>
    <td><a href="https://github.com/google/BIG-bench/blob/main/bigbench/benchmark_tasks/keywords_to_tasks.md#context-length" target="_blank">Big-bench</a><br><ul><li>Self-Awareness</li><ul></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td rowspan="1" colspan="1">Autonomous replication / self-proliferation</td>
    <td><a href="https://evals.alignment.org/" target="_blank">ARC Evals</a><br><ul><li>Autonomous replication</li><ul></td>
    <td>Manual Red Teaming</td>
</tr>
<tr>
    <td rowspan="3" colspan="1">Persuasion and manipulation</td>
    <td><a href="https://crfm.stanford.edu/helm/latest/" target="_blank">HELM</a><br><ul><li>Narrative Reiteration</li><li>Narrative Wedging</li></ul></td>
    <td>Benchmarking (with human scoring)</td>
</tr>
<tr>
    <td><a href="https://github.com/google/BIG-bench/blob/main/bigbench/benchmark_tasks/keywords_to_tasks.md#context-length" target="_blank">Big-bench</a><br><ul><li>Convince Me (specific task)</li></ul></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td><a href="https://arxiv.org/abs/2302.00560" target="_blank">Co-writing with Opinionated Language Models Afffects Users' Views</a></td>
    <td>Manual Red Teaming</td>
</tr>
<tr>
    <td rowspan="3" colspan="1"><strong>5.1. Misinformation</strong></td>
    <td><a href="https://crfm.stanford.edu/helm/latest/" target="_blank">HELM</a><br><ul><li>Question answering</li><li>Summarization</li></ul></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td><a href="https://github.com/google/BIG-bench/blob/main/bigbench/benchmark_tasks/keywords_to_tasks.md#context-length" target="_blank">Big-bench</a><br><ul><li>Truthfulness</li></ul></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td><a href="https://arxiv.org/abs/2209.07858" target="_blank">Red Teaming Language Models to Reduce Harms</a></td>
    <td>Manual Red Teaming</td>
</tr>
<tr>
    <td rowspan="2" colspan="1"><strong>5.2. Disinformation</strong></td>
    <td><a href="https://crfm.stanford.edu/helm/latest/" target="_blank">HELM</a><br><ul><li>Narrative Reiteration</li><li>Narrative Wedging</li></ul></td>
    <td>Benchmarking (with human scoring)</td>
</tr>
<tr>
    <td><a href="https://github.com/google/BIG-bench/blob/main/bigbench/benchmark_tasks/keywords_to_tasks.md#context-length" target="_blank">Big-bench</a><br><ul><li>Convince Me (specific task)</li></ul></td>
    <td>Benchmarking</td>
</tr>
<tr>
    <td rowspan="1" colspan="1"><strong>5.3. Information on harmful, immoral or illegal activity</strong></td>
    <td><a href="https://arxiv.org/abs/2209.07858" target="_blank">Red Teaming Language Models to Reduce Harms</a></td>
    <td>Manual Red Teaming</td>
</tr>
<tr>
    <td rowspan="1" colspan="1"><strong>5.4. Adult content</strong></td>
    <td><a href="https://arxiv.org/abs/2209.07858" target="_blank">Red Teaming Language Models to Reduce Harms</a></td>
    <td>Manual Red Teaming</td>
</tr>
</table>
