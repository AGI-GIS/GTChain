# GTChain
## Geospatial large language model trained with a simulated environment for generating tool-use chains autonomously
we propose a framework for training a Geospatial large language model to generate Tool-use Chains autonomously (GTChain). Specifically, we design a seed task-guided self-instruct strategy to generate a geospatial tool-use instruction tuning dataset within a simulated environment, which includes a simulated multiple-step processing environment and simulated geospatial data stream. Subsequently, an open-source general-domain LLM, LLaMA-2-7B, is fine-tuned on the collected instruction data to understand geospatial tasks and learn how to generate geospatial tool-use chains. Finally, we also collect an evaluation dataset to serve as a benchmark for assessing the geospatial tool-use ability of LLMs. Based on the evaluation dataset, experimental results demonstrate that the fine-tuned LLM can effectively solve geospatial tasks with the provided tools, which validates the effectiveness of our framework.
## Trainging Data
We release training data samples for training GTChain, stored in **TrainingData.json**. You can contact the author to obtain all the training data.
## Evaluation Data
We release an evaluation dataset to serve as a benchmark for assessing the geospatial tool-use ability of LLMs, stored in **EvalData.json**.
## Tools Description
We provide detailed descriptions of the tools we collected. Details of the tool set (27 tools) are stored in **Tools.json**, and the external tools (5 tools) are stored in **ExternalTools.json**.
## License
GTChain and all our publicly available data are intended for research preview and non-commercial use only, subject to the model License of LLaMA2. Please contact us if you find any potential violations. If you have any questions, you can emaill us yuwh@cug.edu.cn.
