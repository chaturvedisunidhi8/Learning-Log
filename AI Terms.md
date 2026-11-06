<H1>AI Terms</H1>    
<h3>Guardrails</h3>        
In Generative AI, guardrails are rules, checks, and controls placed around an AI system to make sure it behaves safely, correctly, and within the application's requirements.<br> 
Think of them as “boundaries for an AI model.”<br   
<h4>Types of guardrails</h4>  
1. Input guardrails<br>
They check the user's input before it reaches the LLM.<br>
2. Output guardrails<br>
They check the LLM's response before giving it to the user.<br>



 
<h3>Harness in AI</h3> 
An AI harness is the framework that connects an AI model's intelligence to the tools, resources, and processes it needs to perform real-world tasks effectively
<h3>Jailbreak</h3>
A Jailbreak in AI is an attempt to trick an AI model into ignoring its safety rules, restrictions, or instructions so that it<br>produces a response it would normally refuse.
Basically,<br>
A jailbreak is an attempt to bypass an AI's restrictions


CDMs(Constraint Decoding Model)
It is Introduced by ScaleDown ,  It has 3 specialist and each specialist has one specific task and these specialist generates output in a fixed format<br>
1st Specialist: Classify based on labels e.g spam and not spam and also provide reason<br>
2nd Specialist: Extract Information<br>
3rd Specialist :Summarize content 

<h3>LLM vs NCM</h3>

Problem with LLm : LLM follows Autoregression Generation ,It is a process in which a Large Language Model (LLM)<br> generates text one token at a time, where each newly generated token depends on the previously generated tokens.

The model must predict the next token, add it to the existing sequence, and then predict the following token.<br> This process continues until the complete response is generated.

Major problems of autoregressive generation:
1. Sequential processing: Tokens are generated one after another, making generation slow.<br>
2. Latency: The model must repeatedly perform inference before producing the next token.<br>
3. Error propagation: An incorrect earlier prediction can influence subsequent predictions.<br>
4. Computational overhead: Generating long responses requires repeated model execution.<br>
5. Limited parallelism: Future tokens cannot normally be generated independently because they depend on previous tokens.<br>

<H4>How NCM Address this Problem</H4>
A Next Context Model (NCM) is an AI model that aims to overcome the limitations of traditional autoregressive generation by predicting the next context in the form of discrete codes (compact representations of information) rather than generating individual tokens one by one. <br>These discrete codes represent larger units of information, potentially enabling faster and more efficient generation while preserving contextual relationships.

<b>LLM</b>: Predicts the next token (word or part of a word).<br>
<b>NCM</b>: Predicts the next discrete code representing a larger unit of context.

<h3>Frontier Model</h3>
<h3>Frugal AI</h3>


