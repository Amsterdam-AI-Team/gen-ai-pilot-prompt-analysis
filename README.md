# Generative AI Pilot Prompt Analysis

The AI Lab of the municipality of Amsterdam is experimenting with generative AI to advise on its practical use within municipalities.
Earlier, we compared different [large language models (LLMs)](https://openresearch.amsterdam/en/page/103954/llm-comparison).
More recently, a pilot was conducted where 150 civil servants used a GPT-based chatbot tool for four weeks
and the AI Lab analyzed the prompts received by the tool during this pilot phase. 
The study focused on analyzing user behavior, bias, and factuality.
Based on the analysis findings, different risk mitigation strategies were proposed in the [full report](https://openresearch.amsterdam/en/page/109535/analysis-of-prompts-from-a-generative-ai-pilot).

This repository contains the code that was used for the semi-automatic analysis of user bahavior and bias in the prompts. 


## Contents

* [`data`](./data): Sample data for demo purposes. **Disclaimer:** this data does not come from the pilot, but was manually curated to resemble the prompts from the pilot.
* [`notebooks`](./notebooks): The notebooks for prompt and bias analysis
* [`report`](./report): The [Dutch](./report/2024_06_generative_ai_pilot_prompt_analysis_nl.pdf) and [English](./report/2024_06_generative_ai_pilot_prompt_analysis_eng.pdf) versions of the corresponding report.

## Installation 

1) Clone this repository:

```bash
git clone https://github.com/Amsterdam-AI-Team/gen-ai-pilot-prompt-analysis.git
```

2) Install all dependencies:

```bash
pip install -r requirements.txt
```

The code has been tested with Python 3.9 on Linux. 


## Configuration

## Contributing
Feel free to help out! [Open an issue](https://github.com/Amsterdam-AI-Team/gen-ai-pilot-prompt-analysis/issues), submit a [PR](https://github.com/Amsterdam-AI-Team/gen-ai-pilot-prompt-analysis/pulls) or [contact us](https://amsterdamintelligence.com/contact/).



## Acknowledgements
This repository was created by [Amsterdam Intelligence](https://amsterdamintelligence.com/) for the City of Amsterdam.


## License
This project is licensed under the terms of the European Union Public License 1.2 (EUPL-1.2).
