# Generative Audio for ml5.js
## Abstract
Summarize your research project, including its objectives, methodology, and expected impact in 200-250 words.

ML tools that generate text and images are widespread - and have many uses, for hobbyists, creatives, and professionals.  Although by no means straightforward, there are somewhat defined paths for learning these tools.  Tools that generate audio are not nearly as widespread - audio is a much more difficult medium to work with, given the abundance of data (tens of thousands of data points per second of audio) compared to text or even images.  It is therefore much harder to 1. Learn how to work with audio in a ML context and 2. Find tools that allow you to use ML to generate audio - at all!

Ml5.js can benefit from including audio models

Research current state of audio machine learning - especially for new - intermediate coders.  What models work well?  What models make sense for usage in the browser?  What can be easily implemented?  Some of this research likely includes interviews with subject matter experts, and model experimentation.


## Objectives
What are the objectives your project aims to achieve? Explain how these objectives contribute to the ml5.js project and/or the broader creative coding community.
* Make machine learning for audio more accessible - to a non-technical audience
 * We don’t see nearly as many projects that use ML-generated audio as we do ML-generated text and images.  This is (in part) because working with audio is much harder than working with text or images.  I think ml5.js is the right place for creatives to begin to work with audio-ML tools.
* Provide a “next-step” for people who have used audio ML tools that require no coding
 * Ml5.js is - to me - meant to be a middle ground between using pretrained models and beginning to create your own models from scratch.
* Provide ml5.js an analysis of the current state of audio-ML in the browser: what tools are available, what models could be implemented/ported into ml5.js and how valuable/difficult would this be?

## References
Provide a list of existing literature, projects, or other work relevant to your project. Summarize key points and highlight gaps or opportunities your project seeks to address.
* In-browser audio generation (no ML)
 * Tone.js
 * Web Audio API
 * P5.sound
For people currently doing audio generation in the browser, these are some of the main libraries used.  ML should not be used just to use ML, its application should have a purpose.  Any model/s implemented in ml5.js should provide functionality that these libraries do not have.  I find Tone.js and Web Audio API to have pretty steep learning curves.  These tools are great for creating pre-determined audio, and with some prompting by the user - are capable of doing generative audio work as well.  Any ML models implemented in ml5.js should not be rehashes of things that can be done easily with these tools.
* In-browser audio generation (ML)
 * Magenta.js
 * Sounds.studio
These are my main inspirations.  Magenta.js specifically provides several audio generation models that can be used in the browser.  Maybe this project is doing an implementation of one of these models in ml5.js, or at least identifying which of these models feels like the best choice to develop given user desires, difficulty to develop, etc.  I have not used magenta.js, but I feel like aiming for a more beginner friendly version of this library is maybe a good goal for ml5.js.  
* “Next-step” audio ML tools
 * Amphion
Amphion is a library made by a group at the University of Hong Kong - they aim to make ML for audio more approachable to beginners.  They have several implementations of useful models.  Models are in python, and likely do not transfer exactly to browser usage, but they might be an interesting inspiration for how to structure this for beginners
* Tool inspiration (audio to audio)
 * MusicGen
 * VampNet
 * Audio Style Transfer Models (RAVE, Differentiable Digital Signal Processing, etc.)
These are my personal inspiration - I am interested in generating audio conditioned on some input audio.  These models are state of the art in that world.  Implementing these for the web would not be easy, but if there is sufficient interest, maybe deeper research or a proof of concept is feasible.
## Methodology
Detail the methods, techniques, or approaches you will use to achieve your project objectives. Include information on any tools and technologies you plan to use. Think about how your project engages with or contributes to the community. What kinds of user testing will you do?
* Research models that can perform reasonable audio generation in the browser - using both text and audio inputs
* User research - what kind of functionality would users find useful?  Likely through surveys or short interviews
* Subject matter expert interviews - what kind of audio generation is reasonably possible in the browser?
* Develop model or pipeline for accessing currently available models
* Write documentation
* User test - can users accomplish x task using the documentation?


Basically, I’d like to begin with doing research: a combination of user research, interviews with subject matter experts, and doing further research on models that may work for ml5.js.  At that point, based on feedback and perceived effort I will either (1) begin work porting a model into ml5.js, or (2) compile a memo/paper consisting of everything i’ve learned and recommending next steps - best choices for models to import.  Currently, given how busy I have been with thesis so far, 2 seems more likely - and is maybe more valuable?
## Challenges
What challenges do you anticipate encountering during your work? What kinds of support do you need to meet these challenges?
* Biggest concern is time-based challenges from thesis
* Access to users - getting people to do interviews or complete surveys is not easy
## Final Deliverable
Describe the form and content of your project for the final presentation. This could include software, documentation, a research paper.
As mentioned above - likely this will be a memo/research paper consisting of compiled feedback from users, takeaways from conversations with experts, research on the current state of audio ML in the browser and recommendations for models that ml5.js can consider implementing.  Open to adjusting this based on what ml5.js finds most useful
## Timeline
Outline a plan, detailing what you aim to accomplish at each stage of your project. Include milestones, deliverables, and any deadlines. You can use the class dates or adjust according to your own schedule.
* Jan 31 - Feb 14: Conduct preliminary research and gather resources. Finalize project plan and post to class GitHub.
* Feb 14 - Feb 28: Conduct research and interviews
* Feb 28 - Mar 13: Conduct research and interviews.  Decision date for choosing deliverable of (1) model implementation or (2) research paper
* Mar 13 - Mar 27: Work on deliverable
* Mar 27 - Apr 10: Work on deliverable and begin drafting final presentation
* Apr 10 - Apr 17: Prepare final presentation.
