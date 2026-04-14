<h1>Advance Prompt Engineering framework</h1>
<h3>1) ReAct Framework(Reason+Act)</h3>
Instead of AI just giving a direct answer, it works in a loop:

Thought(Reason) → Do(Action) → Observation(Result) → Repeat (if needed)→ Final Answer(after enough thinking+ acting)<br><br>
Use Case: Researching a market trend using AI with browsing capabilities (like ChatGPT with Search or Perplexity).

<h3>2)Tree of Thoughts (ToT)</h3>

Tree of Thoughts is like an advanced version of Chain of Thought.
In Chain of Thought, AI thinks in a single line.
In Tree of Thoughts, AI explores multiple paths (branches) like a tree.

<b>How it works:</b>

The AI generates 3–4 different ideas (thoughts) at the same time.
Then it evaluates them itself to decide which idea is best.

If a path seems wrong → it is discarded
If a path looks promising → it is explored further
<br>
Strategy A: Cheap and fast → continue<br>
Strategy B: Too expensive → discard

<h3>3)Directional Stimulus Prompting</h3>
 We don’t just give an instruction<br>
 We also give hints (keywords/directions) to guide the AI’s focus
 So instead of:

Do this task

We say:

Do this task, but focus on THESE aspects<br>

<b>How it works:</b>
We give a main instruction
Along with it, we provide keywords or directions
These help the AI focus only on specific parts

Think of it like telling someone:<br>
“Summarize this article, but focus only on money and future growth”

<h1>Iterative Prompt Development(The Improvement cycle)</h1>
It is a systematic approach for Prompt engineering<br>
<b>Draft:</b>Write the prompt.
<b>Test:</b>test the prompt on AI.
<b>Analyze:</b>Analyze the output.
<b>Refine</b>:Make changes in prompt for desired output.
<b>Repeat</b>:Repeat the cycle until you get the required output.









