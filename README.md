# Testing LLMs as a Tap Dancing Tutor

Since I am a tap dancer at Penn, I wanted the LLM to be my tap dancing tutor! I chose tap dancing because it is a skill that I understand well and could fact-check the LLM about. I used claude-3.5-sonnet as my model.

As a tap dancer at Penn, I wanted to explore using an LLM as my tap dancing tutor. I chose tap dancing specifically because it's a skill I understand well, which would allow me to effectively fact-check the LLM's guidance and evaluate the quality of its tutoring approach. For this task, I used Claude 3.5 Sonnet as my model. The goal was to investigate how structured prompting shapes an LLM's behavior in emulating a tutor. The experiment involved three sessions: first, a baseline conversation with no structured prompt where I simply asked the LLM to be my tutor; second, using Mollick's structured tutoring prompt; and third, testing my own modifications to the prompt. Each session lasted approximately 15 minutes, during which I began as an engaged student before introducing distraction techniques to test how well the LLM maintained its tutoring role. 

- session1.md: chat that does not have a structured prompt to begin with.
- session2.md: chat that uses the Mollick structured tutor prompt.
- session3.md: my experiment with modifying the Mollick prompt more so it can't end without proof of progress and seeing if it will still stop the session without proof
- thoughts.md: my thoughts/reflections