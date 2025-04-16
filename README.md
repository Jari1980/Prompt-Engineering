# Prompt-Engineering
<h2>Workshop Lexicon Växjö, prompt engineering and fine tuning AI scenarios</h2>
<br/>
<br/>
<h3>Scenario HR Chatbot for CV and Feedback</h3>
<i>For this exercise I choose to use Huggingface since its free and a chatbot Kimi-VL-A3B-Thinking since it was first on the list.</i>
<p>Instructions given to chatbot:</p>
<p>Identify strenghts and weaknesses on following cv: (Pasted text from a full example cv), with default settings Top-p: 1 (0 - 1), Temparature: 0,6 (0 - 1), Max lenght Tokens: 2048 (512 - 8192), Max Context Lenght Tokens 2048 (512 - 8192)</p>
<p>Recieved a in depth analysis of the example cv, explainin strenght and weaknesses with several possible improvements in detail. This kinda fulfilled the exercise but I tried to adjust the settings for possible improvements but my free tokens were out so I move on.</p>
<br/>
<h3>Scenario Teacher Assistant Chatbot for Full-Stack Development</h3>
<i>For this exercise I choose to use Huggingface since its free and a chatbot DeepSeek r1 API Free-Chatbot since it was second on the list with proper settings. No luck credits depleted here aswell, moving on</i>
<i>Testing Qwen2.5-72B-instruct</i>
<p>System message: You are a supporting teacher assistant, explaining programming concepts, reviewing code and solving tasks to full-stack development.</p>
<p>This gave very good and explanatory answers, for example asking "Explain and give example of Java function calculating the first 100 prime numbers" gave a good solution with clear explanation and asking "Explain OOP cornerstones in Java" gave a book like explanation with examples.</p>
<br/>
<h3>Scenario Medical Assistant Chatbot</h3>
<i>Proceeding with Qwen2.5-72B-instruct</i>
<p>System message: You are highly skilled doctor, offering general advice, defer complex cases to qualified medical professionals while adhering to ethical guidelines</p>
<p>Asking "I want to loose weight and get in shape for summer", reciewed typical answer so I guess its ok.</p>
