# LLM Comparison — Product Teardown: Youtube’s recommendation feed.

## Models Used
| # | LLM Name     | Mode (Fast/Standard/Thinking) | Response Time (approx)   |
|---|--------------|-------------------------------|--------------------------|
| 1 |Google Gemini |         (Thinking)            |Not Specified (A few sec) |
| 2 |     GLM - 5  |         (Standard)            | Not Specified (A few sec)|
| 3 |Chat GPT      |         (Thinking)            |      9 sec               |

## Layer-by-Layer Comparison

### Layer 1: Data Foundation
| Criteria           | Gemini | GLM - 5|Chat GPT| Best? |
|--------------------|--------|--------|--------|-------|
| Specificity (1-5)  |    4   |   4.5  |    4   |GLM - 5|
| Named real tech?   |    Y   |   Y    |    Y   |GPT    |
| Identified a real engineering challenge? | Y | Y | Y |GLM - 5|
| Notes:             |brief but lacks some useful information | brief, precise and informative| elaborate and informative|       |

### Layer 2: Statistics & Analysis
| Criteria           | Gemini |GLM - 5 |Chat GPT| Best? |
|--------------------|--------|--------|--------|-------|
| Specificity (1-5)  |  4.5   |   4    |   3.5  |  Gemini  |
| Named real tech?   | Y    | Y    | Y   |  chat GPT    |
| Identified a real engineering challenge? | N | Y | N |GLM-5  |
| Notes:             | easily understood|  easily understood| Keywords that need reasearch to be understood|       |

### Layer 3: Machine Learning Models
| Criteria           | Gemini |GLM - 5 |Chat GPT| Best? |
|--------------------|--------|--------|--------|-------|
| Specificity (1-5)  |   4    | 4.5    |  4.5   | chatgpt |
| Named real tech?   | Y    | Y    | Y    | GLM-5      |
| Named model family?| Y    | Y    | Y    | GLM-5      |
| Identified a real engineering challenge? | Y/N | Y/N | Y/N | |
| Notes:             | too brief| informative and easy to understand|too many deeply technical related terms used, needs research to understand|       |

### Layer 4: LLM / Generative AI
| Criteria           | Gemini |GLM - 5 |Chat GPT| Best? |
|--------------------|--------|--------|--------|-------|
| Specificity (1-5)  |    3   |  4.5   |  3.5   | GLM-5|
| Honest if not applicable? | Y | Y | Y |   Gemini   |
| Notes:             |        |        |        |       |

### Layer 5: Deployment & Infrastructure
| Criteria           | Gemini |GLM - 5 |Chat GPT| Best? |
|--------------------|--------|--------|--------|-------|
| Specificity (1-5)  |   3.5  |    4   |  4.5   | Chat-GPT|
| Named real tech?   | Y    | Y    | Y    |   Chat-GPT    |
| Notes:             |        |        |        |       |

### Layer 6: System Design & Scale
| Criteria           | Gemini |GLM - 5 |Chat GPT| Best? |
|--------------------|--------|--------|--------|-------|
| Specificity (1-5)  |   3.5   | 4       |   4     | GLM-5      |
| Named real tech?   | Y    | Y    | Y    | chatgpt      |
| Notes:             |        |        |        |       |

## Overall Verdict

| Dimension                          | Winner (LLM #) | Why? (1 sentence)        |
|------------------------------------|-----------------|--------------------------|
| Most technically specific overall  |  GLM-5          | included specific and easily understandable key terms|
| Best at naming real technologies   | Chat-GPT        | elaborate, deep dives into technilogies, required research to understand|
| Least hallucination / made-up info |  GLM-5          | Provides answers that flow in sequence  and doesn't lose track|
| Best at "hardest problem" insight  |  GLM-5          |easily comprehendible infromation, related more to real world |
| Best structured output             | GLM-5           |Includes most of the important information and structures words.|
| Fastest useful response            |  GLM-5          | Provides a quickly understandable and informative workings of the scenario.|

## Key Observation
> One thing I noticed about how different LLMs handle the same prompt:
> Gemini - Too brief, leaves a lot of important information.
> GLM - 5 - uses human friendly terms and structures them in a way that human mind doesn't lose track.
> ChatGPT - Give too much information and each term requires research separately.___ 

(write 2-3 sentences)
