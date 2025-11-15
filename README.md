# AI 

AI Journaling Prompt Generator
AI Agent to help college students generate personalized daily journaling prompts

🧠 SECTION 2: PROBLEM FRAMING
1.1. What problem does your AI Agent solve?
Many college students struggle to find meaningful topics for daily journaling, leading to less reflection and personal growth. This agent provides tailored prompts to inspire consistent journaling habits.

1.2. Why is this agent useful?
It offers personalized, engaging prompts that motivate students to reflect daily, enhancing self-awareness and emotional well-being without requiring them to brainstorm ideas themselves.

1.3. Who is the target user?
College students seeking to build a journaling habit, especially those interested in self-improvement, mental health, or creative expression.

1.4. What not to include?
Avoid complex psychological assessments, detailed coaching, or prompts that could be triggering or inappropriate. Focus solely on neutral, positive prompts.

🧱 SECTION 3: 4-LAYER PROMPT DESIGN
🔹 3.1 INPUT UNDERSTANDING
Prompt:
"Understand that the user wants a personalized journaling prompt based on their mood, interests, or recent experiences."

Purpose:
To interpret user requests and extract relevant context for generating tailored prompts.

Example Input + Output:
Input: "Give me a reflective prompt about feeling overwhelmed."
Output: "The user wants a reflective prompt related to feeling overwhelmed."

🔹 3.2 STATE TRACKER
Prompt:
"Remember the user’s preferences or recent moods mentioned in previous inputs to tailor future prompts."

How it helps:
It maintains a simple memory (via variables) of user mood, interests, or recurring themes, enabling more personalized interactions across sessions.

Simulation of memory:
Using variables like last_mood, interests, or topics stored in the system to inform prompt generation.

🔹 3.3 TASK PLANNER
Prompt:
"Break down the user’s request into specific steps: (1) identify user mood/interest, (2) select a relevant theme, (3) formulate a creative prompt, (4) deliver the prompt with a friendly tone."

Approach:
Uses branching logic based on detected user input, managing complexity by modular steps and conditional flows.

🔹 3.4 OUTPUT GENERATOR
Prompt:
"Format the final prompt with an encouraging tone, possibly adding a motivational phrase or example. Use markdown for clarity."
Example:
"Today, reflect on a time when you felt overwhelmed and what you learned from it. Remember, your feelings are valid and part of your growth."

Special behaviors:
Tone control (friendly, motivational), variation in prompts, clear formatting.

🔍 SECTION 4: CHATGPT EXPLORATION LOG
Attempt 1:
Prompt: Basic "Generate journaling prompts" — output too generic.
Changed: Added user context ("based on mood/interests") — more personalized prompts.
Attempt 2:
Prompt: Integrated memory simulation — improved relevance but limited variety.
Changed: Introduced tone modifiers for more engaging responses.
Attempt 3:
Prompt: Included examples and formatting instructions — output clearer and more inspiring.
Changed: Fine-tuned tone and structure for better user engagement.
🧪 SECTION 5: OUTPUT TESTS
Test 1:
Input: "I want a journaling prompt about career confusion"
Output:
"Write about a moment when you felt unsure about your career path. What did you learn from that experience, and how can it shape your future decisions?"
Test 2:
Input: "Give me something to think about"
Output:
"Consider a recent challenge you faced. What emotions did it evoke, and how did you handle it? Reflect on what this teaches you about yourself."
Test 3:
Input: "" (empty input)
Output:
"Would you like a prompt about a specific topic or mood? Let me know, and I'll craft one for you."
🔄 SECTION 6: REFLECTION
6.1. The hardest part was balancing personalization with scope—making prompts relevant without overcomplicating the system.
6.2. I enjoyed crafting multiple iterations to improve prompt relevance and tone.
6.3. Given more time, I’d add adaptive learning to refine prompts based on user feedback over time.
6.4. I learned that prompt modularity helps in managing complexity and improving output quality.
6.5. I felt stuck when trying to make prompts both specific and flexible; I handled it by layering incremental improvements.

🧠 SECTION 7: HACK VALUE (Optional)
I simulated multiple user moods and interests to test personalization. I also added simple memory variables to maintain context across turns, making interactions feel more cohesive.
