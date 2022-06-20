# **Generate images from an guardian article**

I'm exploring how to visuallise an article from an AI's lens. It could be also helpful to generate illustration for stories. I was planing to use DALL-E 2 or similar text2image model but there are challenges either it's not open to public or need to upgrade colab. So, I changed my design to an alternative flow.

In this notebook, I firstly followed few tutorials and modified a webscraper to grab content from an article on the Guardian. Then the content is send to GPT-3 to take keywords out. Lastly I am using VQGAN and CLIP to generate images and video.


**Reference:**


How to build a web scraper: 

https://hackernoon.com/how-to-build-a-web-scraper-with-python-step-by-step-guide-jxkp3yum


Open AI API Reference:


https://beta.openai.com/docs/api-reference/models


Request website content with proxy:

https://blog.csdn.net/a877415861/article/details/79468878


How to Easily Use AI to Generate AMAZING Images [VQGAN+CLIP]:


https://www.youtube.com/watch?v=8hnZmtqi-YE


Notebook of VQGAN+CLIP:


https://colab.research.google.com/github/justinjohn0306/VQGAN-CLIP/blob/main/VQGAN%2BCLIP(Updated).ipynb#scrollTo=VA1PHoJrRiK9
