# The story of Mann-E

This part of the book is dedicated to the mother company of _Aqua Regia_ which is called [Mann-E](https://mann-e.com). The story and start point of the whole new business has been started from here so it was worth having a whole chapter dedicated. 

Also, in order to give up some information on my culture, Iranian men are famous for talking a lot about their good memories. You can count this chapter as one of the most Iranian parts of this whole document. Anyway, let's get started!

## A friend on Twitter

_Finding like minded individuals_ is the only thing I am good at. On most of the social media platforms and specially twitter (don't really care if it's called X now) I always have a good base of like minded individuals who are really good at their jobs. 

This superpower helped me a lot. And it is the beginning of my serious entrepreneurship journey! You may ask how? Simple. One day I saw one of my friends posts weird abstract paintings on his page. And later, he said that he made those using _artificial intelligence_ and it made me more curious and excited about the whole topic. I DMed him and asked about the procedure and he was nice and generous enough to give me links to tools he was using. 

After that, I had the most important thing. __The keywords__. I did my own research as well and I found OpenAI's `CLIP` which is still used in order to describe the images in a lot of tools (like Automatic1111 WebUI or ComfyUI.). But I was in search of a generative tool which puts me in absolute control. Then I found something called `VQGAN+CLIP` which was like magic. I just wrote a few lines of description and it was like it is giving me my internal weirdness in form of an abstract painting!

I have started posting these artworks on Twitter and some of my friends got curious about that. It becomes some sort of tradition for our gatherings. I was like a magician or a showman who can turn people's dreams into a painting in the blink of an eye. This was the start of the business!

## First phase of monetization

It was summer of 2022 and one of my friends - who is a marketer - joined me to monetize the project. We decided to make it like this: "People give us their prompts, we generate for them, print it on wooden frames and send it to them". It was a good business model at first glance but had a lot of flaws. First, when we didn't have any GPU's and we relied on _free tier google colab_ for generation of the images, we couldn't give our customers mulitple options to choose from. 

And by now you probably are generating a dozen images or logos before choosing one for your purpose right? Imagine how worse it could be three years ago. The next flaw was the logistics. We had to get wooden frames and store them. We had to talk to print houses and we had to find the efficient way to handle the orders and sending them to customers efficiently. 

So this was failed. But there was another thing happening at the same time!

## Stable Diffusion

Stable Diffusion was basically the first model advertised as _The Open Source Midjourney Killer_ and honestly in August and June of 2022, it was really a better option compared to midjourney for generating images. But Stable Diffusion alone wasn't the magic. 

A short time passed and people started tuning the model on different datasets. So you could have different Stable Diffusion models for different purposes (my most favorite one back then was _analog diffusion_) and then __DreamBooth__ came. DreamBooth was really a game changer. It made tuning on a free tier colab really easy and I can't describe how happy I was with that project. I tried too many times to make different styles. 

But there was one more thing! Stable Diffusion introduced _model merging_ as well. You could download multiple checkpoints and merge them in order to get a bigger and better model. So I decided to have my own trained checkpoints merged. Then I started looking for other checkpoints as well and merge them into my big model. My intention was to make the model as perfect as possible and keep in mind, LoRA's were not a thing yet. 

I just did this. And I had a name for my project. I called it _Open Journey_. 

## The Open Journey Event

One day (I don't know it was December 2022 or January 2023) I woke up and saw my personal blog and LinkedIn are exploded. Lots of views, comments and messages. I found out someone posted my Open Journey ([Link](https://news.ycombinator.com/item?id=34522311)) to Hacker News (and probably it was mistaken with what PromptHero made). When I realized this happened, I told myself this is the time it must be a service. But I still had a problem which was the name!

Open Journey was cool but taken by PromptHero. What should I do then? I remembered that when we wanted to be _an AI driven print on demand service_ we just had _Mani_ in mind which is the name of a Persian spiritual leader who happened to be a painter as well. 

Since Dall-E was a thing and it was a combination of Dali and Wall-E, I took a page from OpenAI's book and called my model _Mann-E_. 

## Early adapters

When I started coding the platform, I decided to gather a list of emails of the possible early adapters. First, I thought it will be around 20-25 people maximum and I didn't really aim high in terms of infrastructure. The whole project was running on a single _RTX 2080 TI_ GPU which I could rent with a nice price from a local infrastructure provider here. When I posted about the project on social media, I bombarded with emails. In course of 72 hours, I got around 200 emails and it was amazing!

When I reached the 200 point, I told people I won't accept any new early adapters and you will be able to sign up on platform when we launch publicly. Then I emailed these people one by one and sent them instructions on how they can access the platform and I made a group on Telegram to gather the feedback from my community. The feedback helped me make the product much much better in a few weeks. 

## Public Launch 🚀

Finally Mann-E was launched on April 14th 2023 (since April 14th is the birthday of _Mani The Prophet_ as well) and since then we had a lot of progress which is explained on Mann-E's blogs and web pages. 