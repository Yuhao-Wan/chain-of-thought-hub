## Engineering 
* [ ] Recommended Prompts
* [ ] Stablize BBH answer extraction
* [ ] GPT-3.5 results for each STL 
* [ ] Make this prompt and the associating prompts as a huggingface dataset
* [ ] Detailed raw results in a shared google sheet
* [ ] Random baseline
* [ ] More models
  * [ ] Galactica
  * [ ] text-bison-001 and chat-bison-001
  * [ ] Bard -- but how to get the online Bard API?
  * [ ] Cohere
  * [ ] AI21Labs
* [ ] More reasoning datasets
  * [ ] Arc-c
  * [ ] Commonsense
  * [ ] [BigCode eval](https://github.com/bigcode-project/bigcode-evaluation-harness)
  * [x] Theorem proving 
  * [x] Coding 
  * [ ] API Call
    * [API Bank](https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/api-bank)
    * [ToolBench](https://github.com/OpenBMB/ToolBench)
  * [ ] proofbank, entailment bank -- maybe sweep all Aristo datasets then see how LLM works 
* [x] Draw a figure about model scale v.s. reasoning accuracy 
* [x] Add Alpaca and Vacuna 
* [ ] Test LLaMA on BBH
* [ ] Fancy tricks in prompt engineering 
* [x] Add smaller LLaMA
* [x] Add Flan-T5

## Research
* [ ] Decoding space 
  * [ ] Do larger models have "larger" decoding space than smaller models? 
  * [ ] Can instruction finetuning "closes" some meaningful/ reasonable decoding path? Can it "open" new decoding paths? 
* [ ] Advanced prompt engineering
  * [ ] Planning and deductive prompting 
  * [x] Dialog in-context learning
* [ ] CoT prompt engineering documentation, including 
  * Stable: 
    * [ ] complexity based prompting
  * Test: 
    * [ ] concise prompting
    * [ ] emphasizing important steps 