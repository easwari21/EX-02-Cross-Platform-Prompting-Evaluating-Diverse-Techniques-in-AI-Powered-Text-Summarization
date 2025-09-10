# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini,Perplexity) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy
Coherence
Simplicity
Speed
User experience

## Algorithm

### 1. Article Selection

Choose a technical article: “The Basics of Blockchain Technology”.

### 2.Prompting Strategies

1.Zero-shot: Directly ask the model to summarize without examples.

2.Few-shot: Provide 2–3 example summaries of similar technical texts before asking for the summary.

3.Chain-of-Thought (CoT): Instruct the model to break down the content logically step by step before generating the final summary.

4.Role-based: Instruct the model to act in a role (e.g., “a university professor summarizing for freshmen students”).

### 3.Platform Selection

1.ChatGPT (OpenAI)
2.Gemini (Google)
3.Perplexity AI

### 4.Execution

1.Apply each prompting strategy on each platform with the same input article.

2.Record the generated summary.

3.Note the time taken to generate the summary.

### 5.Evaluation Criteria

1.Accuracy – Captures main ideas without distortion.

2.Coherence – Logical flow and structure.

3.Simplicity – Accessibility for undergraduate students.

4.Speed – Response time of the platform.

5.User Experience (UX) – Ease of use, readability, and ability to copy/share.

### 6.Scoring & Analysis

1.Assign scores from 1 (poor) to 5 (excellent) for each criterion.

2.Tabulate results for comparison.

3.Identify the best-performing strategy-platform combination.

## Result
| Platform   | Prompt Type      | Accuracy | Coherence | Simplicity | Speed | UX | **Total (/25)** |
| ---------- | ---------------- | -------- | --------- | ---------- | ----- | -- | --------------- |
| ChatGPT    | Zero-shot        | 4        | 4         | 4          | 5     | 5  | 22              |
| ChatGPT    | Few-shot         | 5        | 5         | 5          | 4     | 5  | **24**          |
| ChatGPT    | Chain-of-Thought | 5        | 5         | 4          | 3     | 5  | 22              |
| ChatGPT    | Role-based       | 5        | 5         | 5          | 4     | 5  | **24**          |
| Gemini     | Zero-shot        | 3        | 3         | 3          | 5     | 4  | 18              |
| Gemini     | Few-shot         | 4        | 4         | 4          | 4     | 4  | 20              |
| Gemini     | Role-based       | 4        | 4         | 5          | 4     | 4  | 21              |
| Perplexity | Zero-shot        | 4        | 4         | 4          | 5     | 4  | 21              |
| Perplexity | Few-shot         | 4        | 4         | 5          | 4     | 4  | 21              |
| Perplexity | Role-based       | 5        | 5         | 5          | 4     | 4  | **23**          |


## Conclusion

The best-performing combinations were:

1.ChatGPT + Few-shot prompting → Total score: 24/25

2.ChatGPT + Role-based prompting → Total score: 24/25

3.Perplexity + Role-based prompting → Total score: 23/25


ChatGPT performed the strongest overall, especially with few-shot and role-based prompts, delivering highly accurate and student-friendly summaries.
Gemini was faster but weaker in coherence and accuracy, making it better suited for quick but less detailed outputs.
Perplexity provided balanced results, particularly strong in role-based prompting, making it effective for clear, structured explanations.
