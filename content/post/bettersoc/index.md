---
title: A Better Society
summary: What does a better society mean?
tags:
- Random Thoughts
date: "2019-06-13"

image:
  focal_point: Center
---
One of the major challenges I face while doing my research is how to drive it towards building a better society.
Although I understand the concept of a *better society* may be different from one culture to the other, I try to make things simpler by believing that any society gets better whenever **all** of its members experience more **freedom** to enjoy their **rights**. 

Among the untold manners technology can be used to breach people's rights, five setbacks in the way we are doing informatics get my attention.
Devices and programs usually suffer from (1) lack of **safety**, (2) nonobservance of **data integrity**, (3) lack of **privacy**, (4) nonobservance of **diversity**, and (5) lack of **accountability**.
Not unintentionally, the [projects](/#projects) I've been contributing to in the past few years tackle one or more of these issues.


## Safety
{{< figure src="safety.jpg" link="https://commons.wikimedia.org/wiki/File:Interest.jpg"  width="300px">}}

From the many ways safety can be harmed by technology, the improper dissemination of sensitive content (such as pornography or violence), to inadequate audiences (such as kids or unwary spectators), gained my attention while I was developing my PhD, under the supervision of prof. [Anderson Rocha](https://www.ic.unicamp.br/~rocha/index.html) (who generously proposed the topic).

With the popularity and pervasiveness of online video streams, sensitive scenes depicting [suicide](https://www.washingtonpost.com/news/the-intersect/wp/2017/01/15/a-12-year-old-girl-live-streamed-her-suicide-it-took-two-weeks-for-facebook-to-take-the-video-down/?utm_term=.ea8124e4a0e9), [murder](https://www.cnn.com/videos/us/2016/06/17/man-shot-killed-while-live-streaming-orig-vstan-dlewis.cnn), and even [rape](https://www.nytimes.com/2016/04/19/us/periscope-rape-case-columbus-ohio-video-livestreaming.html) have been broadcasted on the Internet, raising questions about the safety of these services.
Aware of this situation, [Samsung](https://www.samsung.com/br/) has funded us to focus on the development of solutions to detect sensitive video.
Rather than aiming at denouncing or morally condemning the lawful consumers of certain types of sensitive content, our intent has always been to support the implementation of filtering and warning features that would make player systems safer (especially in the case of child spectators).

I've had the chance to tackle the lack of safety in video streaming systems through the [SMA](/project/sma) project.


## Data Integrity
{{< figure src="trust.jpg" width="300px">}}

In the era of misinformation and *fake news*, there is a symptomatic undermining of trust not only in textual but also in visual information.
People are conscious of the existence of image editing software (e.g., *Photoshop*), with which even unskilled users can easily fabricate and manipulate pictures.
Although many of these manipulations have benign purposes (no, there is nothing wrong with *your memes*), some contents are generated with malicious intents, such as general public deception and propaganda.

The lack of available solutions to assess the integrity of images and videos allows adversarial manipulated data to have a negative impact on the way people relate to each other on the Internet.
They don't know what to trust anymore.
In addition, fraudulent images represent a challenge even for the [scientific community](https://www.nature.com/articles/s41419-018-0430-3).
Aware of this scenario, [DARPA](https://www.darpa.mil/program/media-forensics) has been funding us, at [CVRL](https://cvrl.nd.edu/), to conduct research on the development of tools to verify the integrity of digital images.

I'm having the chance to tackle the nonobservance of data integrity in visual media systems through the [MediFor](/project/medifor) and [Sci-Int](/project/sciint) projects.


## Privacy and Diversity
{{< figure src="privacy.gif" width="300px">}}

With the advent of deep learning and the necessity for large datasets, *visual data collection* has become an important step of Computer Vision and Machine Learning research.
Due to the popularity of image and video capture devices (such as digital cameras, smartphones, dash cams, etc.), large datasets can now be quickly generated.
Nevertheless, a major question that stands out in such a process is how to protect the privacy of people who are eventually being recorded.
Imagine, for example, a dash cam that is collecting road data for a self-driving car project.
In a major city, plenty of people will certainly be captured in the footages, and it is very unlikely that one will be able to obtain image rights for each individual.

Interested in such issue, we, at [CVRL](https://cvrl.nd.edu/), investigate the generation of realistic synthetic faces, whose identities do not belong to a real existing person, hence avoiding privacy breaches.
The idea is to de-identify the recorded individuals, by replacing their faces with synthetic assets.

{{< figure src="diversity.gif" link="https://www.youtube.com/watch?v=t4DT3tQqgRM" width="300px">}}

In addition, collected data may be biased, due to a lack of diversity in the captured individuals.
Consider, for instance, training video footages collected in China.
It is very [unlikely](https://www.nationalgeographic.com/travel/destinations/asia/china/black-tourist-china/) that black people will be represented in such a dataset.

Limitations of this nature comprise what I call *nonobservance of diversity* and are the potential cause of many [technological failures](http://www.cnn.com/2009/TECH/12/22/hp.webcams/index.html) in the presence of underrepresented groups.
Unfortunately, glitches like these may go [beyond the technological aspects](https://www.forbes.com/sites/mzhang/2015/07/01/google-photos-tags-two-african-americans-as-gorillas-through-facial-recognition-software/#41ebc8e8713d) and prejudice the rights of equality in face of diversity.
To cope with this problem, similar to the privacy protection strategy, synthetic identities can be used to diversify the recorded individuals by performing face replacement, providing controlled variation of not only ethnicity but also of age and of gender.

I'm having the chance to tackle the lack of privacy and nonobservance of diversity in image and video datasets through the [SREFV](/project/srefv) project.


## Accountability
{{< figure src="acc.gif" width="300px">}}

People have the right to understand in details the decisions made about them by algorithms belonging to either government or industry.
This is fundamental to give them the possibility of questioning determinations and defending against resolutions that might be the outcome of incorrect, rigged, or even [bogus](https://www.youtube.com/watch?v=rga2-d1oi30) computations.
In this context, *accountability* becomes a relevant concept, since it comprises the property of an automated decision system to be fair, transparent, and explainable to human beings.
As a consequence, the more accountable a system is, the more audit power it gives to people.

Within the field of Biometrics, traditional iris recognition solutions are well known for constituting very reliable methods of identity verification.
Nevertheless, since they are not human-friendly enough to convince people who do not possess image processing expertise, their usage before a jury in courts of law is usually avoided.
Aware of this limitation, Prof. [Adam Czajka](https://engineering.nd.edu/profiles/aczajka) has started at [CVRL](https://cvrl.nd.edu/) the investigation of human-intelligible iris matching strategies.

I'm having the chance to tackle the lack of accountability in iris recognition algorithms through the [TSHEPII](/project/tshepii) project.

## Keep pushing
{{< figure src="conclusion.jpg" link="http://matt.might.net/articles/phd-school-in-pictures/" width="600px">}}

Although the aforementioned efforts may seem minuscule in face of the size of the challenge of building a better society, I try to calm myself down by making a parallel to the [explanation](http://matt.might.net/articles/phd-school-in-pictures/) of Prof. Matt Might on how the human knowledge increases with the progress of scientific research.
As he advises, *I keep pushing*.
