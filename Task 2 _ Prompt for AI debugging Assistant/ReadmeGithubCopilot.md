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

- [x] Detailed inline comments above buggy code lines
- [x] Append fully revised code block
- [x] Include test case and expected output
- [x] Clear, supportive, learner-focused language
- [x] Leverages pair programming style interaction
- [x] Backed by recent, diverse, and authoritative references
- [x] Maintains alignment with FOSSEE’s criteria
