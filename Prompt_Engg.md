<H1>What is Prompt Engineering ?</H1>

Prompt engineering is a discipline or manner of designing the inputs for LLM which guides the model to generate accurate,reliable and useful output.<br>
AI systems can read the long sentences the way human do.<br>
it requires text to be converted into small,structured pieces ->tokens -> later it is converted into numbers(vectors)<br><br>
In simply words prompt engineering is the art of asking the Right question in the right way.
<br>

<h4>What is Tokenization </h4>
Tokenization is the process of breaking down the sentence of text into smaller units calles tokens.<br>
AI reads Tokens not the words.<br>

<h4>Tokenization process :</h4>
word: Playing ->It will be broken in two tokens i)Play ii)ing  <br>
word: Transformation -> i)Trans ii) form iii)ation  <br>

<h4>Why it is important</h4>
AI get the prefixes and suffixes through tokenization by which it can get the meaning of another words. <br>

<h2>Context Window - Memory Limit of AI</h2>
<h4>Blackboard Analogy</h4>

Whenever we write a prompt and the AI gives an answer, it writes everything on a blackboard.<br>
When the blackboard gets full, to write something new, the AI has to erase the top (earlier) lines first.<br>

<h4>Definition</h4>

The maximum number of tokens an AI model can see or remember at one time is called the Context Window.

<h4>Effect of the Limit</h4>

If your model has a limit of 8,000 tokens and you provide a document of 10,000 tokens:
The AI will forget the first 2,000 tokens.

 


