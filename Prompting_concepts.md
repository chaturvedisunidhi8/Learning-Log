<h1> Core Prompting Technique</h1>
<h3>1)Zero-Shot Technique :The Direct Order</h3>
In this prompting technique, The user simply provide an instruction without any example.<br>
Here AI use the knowledge of pre-trained data to predict the outcome of unseen data.

Practical use case:Sentimental Analysis

<h3>2)Few-Shot Technique:The Pattern Maker</h3>
Sometimes Zero-Shot prompting fails especially when you want your output in specific format that time we use  Few- shot prompting 
In this promting technique, we provide 2-3 examples to AI so that it can understand the pattern.

<h4>Practical Use Case(Formatting Data):</h4>Suppose you want feedback of customers in JSON format <br>
<h4>Example:</h4>
Prompt:"The deleivery of Pizza was late."-> {"sentiment":"negative","label":0},"Pizza was good."-> {"sentiment":"positive","label":0}<br>
Output:{"sentiment":neutral","label":0.5}
<h3>3)Chain of thoughts(CoT):"The logical Thinker "</h3>
It is the most important technique to solve the complex problem.<br>
here, when AI is intructed to solve problem step by step that time AI makes logic to solve the problem instead of directly jumping on the output.<br>
It helps in avoiding the hallucination.
<b>Why it is important</b> :Complex Math, Coding logic or making strategy 
Example of AI hallucination :If you ask provide me the picture or Seahorse again & again ,AI will confuse what picture to provide  

<h3>4)Instruction Prompting :The Framework</h3>
In this technique ,We Not just give the Tasks to AI but also set boundaries.<br>
Here we provide 3 things:<br>
1)Persona(Role): e.g -Act as senior Python developer<br>
2)Constraint(Limit): e.g- don't use external libraries keep code under 20 lines.<br>
3)Specific Instruction: e.g -Explain the code like i am 5 year old.<br>



