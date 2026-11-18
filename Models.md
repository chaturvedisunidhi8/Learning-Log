<h3>LLM Models</h3>          
1)Gemini<br>    
2)GroK<br>    
3)Llama,Codelama<br>   
4)Mistral<br> 
5)GPT<br>  
6)MiniLM<br>
7)Deepseek ,jonus<br>
8)Gemma<br>
9)Qwen<br>
10)MiniMax<br>
11)Opus<br>
12)Haiku<br> 
13)Sonnet<br>
14)Nova<br> 
15)Phi and MAI<br> 
16)GLM <br>
17)Kimi K2/K3<br>
20)Fable and Mythos<br> 
19)laguna XS 
20)Nemotron (Nvidia)
21)Granite (IBM)

GloVe(Global Vectors for Word Representation)<br>
It is technique used in NLP to convert words into numerical vectors (embeddings) that capture their meanings.<br>
Before models like BERT and GPT became popular, GloVe was one of the most widely used methods for representing words.<br>
<br>
OCR(Optical Character recognition)<br>
It convert text inside Image,scanned Documents or PDF into editable and searchable texts 

Model Context Protocol(MCP):Open standard created by Anthropic that as a universal connector between claude code and external<br> tools,services and data sources .
It basically connect AI models to various Data sources and tools and feed context to the LLM.<br>
Act as USB e-port for AI applications.  

<h3>Some Concepts of Transformer</h3>
- Attention is a **communication mechanism**. Can be seen as nodes in a directed graph looking at each other and aggregating information<br> with a weighted sum from all nodes that point to them, with data-dependent weights.<br>
- There is no notion of space. Attention simply acts over a set of vectors. This is why we need to positionally encode tokens.<br>
- Each example across batch dimension is of course processed completely independently and never "talk" to each other.<br>
- In an "encoder" attention block just delete the single line that does masking with `tril`, allowing all tokens to communicate.This block here is called a "decoder" attention block because it has triangular masking, and is usually used in autoregressive settings, like language modeling.
- "self-attention" just means that the keys and values are produced from the same source as queries. In "cross-attention", the queries<br> still get produced from x, but the keys and values come from some other, external source (e.g. an encoder module)<br>
- "Scaled" attention additional divides `wei` by 1/sqrt(head_size). This makes it so when input Q,K are unit variance, wei will be unit<br> variance too and Softmax will stay diffuse and not saturate too much. Illustration below

<h3>Collibri</h3>
 
