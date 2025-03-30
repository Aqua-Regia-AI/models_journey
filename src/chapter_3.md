# Maral : Mann-E's way to LLMs

Image generation space is cool. There is a lot of cultural potential in image generation space and there is no doubt of that but when we look deep in how people kept their languages alive, there are multiple phases which make you scratch your head for a moment. 

I am not really a linguistics expert but I read enough about my own language. The phases of saving Persian language from multiple big replacements are really cool and I think it is a really good lesson on how a nation can save their national treasures. But what were these steps? 

## How my ancestors saved Persian lanugage

First when Persian speaking kings or warriors could find a chance to take over the Iranian land (I mean mostly the modern day Iran and not the ancient Persia) before Arabic speaking caliphates or after their collapses, they immediately made Persian their national language and people followed them as well. This was a good step but not enough. Then scholars started collecting the epics and stories of pre-Islamic era and one of the most famous ones is _Epic of The Kings_ or _Shahnameh_ by _Ferdowsi_. 

Ferdowsi is the person known for saving Persian language although this is not a hundred percent true. He tried and he was successful but people after him continued this movement. For centuries, poetry was a way of keeping this beautiful language alive but when Qajar dynasty took over Iran, the space changed a lot. Our people were introduced to newspapers and magazines and novels (mostly because of the connections of Qajars with France and UK.) and this was the new way of saving the language. 

Years passed and we introduced to the internet. Internet content creation was really a thing and it also helped a lot. People wrote blogs, made channels on YouTube, made forums and group chats and this was a new phase. But the most important phase of saving a language is still remained. This is _Artificial Intelligence_. 

## Why AI matters?

Nowadays the most linguistic entity we have in our lives is AI. We can't deny this fact. AI helps us write code, write essays, even write our applications for a job or educational position. This is all besides how AI almost replaced classic meaning of a search engine for us. The problem is although most of the models are good at speaking English, they usually are not good at other languages specially languages like Persian or Arabic. 

So one way of keeping our languages alive is to add them to AI. Building an AI which understands the language you speak can help keeping that language alive. And now you may ask _ChatGPT is fluent in Persian as well, so why did you make a new one?_ which I'm going to explain. 

## Birth of Maral

I was testing multiple bases to find which one is better in understanding the Persian language. First option was LLaMA 2. It was horrible. The next option was GPT Neo-X which was good but it didn't have a perfect conversational structure in its output. What should I do then? The answer is finding a newer model which can be a little risky to fine tune but the outcome might be better than the past two. This made me check Mistral 7B. 

Mistral wasn't bad at understanding Persian sentences but since it didn't have any good Persian data source, most of the text it was generating was pure nonsense. This part of the story basically begged for a good dataset. You may recall the famous _alpaca_ dataset right? Someone did a great job at translating the whole dataset to Persian. I just used the same dataset on Mistral 7B and the results were better than expected!

Although it had made some serious factual mistakes (like calling Elon Musk an actor from 60's) but wasn't a grammatical mess like the other models. When I found this works like this, I published it on [HuggingFace](https://hf.co/MaralGPT) without any hesitation. I also posted on twitter and different social media about the model and it grabbed a lot of attention from people, enthusiasts and even local companies who were trying to make a Persian language model.

## Restoring an old project...

A while after this LLaMA 3 released which had a good understanding and generation of Persian language. This was the time to give it a shot. So I gathered a team of enthusiasts to work on a completely new project which becomes somehow the founding steps of _Aqua Regia_. In the next chapter, we're going in details of that project which was also the restoration of an old project of mine. 