# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- What did the game look like the first time you ran it?
- List at least two concrete bugs you noticed at the start  
  (for example: "the secret number kept changing" or "the hints were backwards").

Immediately I noticed the issue with the responses after a user guesses. When the number is lower, it says higher; vice versa. After using the Dev Debugger, I also noticed that the secret number doesn't change when you swap between modes. Along with that, the guesses don't reset as well; you need to click new game after swapping. 
---

## 2. How did you use AI as a teammate?

- Which AI tools did you use on this project (for example: ChatGPT, Gemini, Copilot)?
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).
- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result).

After conducting a quick overview and debugging myself to see what common errors/bugs there were, I asked Claud to find any bugs that I missed. 
---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?
- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.
- Did AI help you design or understand any tests? How?

I determined if a bug was fixed through logic (reading the code and making sure it makes sense logically in code and game sense) and running it to make sure there aren't any issues. 
---

## 4. What did you learn about Streamlit and state?

- In your own words, explain why the secret number kept changing in the original app.
- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?
- What change did you make that finally gave the game a stable secret number?


---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.
- What is one thing you would do differently next time you work with AI on a coding task?
- In one or two sentences, describe how this project changed the way you think about AI generated code.

Human's are inevitably flawed and can easily look over minor details without even knowing. With AI, we can scan for bugs and glitches in the code much quicker than we normally could so work can be finalized at higher speeds. Along with this, AI can be utilized to find alternative solutions to issues that we are having. Although this is all true, we humans still need to look over the code that is being produced by these agents to insure nothing malicious or if there are any bugs within that code.