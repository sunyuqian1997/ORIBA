# Academic Project Page Template
This is an academic paper project page template.


Example project pages built using this template are:
- https://www.vision.huji.ac.il/deepsim/
- https://www.vision.huji.ac.il/3d_ads/
- https://www.vision.huji.ac.il/ssrl_ad/
- https://www.vision.huji.ac.il/conffusion/


## Start using the template
To start using the template click on `Use this Template`.

The template uses html for controlling the content and css for controlling the style. 
To edit the websites contents edit the `index.html` file. It contains different HTML "building blocks", use whichever ones you need and comment out the rest.  

**IMPORTANT!** Make sure to replace the `favicon.ico` under `static/images/` with one of your own, otherwise your favicon is going to be a dreambooth image of me.

## Components
- Teaser video
- Images Carousel
- Youtube embedding
- Video Carousel
- PDF Poster
- Bibtex citation

## Tips:
- The `index.html` file contains comments instructing you what to replace, you should follow these comments.
- The `meta` tags in the `index.html` file are used to provide metadata about your paper 
(e.g. helping search engine index the website, showing a preview image when sharing the website, etc.)
- The resolution of images and videos can usually be around 1920-2048, there rarely a need for better resolution that take longer to load. 
- All the images and videos you use should be compressed to allow for fast loading of the website (and thus better indexing by search engines). For images, you can use [TinyPNG](https://tinypng.com), for videos you can need to find the tradeoff between size and quality.
- When using large video files (larger than 10MB), it's better to use youtube for hosting the video as serving the video from the website can take time.
- Using a tracker can help you analyze the traffic and see where users came from. [statcounter](https://statcounter.com) is a free, easy to use tracker that takes under 5 minutes to set up. 
- This project page can also be made into a github pages website.
- Replace the favicon to one of your choosing (the default one is of the Hebrew University). 
- Suggestions, improvements and comments are welcome, simply open an issue or contact me. You can find my contact information at [https://pages.cs.huji.ac.il/eliahu-horwitz/](https://pages.cs.huji.ac.il/eliahu-horwitz/)

## Acknowledgments
Parts of this project page were adopted from the [Nerfies](https://nerfies.github.io/) page.

## Website License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.


# Summary

## ORIBA: Transforming Artists' Original Characters into Chatbots
## Introduction
ORIBA is an innovative AI chatbot that transforms artists' original characters (OCs) into interactive agents. This research explores the intersection of illustration art and artificial intelligence (AI), focusing on how illustrators engage with AI agents that embody their OCs. By examining the impact of AI on the creative process and the boundaries of authorship, we aim to enhance human-AI interactions in creative fields, with potential applications extending beyond illustration to interactive storytelling and more.

{Insert Image: ORIBA Workflow}

## Key Features
Autonomous Agents for Creators: ORIBA leverages advancements in AI technology, such as AutoGPT, BabyAGI, and CAMEL, to transform artists' OCs into autonomous agents. These agents can observe, reflect, and make decisions, enhancing the believability of virtual characters and reshaping artists' storytelling and illustration approaches.

### ORIBA Workflow: The ORIBA workflow consists of the following steps:

Observation: The Agent forms an observation based on the most recent dialogue records (5 entries), summarizing what has happened.
Reflection: The Agent reflects, associating information from its own profile.
Impression: The Agent summarizes its impression of the current speaker.
Behavior: The Agent describes its current physical or facial behavior.
Action: The Agent chooses an action. By default, we provide three actions: "Normal reply", "Relate reply (relate to memories)", and "Silence".
Reply: After generating the ORIBA trajectory, the character's final reply is produced.
This approach allows artists to not only receive responses from their OCs but also observe how they think and behave. Through in-depth and informative conversations, we aim to support and facilitate the creative process of authors.

{image inno}

Authors
Yuqian Sun: Royal College of Art, London, United Kingdom. Email: yuqiansun@network.rca.ac.uk
Xingyu Li: Georgia Institute of Technology, Atlanta, United States. Email: xingyu@gatech.edu
Ze Gao: Hong Kong University of Science and Technology, Hong Kong SAR, China. Email: zgaoap@connect.ust.hk


### Conclusion
Our study provides valuable insights into effective human-machine collaboration in creative tasks. We found that illustrators adapted their working styles to accommodate the AI agent's capabilities, resulting in more efficient collaboration. However, maintaining the illustrator's agency and creative input is crucial in the collaboration process. Our platform enables authors to interact with their original characters via AI-powered dialogue systems, providing a unique testing ground for expanding creativity.

{image esca}

### Future Works
Based on the limitations of our system, there are three main directions for our further study:

Improve AI's associative capabilities: Enhance the AI's reasoning and associative abilities to align more with the character's details in the profile.

Enhance AI's personalized responses: Improve the AI's language tone and emotional responses to make the AI agents more characterized.

Improve AI's memories: Enhance the AI's ability to recall past interactions to ensure consistency in long-term conversations.

{Insert Image: Future Works}