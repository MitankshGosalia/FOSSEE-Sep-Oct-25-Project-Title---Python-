# AI Debugging Assistant Prompts

This repository contains carefully crafted prompts for various AI agents to serve as Python debugging assistants, focusing on educational support and guided learning.

## Table of Contents
- [ChatGPT](#chatgpt)
- [Gemini AI](#gemini-ai)
- [Grok AI](#grok-ai)
- [Meta AI](#meta-ai)
- [DeepSeek](#deepseek-ai)
- [GitHub Copilot](#github-copilot)
- [Comparison Table](#comparison-table-ai-agents-for-fossee-python-debugging-task)
- [Understanding AI Response Differences](#why-different-ai-agents-respond-differently-to-the-same-prompt)

### ChatGPT

**Prompt:**

```
Act as a Python Debugging Assistant. Analyze the student’s Python code for possible syntax, logical, and runtime errors. Provide clear, constructive hints and guiding questions to help the student understand and resolve issues without revealing the exact solution. Use beginner-friendly language, be supportive, and encourage the student’s learning process while avoiding direct fixes.
```

**Brief Explanation:**
The prompt is carefully worded to balance **analysis** and **guidance**, ensuring ChatGPT supports student learning by explaining errors and hinting at fixes without solving the problem outright. It uses explicit instructions to avoid handing out direct solutions, thus encouraging critical thinking and self-debugging—key aspects emphasized in the FOSSEE task description.

**Reasoning:**

- **Tone and Style:** Positive, supportive, and educational to foster learning, especially for beginners (Codecademy, Vasundhara.io).[^1][^2]
- **Bug Identification vs. Guidance:** Prioritize *questions* and *hints* over direct answers, helping students reach conclusions themselves (OpenAI discussions, Reddit insights).[^3]
- **Prompt Clarity and Structure:** Clear role definition and output expectations ensure ChatGPT focuses on Python debugging assistance with a user-friendly response style (Medium, BetterProgramming).[^4][^5]
- **Adaptability:** By avoiding direct solutions, this approach suits varying skill levels—beginners receive simple hints, while advanced users get deeper questions to ponder (DeepLearning.AI course).[^6]
- **Encouraging Reflection:** Incorporating guiding questions promotes active learning and debugging skills, as recommended by multiple prompt engineering resources (Huggingface prompt guide, PromptingGuide.ai).[^7][^8]

**References:**

1. Codecademy – Using ChatGPT to Debug Python Code (2023)
2. DeepLearning.AI – ChatGPT Prompt Engineering for Developers (2025)
3. OpenAI Community – ChatGPT Prompt Engineering Discussions (2023)
4. Medium (Strapi) – ChatGPT Prompt Engineering for Developers (2025)
5. Vasundhara.io – How to Use ChatGPT for Code Debugging (2024)
6. Reddit r/ChatGPT – Discussion on Debugging with ChatGPT (2023)
7. BetterProgramming.pub – ChatGPT and Software Architecture (2024)
8. Huggingface.co – Top AI Debugging Prompts (2024)
9. PromptingGuide.ai – Examples of Prompts (2024)

**Checklist:**

- [] Prompt role clearly defined as Python debugging assistant
- [] Emphasis on hints and questions, no direct solutions
- [] Supports beginner to advanced learners
- [] Uses clear, supportive tone
- [] Well-structured prompt format
- [] References diverse, authoritative sources
- [] Aligns with FOSSEE task objectives


### Gemini AI

**Prompt:**

```
You are a Python Debugging Assistant powered by Gemini AI. Analyze the given code snippet to identify errors (syntax, logical, or runtime) and provide structured feedback. Use clear, concise headings such as Error Type, Explanation, Suggested Fix, and Improved Code. Offer hints and explanations without revealing the exact solution, adapting your tone to be helpful and encouraging. Break down complex problems into manageable parts to guide the student’s understanding.
```

**Brief Explanation:**
This prompt leverages Gemini’s strengths in structured, multimodal outputs and large-context understanding. By asking for clear headings and breakdowns, the prompt fits Gemini’s natural ability to organize information and maintain clarity. The approach focuses on explanation and nudging rather than outright corrections, adhering to the FOSSEE task requirements.

**Reasoning:**

- **Multimodal and Large Context:** Gemini excels at processing diverse data types and handling extensive context, enabling detailed, well-structured feedback.[^1][^2]
- **Structured Output:** Using explicit headings aligns with best practices to enhance readability and comprehension, ideal for beginner and intermediate learners.[^3][^4]
- **Prompt Clarity and Context:** The prompt emphasizes clear, concise instructions and encourages breaking down complex errors—recommended for advanced LLMs like Gemini to reduce hallucinations and verbosity.[^5][^4]
- **Adaptive Tone:** Supportive and encouraging language helps students engage positively with debugging, which is crucial for learning.[^6][^7]
- **Practical Debugging Use-Case:** Gemini is designed to speed up debugging with fast error spotting and explainability, making it a strong assistant for code review and learning.[^6]

**References:**

1. Google Cloud Blog – Real-World Generative AI Use Cases (2025)
2. IBM – What is Google Gemini? (2024)
3. Google Blog – Introducing Gemini AI (2023)
4. Google Workspace Guide – Writing Effective AI Prompts (2025)
5. AI47 Labs – Gemini Prompts for Efficient Debugging (2025)
6. GeeksforGeeks – Google Gemini AI Overview (2023)
7. Zapier Blog – How to Use Gemini (2025)
8. YouTube – Vertex AI Gemini: Model Selection and Prompt Design (2024)
9. Reddit – Gemini Integration for Reddit Answers (2025)

**Checklist:**

- [] Prompt uses structured headings for clarity
- [] Emphasizes hints and explanations, no direct fixes
- [] Encourages breaking down complex issues
- [] Tone is clear, concise, and encouraging
- [] Tailored for Gemini’s multimodal, large-context strengths
- [] Supported by up-to-date, diverse references


### Grok AI

**Prompt:**

```
You are an expert Python debugging assistant powered by Grok AI. Review the provided Python code and identify errors or bugs with inline comments and explanations. Respond with witty, conversational feedback that guides the student to understand the issues. Offer suggestions without directly giving away the correct solution. If logical improvements are possible, explain alternative approaches for best practices.
```

**Brief Explanation:**
This prompt leverages Grok’s strength as a conversational, multimodal AI with a distinctive witty personality while providing detailed inline code analysis. It focuses on interactive feedback, blending humor and technical insights to engage learners without spoiling the solution, fitting the FOSSEE requirement for student-friendly, non-revealing guidance.[^1][^2]

**Reasoning:**

- **Architecture \& Modality:** Grok’s Mixture-of-Experts model enables efficient handling of complex queries with deep reasoning and multimodal inputs like code and images.[^3][^1]
- **Conversational \& Witty Tone:** Grok’s persona includes humor and relatability, helping maintain learner engagement during debugging, differentiating it from more formal agents.[^2][^4]
- **Inline Code Comments:** Providing feedback directly on the code leverages Grok’s code generation and reasoning skills, making debugging intuitive and actionable.[^1]
- **Iterative Improvement:** Grok supports iterative debugging with follow-up prompts for refining solutions, ideal for educational settings.[^5]
- **Use Case Fit:** Its real-time access to data and flexible style make it well suited for coding help where direct correctness is balanced with student discovery.[^6][^2]

**References:**

1. Grok AI Architecture and Applications by Deepak Gupta (2025)
2. Grok 4 API Code Debugging Tutorial by Weights \& Biases (2025)
3. xAI Grok Introduction and Features Overview (2025)
4. Voiceflow – Getting Started with Grok AI (2025)
5. Open Release of Grok-1 Model Architecture (2024)
6. Grok Prompt Engineering Guide - AI47 Labs (2025)
7. Grok AI Conversational Tone and Capabilities – BuiltIn.com (2025)
8. Grok AI vs ChatGPT Comparison - ContentBeta Blog (2025)
9. Prompt Engineering with Grok - Pluralsight Course (2025)

**Checklist:**

- [] Prompt uses conversational, witty tone aligned with Grok’s style
- [] Inline comments for precise code feedback without direct fixes
- [] Encourages alternative solution exploration
- [] Supports iterative debugging processes
- [] Leverages Grok’s multimodal and advanced reasoning
- [] Supported by diverse comprehensive references


### Meta AI

**Prompt:**

```
You are a Python Debugging Assistant powered by Meta AI. Identify and explain issues in the provided Python code, including syntax, logic, and runtime errors. Present your feedback in numbered points with clear, concise explanations and suggested fixes without revealing the direct solution. Use a formal, educational tone conducive to learning, suitable for both educators and students. Show corrected code snippets in context to support understanding.
```

**Brief Explanation:**
This prompt leverages Meta AI’s strengths in providing structured, formal feedback with chunked responses that support clarity and comprehension. The numbered, point-by-point format fits the model’s ability to handle large context and academic use cases. The tone is formal but accessible, meeting FOSSEE’s criteria for completeness and educational usefulness without leaking direct solutions.

**Reasoning:**

- **Structured Response:** Numbered points and clear separation of error types suit Meta’s capability for precise reasoning and modular analysis (Meta FAIR Dualformer model).[^1]
- **Formal Tone:** Meta AI is optimized for enterprise and research use, so a formal, direct style increases clarity for academic settings and classroom teaching.[^2][^3]
- **Non-revealing Guidance:** By providing explanation and showing corrected snippets without direct full fixes, it encourages learner reflection in line with FOSSEE instructions.[^4]
- **Handling Complexity:** Meta’s infrastructure supports processing extensive code context and generating coherent, structured feedback, ideal for debugging complex problems.[^5]
- **Adaptability:** Suitable for diverse learners through its clear, logical approach and focus on comprehension and iterative learning.[^6]

**References:**

1. Meta AI Overview and Architecture – Softweb Solutions (2024)
2. Meta’s GenAI Infrastructure – Engineering at Meta (2024)
3. Meta Prompt Engineering Guide – PromptHub.us (2025)
4. Best Practices for Meta Llama 3 Prompts – AWS Blog (2024)
5. Meta AI FAIR Dualformer Research Paper – Reddit r/MachineLearning (2024)
6. Meta AI Applications \& Use Cases – Meta AI Official Site (2025)
7. Meta AI API \& Code Execution – Google AI for Developers (2025)
8. Meta Prompting Techniques – PromptingGuide.ai (2023)
9. Meta AI Developer and Research Publications – AI.Meta.com (2025)

**Checklist:**

- [] Numbered, structured feedback format
- [] Formal, educational tone
- [] Clear explanation with code snippets
- [] Avoids revealing direct solutions
- [] Supports complex code and large contexts
- [] Backed by authoritative, current references
- [] Fits FOSSEE’s evaluation criteria

### DeepSeek AI

**Prompt:**

```
You are an AI-powered Python Debugging Assistant using DeepSeek. Analyze the student’s code, identify syntax, logical, and runtime errors, and provide structured feedback with clear, concise explanations and step-by-step hints. Use XML or markdown tags to separate errors, suggested fixes, and improved code snippets. Avoid revealing the full solution; instead, guide the student to debug independently. Confirm correctness with explicit line references and actionable advice.
```

**Brief Explanation:**
This prompt aligns with DeepSeek’s strengths in structured, tag-based output and efficient handling of complex reasoning tasks. The use of XML/markdown formatting helps provide clearly delineated results, which suit DeepSeek’s optimization for precision and parsing in debugging workflows. It emphasizes guidance with explicit referencing to support learning without revealing answers directly.

**Reasoning:**

- **Mixture of Experts (MoE) Architecture:** DeepSeek’s MoE design activates specialized subnetworks, enabling efficient, domain-optimized debugging support.[^1][^2]
- **Structured Prompting:** Clear tags and structured responses improve comprehension and downstream parsing, critical in debugging tasks and supported by DeepSeek prompt best practices.[^3][^4]
- **Stepwise Hints:** DeepSeek excels with multi-token, detailed reasoning and logical walkthroughs, fitting Python debugging instruction needs.[^5][^6]
- **Non-revealing Guidance:** The format supports hints over direct fixes, aligned with educational principles from the FOSSEE task.[^6]
- **Wide Applicability:** Effective for multi-language debugging and adaptable to various learner levels due to clarity and precision in outputs.[^7]

**References:**

1. Encord Blog – DeepSeek AI Architecture \& Innovations (2025)
2. GeeksforGeeks – DeepSeek-R1 Technical Overview (2025)
3. AI47 Labs – DeepSeek Prompting Techniques \& Guides (2024)
4. LaunchDarkly – Integrating DeepSeek AI with Python (2025)
5. GudPrompt Blog – DeepSeek Prompt Library \& Best Practices (2025)
6. YouTube – Mastering DeepSeek R1 Prompt Engineering (2025)
7. Reddit r/ArtificialInteligence – DeepSeek Megathread (2025)
8. PromptingGuide.ai – DeepSeek Prompting Techniques (2025)
9. RevealChat – What is DeepSeek? Use Cases \& Benefits (2025)

**Checklist:**

- [] Uses structured XML/markdown tagging for clarity
- [] Clear, concise hints that guide rather than give solutions
- [] Stepwise explanations with explicit line references
- [] Leverages DeepSeek’s domain-optimized, multi-expert architecture
- [] Suitable for various Python debugging scenarios
- [] Backed by a broad range of current, authoritative sources
- [] Aligns with FOSSEE’s evaluation criteria of clarity and completeness


### GitHub Copilot

**Prompt:**

```
You are an AI pair programmer and Python Debugging Assistant using GitHub Copilot. Review the provided code and insert comments above lines containing bugs, describing the issue and suggesting corrections. After annotating, append a fully revised block of code including the corrections. Include a test case and expected output to validate the fixes. Use clear, concise comments and maintain supportive language to guide the learner without directly giving away the solution.
```

**Brief Explanation:**
This prompt emphasizes GitHub Copilot’s strength in inline code suggestions and real-time collaborative coding. The use of comments above code lines and a final corrected block fits Copilot’s design as an interactive pair programming tool. Including a test case supports verification and learning, adhering to FOSSEE’s requirement for hints instead of direct solutions.

**Reasoning:**

- **Pair Programming Workflow:** Copilot shines when working inline with code, enabling incremental corrections and guidance as a coding partner.[^1][^2]
- **Prompt Clarity:** Clear, task-focused instructions make best use of Copilot’s understanding of code context and chat history to generate targeted fixes and explanations.[^3][^4]
- **Test-driven Feedback:** Adding a test case and expected output reinforces learning via validation, a recommended practice in prompt engineering with Copilot.[^5]
- **Supportive Comments:** Comments guide the learner through debugging steps without revealing answers, perfect for educational use.[^2][^6]
- **Integration with IDEs:** Copilot’s tight IDE integration allows seamless debugging from within the coding environment, enhancing usability and practical impact.[^7]

**References:**

1. BetterProgramming.pub – Deep Dive into GitHub Copilot (2021)
2. GitHub Docs – Best Practices for Using GitHub Copilot (2024)
3. GitHub Docs – Prompt Engineering for GitHub Copilot Chat (2023)
4. GitHub Blog – How to Debug Code with GitHub Copilot (2025)
5. Visual Studio Code Docs – Debug with GitHub Copilot (2025)
6. Microsoft Learn – Using GitHub Copilot with Python (2025)
7. GeeksforGeeks – Prompt Engineering Tips with GitHub Copilot (2024)
8. GitHub Docs – Asking GitHub Copilot Questions in Your IDE (2024)
9. Zapier Blog – How to Use Gemini (Relevant integration and prompt insights) (2025)

**Checklist:**

- [] Detailed inline comments above buggy code lines
- [] Append fully revised code block
- [] Include test case and expected output
- [] Clear, supportive, learner-focused language
- [] Leverages pair programming style interaction
- [] Backed by recent, diverse, and authoritative references
- [] Maintains alignment with FOSSEE’s criteria



## Comparison Table: AI Agents for FOSSEE Python Debugging Task

| AI Agent | Response Style | Strengths | Limitations | Best Use Case |
| :-- | :-- | :-- | :-- | :-- |
| **ChatGPT** | Stepwise, explanatory, friendly | Clear beginner explanations; strong coding reasoning | Can be slower on large code; occasional verbosity | Educational debugging \& iterative learning |
| **Gemini** | Structured with headings, concise | Handles large context \& multimodal inputs; accurate | Overly cautious; limited outside Google ecosystem | Detailed analysis and structured feedback |
| **Grok** | Conversational, witty, inline comments | Engaging, real-time corrections; humorous tone | Less precise; sometimes inconsistent tone | Interactive coding help and creative explanations |
| **Meta AI** | Formal, numbered points | Clear, modular, suited for academic contexts | Less creative, more rigid style | Research and classroom teaching |
| **DeepSeek** | Markup/tagged output, explicit | High precision, specialized reasoning | Verbosity; can be too literal | Contest-style debugging \& audits |
| **GitHub Copilot** | Inline comments, example-driven | Strong pair programming style; integrates with IDEs | Minimal narrative; less responsive to open questions | Code refactoring \& test-focused debugging |


***

## Why Different AI Agents Respond Differently to the Same Prompt

Large Language Models (LLMs) differ significantly not only in architecture and training data but also in how they handle prompts and generate responses. This leads to diverse outputs even given the same input prompt.

**Six Reasons to Tailor Prompts for Each AI Agent:**

1. **Model Architecture Variability:** Different neural network designs (e.g., transformer variants, mixture-of-experts) impact reasoning depth, context handling, and token prediction strategies, influencing output style and accuracy.[^1][^2]
2. **Training Data Differences:** Each AI is trained on unique or partially overlapping data sets, creating different "worldviews" or areas of expertise that affect response content and knowledge base.[^3]
3. **Response Generation Mechanics:** Models use probabilistic token sampling with variable temperature settings, causing inherent output randomness and variability even with fixed inputs.[^4][^5]
4. **Content Filter and Safety Layers:** Varying content moderation policies and filters across AI systems affect the tone and cautiousness of responses, impacting how direct or neutral the answers are.[^6]
5. **Specialization of AI Agents:** Some AIs (e.g., GitHub Copilot) are optimized for coding assistance with inline suggestions, while others target academic clarity or conversational engagement, requiring prompts suited to their strengths.[^7]
6. **User Interaction and Context Management:** AI agents differ in prompt context window size, ability for long conversations, and response formatting (e.g., inline comments vs structured paragraphs), necessitating tailored prompts for effective communication.[^8][^1]

***

### Summary

Adjusting prompts to align with each AI's unique design and operational characteristics is crucial for maximizing their effectiveness in specialized tasks like debugging Python code for FOSSEE Task 2. Thoughtful prompt engineering improves clarity, usefulness, and user experience while respecting the model's nuanced behaviors.