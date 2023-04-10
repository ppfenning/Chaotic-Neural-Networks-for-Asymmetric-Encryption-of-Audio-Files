# Capstone Critique of Molly Brown

### What is the research question?

How accurately can one determine authorship of Facebook/Twitter post using existing text classification algorithms?

### What methods were [will be] used?

- Obtain posts from both Twitter and Facebook API/datasets
- Data will be a compilation of real and bot users.
- Test classification of data using:
  - Disjoint-Author Document Topic 
  - Support Vector Machine
  - RoBERTa

So I am a bit confused here. Are we attempting to classify bot vs. non-bot only? 
Or are we attempting to map which user authored the post? 
Is this better suited as a disinformation classifier?
Can "bots" never be reliable, what of automated posts/accounts?

### [What are the main findings and] how do they contribute to the field?

- Over-fitting is a legitimate concern when mapping to user data
- It is a challenge to reconcile the stylistic differences between Facebook and Twiter posts.
- All algorithms are strong in their own ways, but it may be difficult to combine FB and Twitter into a singular model.
- The largest contribution to this could be to have a "digital identity" of sorts. One could link multiple platforms to their likeness to ease account verification. 

### Does the abstract meet the 6 tips from our presentation?

N/A

### Any ethical issues to consider: data privacy, bias, and the potential impact of the research on society?

Disinformation is a huge issue in today's world. 
A reliable tool that can automate verification could be useful.
Whenever using large swaths of personal data we run into ethical concerns, how will you handle PII?