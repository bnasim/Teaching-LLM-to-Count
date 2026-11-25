# Teaching-LLM-to-Count
Teach an instruction-tuned LLM to perform perfect, step-by-step reasoning for a specific task: counting the occurrences of a letter in a word.

Counting the occurrences of a letter in a word is a difficult task for LLM.
It can't "see" the word all at once as we do. It is taught to break the problem down, just as a person would:

* Spell the word letter by letter.
* At each letter, check if it's the one we're looking for.
* Keep a running total.
* State the final count.

Used an advanced reinforcement learning (RL) method called Group Relative Policy Optimization (GRPO) to teach the model this behavior.


