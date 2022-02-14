**Daniel Whitenack:** Welcome to another episode of Practical AI. This is Daniel Whitenack. I am a data scientist with SIL International, and I'm joined as always by my co-host, Chris Benson, who is a tech strategist at Lockheed Martin. How are you doing, Chris?

**Chris Benson:** I'm doing very well today, Daniel. How are you doing?

**Daniel Whitenack:** Doing wonderful, because today is another episode in our series of spotlight podcast episodes AI in Africa. This is a joint initiative between the International Development Research Center in Canada, Practical AI and The Changelog, and a GIZ FAIR Forward project, all of which are involved in one way or another with the Open For Good Alliance. As part of these episodes, it's been really wonderful to have with us a guest co-host, Joyce Nabende, from the Makerere AI Lab at Makerere University. Welcome, Joyce.

**Joyce Nabende:** Thank you, Daniel. Hi, Chris. Thank you.

**Chris Benson:** Hey there.

**Joyce Nabende:** It's just another opportunity for us to discuss on this podcast, and I'm excited to be here.

**Daniel Whitenack:** Yes, it's always wonderful to have you with us, Joyce. Why don't you -- I'll sort of pass it over to you to introduce what we'll be talking about today.

**Joyce Nabende:** Right, thanks, Daniel. So over the past podcasts we've been trying to look at different studies on Practical AI, particularly on the African continent. And we are very excited for this episode, because we are going to focus on AI, but looking at community building in Africa, and especially looking at the very exciting field of natural language processing.

For this podcast today we are very happy to have Kathleen Siminyu with us. Kathleen is currently a Kiswahili machine learning fellow with Mozilla. But before Mozilla, there's a lot of work that Kathleen has been involved in. Kathleen, you're very welcome to this podcast.

**Kathleen Siminyu:** \[00:04:21.28\] Thank you for having me. Thank you very much.

**Joyce Nabende:** Alright, so I think we're ready to dive in. Over to you, Kathleen - give us an introduction about NLP for African languages, what work have you done in NLP, how has it been like for the last couple of years in the space of NLP for African languages.

**Kathleen Siminyu:** Okay, thanks again, Joyce. So I will start with a bit of an introduction to myself and how I got into NLP. My backend is in maths and computer science, and with that I went into data science. I worked briefly in industry for a company in the telecommunications space that's headquartered in Nairobi, Kenya. One of our products was SMS. And through working at this company I came to realize that support for African languages when it came to NLP and just tools or digital tools (if we could say so) was pretty lacking in comparison to, say, your English. And this got me pretty interested in NLP, and I wanted to build particularly resources for African languages.

So yeah, this is where my interest began, and then I ventured into academic research at this point. My next job was with IDRC, or rather AI4D. I was a regional coordinator of AI4D for a couple of years, and this work involved mobilizing funding for communities. IDRC has funding which is going into AI research in Africa, and I helped a lot with that in terms of identifying communities that could and make use of this funding.

So I'll back-track a bit and say that during my role in industry, I did a lot of community work. I began a lot of community building, first with the Nairobi Women in Machine Learning and Data Science. This was sort of my first foray in the field, as I was a data scientist that worked in the industry. And then along with transitioning into academic research, I encountered Masakhane. They were doing exactly what I wanted to do in terms of focusing on resources for African languages, so my organizing also transitioned into that. And in the middle, I attended several Deep Learning Indabas. The Indaba is a movement to trends in Africa machine learning. One of the events we have is an annual summer school. I attended one, the first one in South Africa, in \[unintelligible 00:07:01.01\] after which we got to talking and they realized that there was an ML/AI community in Nairobi, courtesy of the meetup I was organizing... And so we organized a second one together in preparation for the third one, which we then came to host in Nairobi in 2019.

So I've spoken a lot, but let me see -- I'll cap it by saying that I have worked a lot with ML and AI communities in Africa, and that brought me to the intersection of my interests in NLP, and the existence of Masakhane, with our focus on African languages. So here we are - it's probably where I spend most of my organizing time at the moment. I am very excited by the fact that we have a wealth of diversity from the African continent in terms of people who are working on languages, and it's languages that they care about. So a wealth of diversity in terms of African languages included.

\[00:08:05.21\] I'll plug in the fact that as recently as last week we finally had Masakhane registered as an entity, so we are officially the Masakhane Research Foundation. Up till this point we've been really just organizing as a group of people, and that's been great. But yeah, I guess 2022 is going to be the beginning of us starting to see how we can formally organize beyond running on volunteer capacity. What it looks like when we organize \[unintelligible 00:08:33.29\] some of our planning. I will stop there... I kind of forgot what the question was, so I'll throw it back to you guys.

**Daniel Whitenack:** That's so wonderful. I really appreciate all that context, Kathleen. I wonder for those that may be thinking of those out here that might be listening to this podcast, that have never ever heard of Masakhane and the things that they're doing - could you just kind of give a picture of who's involved in Masakhane, how do they interact, and what are the sorts of activities that they're doing?

**Kathleen Siminyu:** Okay. So Masakhane was founded in 2019, and this actually took place at the Deep Learning Indaba that was hosted in Nairobi, Kenya. It was founded by Jade Abott and Laura Martinus. Basically, they did a paper for machine translation involving a bunch of South African languages, and created benchmarks. And part of the work done in this paper, they came to present at the Deep Learning Indaba, with the idea that if they create a notebook which is very easily replicable, then people can take it upon themselves to train similar models for their languages, therefore likely creating first benchmarks... Because very little research exists for African languages.

That is how it began, with a focus on machine translation. The initial work that they did was based on the JW300 dataset. JW is Jehova's Witnesses, and they are an organization that through their work evangelizing in Africa for many years have translated the Bible to many local languages in Africa. So the notebook leveraging this dataset made it super-easy for literally anyone to start up a notebook, put in the language code for the language you would like to work with, and in an hour or two have a benchmark trained. And it gained a lot of momentum in that way. I like to think that even though many of these languages have not been the point of focus in research in the past, or in terms of product development for markets that can pay for products - they haven't been a focus from that perspective, but this gained a lot of momentum because of the setting. Because the Deep Learning Indaba is bringing loads of young people from across the African continent, who given the fact that we've had two previous Indabas, have basic skills.

So some effort in capacity building had been done, and it was sort of a sweet spot in terms of many of us have attended previous Deep Learning Indabas, and we have the basic skills, and we now have a desire to specialize in something... And here comes Jade and Laura, and they have a notebook, and they're telling us "Hey, this is how you can start in machine translation."

So it gained a lot of traction... Personally, I've trained models for Kenyan languages, and I think that's how many people rationalize, in terms of "What languages do I care about? What do languages do the community adjacent speak?" and then went on to do that. If you could find a dataset for your language, then you went ahead and trained a machine translation model.

We wrote a really great paper. Two, I think. One I'd like to highlight is a participatory research \[unintelligible 00:11:54.28\] in African languages. This one in particular because it describes the ecosystem for machine translation to be successful \[unintelligible 00:12:08.10\] in an African context.

\[00:12:12.18\] So one problem is access to data, and we talk about the fact that typically, content creators create data. But In an African context, these content creators may not have access to keyboards, or they may not have access to digital dictionaries, which hinders the development of data to start with. So there's a whole ecosystem description, and I'll leave it at that for now. But then we've seen great success, first in machine translation, with being able to do very multilingual and inclusive work. Then, progressing from there, we've realized that individuals who were participating and contributing to Masakhane were not only interested in machine translation, but as a task in NLP as well. So at this point, we sort of took a step back and generalized and now have membership or participation from people building in NER, in speech, and basically just a wide scope of tasks.

**Chris Benson:** I've got a quick question for you... I was interested in the dataset that you mentioned, the JW dataset being a Bible translation... When you look at a lot of different Bible translations, and kind of the language may not be completely what you typically would talk in today - did that present any kind of challenge, or was that generalized enough to where that didn't affect it, or anything? I was just curious about that being the basis, and what challenges that might present that were unique to the dataset.

**Kathleen Siminyu:** That's a super-interesting question... We encountered a phenomenon which -- I don't know if we called it, or it is known as the biblification of systems. One example I remember is -- actually, I don't remember what word, but in machine translation systems a certain word kept on being changed to 'canon'. Because 'canon' shows up many times in the Bible, but \[unintelligible 00:14:08.00\] 'canon' often in conversation.

**Chris Benson:** Right.

**Kathleen Siminyu:** So it has been a challenge to rely only on Bible data, and to answer your question it has not generalized well... Although, actually interestingly, after a year or two of working with the JW300 dataset, the organization actually pulled it from the internet. So it was scraped from the website, and the organization \[unintelligible 00:14:36.01\] that they were not aware of this dataset existing, and had not given permission for it... I mean, we've been trying to ask them for many months to see if they would make it open anyway, because it has inspired a lot of our research, and we're still waiting to see how that turns out... But then -- yeah, just to bring in the fact that access to data is a huge problem, and in many cases we face IT and copyright issues, even with data that is accessible.

So at the moment a lot of activities unfortunately have to start from a point of dataset creation, which I wish was not the case, but we also have found that it's an easy way to start including and up-skilling individuals... Because someone can start out on our project today, labeling data or creating data or evaluating a model, but then progressively pick up a lot more valuable skills and grow those skills. It's a blessing and a curse, but mostly a curse, because as NLP researchers, I wish we had the luxury of just accessing data for whatever \[unintelligible 00:15:41.15\] we wanted to work on.

**Break:** \[00:15:48.05\]

**Daniel Whitenack:** So Kathleen, I'm actually in the Masakhane Slack group and I just took a quick look at the involvement. I see in the Masakhane Slack group that there's - at least at the time I'm looking, there's 1,304 people in the Slack group... Which is pretty amazing that this community has grown in the ways that it has. I'm wondering if you have any -- you know, looking back on how the community was formed, and the activities you did, and how you welcome people, and those things, did you have any insights into why you think it grew, has grown the way that it has? And maybe looking forward, characteristics of the -- now that it's an entity and a foundation, characteristics of the community that you would like to ensure that they are characteristics of the community moving forward. Any thoughts?

**Kathleen Siminyu:** Yeah... So in terms of it growing, I'd say it was unprecedented, even for me. I will attribute it, first of all, to Jade's never-ending energy, I swear. Masakhane would not be what it is without Jade. I sometimes even struggle with just keeping up with all the conversations \[unintelligible 00:19:23.24\] and on the chat. It can be very overwhelming.

I think one of the reasons why it has grown, again, is just the fact that these languages are very underrepresented in digital platforms. But that is not reflective of the communities that use these languages. They say there's 7,000 languages on Earth, and maybe 2,000 languages in Africa. And many of those are living with thriving language communities that use them every day. They are just not used on digital platforms, and unfortunately, because of social linguistic factors, they're not used in formal spaces. At least in Kenya I know for a fact that parents are more likely to encourage their children to become better at English than their mother tongue... Because with English you can walk into any office and have a conversation and potentially get a job, versus your mother tongue, which is only useful at home or in whatever local context you find yourself.

\[00:20:23.15\] But that doesn't take away the fact that these languages are used, and at least from a sentimental point of wanting them to be preserved and captured on digital platforms, I think that's one huge reason why Masakhane has been so relatable to students and budding researchers across the continent.

I'll also say we have a lot of room for absolute beginners. Again, it's really easy for someone to work \[unintelligible 00:20:48.10\] Young people have loads of energy, and many will come and they'll say "Hey, I want to do something." And you know what - they can add to literally every single project, the fact that they're multilingual. So if we have an NER project and you walk in today and you say "Hey, I want to do something, and I speak Kiswahili in addition to English", then we can say "Hey look, there's this project where you can go and here's a Kiswahili text, and you can start labeling." And that's a way to start involving someone.

And they'll be interested in "Okay, what else can I do? What is this person doing? What is that person doing?" So I think just the fact that literally anybody who is multilingual can participate... And then we've been progressively working towards pathways for capacity building, so we have several groups that now run every 3-4 months. There's one that's particularly for beginner NLP... So any beginner who's involved with something in the community can also plug into that and start gaining more skills. Last week I was on the call and Julia offered to do one for machine translation.

And I'll say -- let that be a segue in to another factor, because we've gained quite some recognition globally, and the wider NLP community has also been super-supportive. So in terms of more experienced researchers wanting to know how they can be of use, and then proceeding to actually support us, right? So Julia has a Ph.D. She works at Google Translate and she shows up probably for 90% of Masakhane activities. If you ever want to debug -- I remember my experiences of training those initial models for Kenyan languages, she was literally always available on Slack. So I'll also shout-out to the fact that we've received a lot of support, a lot of mentorship support, and that's continuing to happen, and I hope it continues to happen for an extremely long time.

So the second part of the question, now that we're already have the entity and are growing somewhat exponentially, characteristics that I would like to see... First I think is a very distributed nature of leadership. Masakhane is like a storm; it's not a coordinated storm, it's just something that started happening and now it's got a life of its own. I love the fact that it's not reliant on any one person; so there's never a day where person X is sick and "Okay, now we can't hold the meeting because person X is supposed to chair it." That's never happened, because literally everyone is empowered to walk in and chair the meeting. We have a template, it's recorded, and everybody else can catch up.

We see that a lot also with the leadership in projects. So we've never sat down and said "Hey, we want to make NER a focus", but somebody in our community did. And they not only ideated, but they went ahead to organize regular meetings, and recruit people, and come and give updates at our weekly meeting... And that turned into a paper that we've accepted to EMNLP.

So distributed leadership - I would like to see this continue. Something we are a little worried about is the fact that having an entity -- well, it's a great thing, first of all, but having an entity means that we can receive funding. And we have been able to receive funding in the past through organizations that we have collaborated with... But having our own registered entity presents an opportunity to fund our research.

\[00:24:27.09\] So far we've mostly run on volunteer efforts, and the results have been great. So our one concern is that now when there's funding, a decision has to be made about what gets funded, what doesn't get funded, and we're worried about how that scales. Will it stifle the distributed leadership, especially on projects, or will it \[unintelligible 00:24:48.05\] forward? So I'd like to see us maintain that, despite funding -- I'd hate us to turn into an organization where the characteristics change because now money is available.

Something else I'd like to see us grow into is just further supporting pathways for individuals who are interested in productizing their work. Again, I'll go back to the fact that we have many young people who this may be their first interaction with any AI topics, or their first interaction with NLP... And we pretty much have a great pathway for them to advanced academic careers, because they're taking part in projects, which means they're writing papers, some of these papers are getting accepted at leading conferences, they're being mentored by leading researchers in the field... Many have gone on to get accepted into masters and Ph.D. programs which are amazing, internship opportunities... Basically, there's a really great pathway for people who want advanced research careers, but I'd like to see us build a similar pathway that is just as strong for individuals who want to productize and build companies. So that's something I'm hoping we can grow into.

And then one of my absolute favorite things about Masakhane is that we have a lot of female leadership. As a woman in tech, this is something I look at. As someone who has organized communities for women, this is something that's close to my heart. And I absolutely love the fact that we have pretty good female representation. I attribute it to the fact that this is a movement that was started by women, and I think it's very powerful signaling.

I'll tell you, whenever I have been in a position to be accepted in a company that I wanted to join, I'll probably go to their website and see if there's women on the team. And if there's none, I start to ask myself, "Do I want to be the first one?" But if there is one, then that's one person I can write to and say "Hey, can we have a chat about what working for company X is like?"

So I think it's a very powerful signal that it was started by women, and I love it that there is a little sisterhood, or perhaps a not so little sisterhood that is part of Masakhane, and I would love for that to continue to be the case.

**Daniel Whitenack:** Joyce, I'm curious if as a researcher in a university setting working on related problems to what the Masakhane community is doing, how has this sort of groundswell of community building in Masakhane influenced your research team, and maybe the things you're able to do, and the way you're able to engage? And then maybe you have a follow-up question for Kathleen with regard to some of the things on your mind as you think about your research group and engaging in the community building.

**Joyce Nabende:** Yeah, thanks. Just listening to Kathleen is really very enlightening...

**Daniel Whitenack:** Super-inspiring.

**Joyce Nabende:** Yeah. \[unintelligible 00:27:49.23\] and the roots of Masakhane that I never knew about. So that's very interesting. And I think for us how it's benefitted the lab is - unlike Masakhane, that is wide and does many things because it's a large community, we setted out in the NLP space building out in speech, and now in machine translation, like she mentioned, for the language that we care about, which is Luganda, the main language in Uganda.

\[00:28:15.00\] And Masakhane has really come in to support the researchers in the lab. As you said, if there are people who need help, maybe they're running their models and they are stuck... I've seen many of the people in my research lab go to Masakhane, put in a query, and get responses. And this has enabled them to move much faster with their model development... Unlike if it was just a closed community for us, or unlike if you went and wrote an email to one of the researchers that maybe developed a model, or did something... But here it's on Slack, it's within that community, and they get faster responses.

Or maybe you find a situation where someone has encountered the same issue, maybe with the models... It's easier for them to even respond. And I like that it's open. They can just put in a question there and then you get an answer. So that sort of community-building is something that's very critical, that the lab is also learning to adopt and leverage as well.

But also listening to Kathleen speak right from the beginning, I think Kathleen you said community, community building... Community is very important to you, and I know that with the new role that you have with Mozilla that there's also a lot of community building involved in there. So can you maybe tell us more about that, the current work that you're doing around community building with Mozilla? And Kiswahili in particular, your language that you're passionate about.

**Kathleen Siminyu:** Yeah. Okay, so my current role is machine learning fellow at Mozilla, and I'm working particularly on Common Voice, and particularly in Kiswahili. So I'm supporting work to build a Kiswahili dataset on Common Voice... And this is starting literally from the collection of sentences. But I should step back and say that it's starting from community building, again, like you highlight. So we want Kiswahili speakers to care about this work; we are working to communicate to them that the existence of this dataset is something that is of benefit to them, because it's intended to be a digital public good, and we're working to build ties with organizations that are already working in Kiswahili.

So I realize that we have the tech capacity, but then we're working into a space where people have been working for years to build language communities, and I'd like for us to be sensitive to that, and we'd like to be sensitive to that. So reaching out to the language boards, the universities that have linguistic literature departments, and such other communities, just to get input from them. And then this work begins at a course, collecting text. Common Voice is a project for building speech recognition, and we started with text because we can't have audio without \[unintelligible 00:30:58.08\]

So building relationships with these organizations basically is also in our best interest, because then we can find avenues to get texts from them if they are existing, or build programs that can enable us to create text in the course of our work.

And then we've learned so far from linguists especially that there's a lot of diversity in Kiswahili speakers. This is something that I innately knew as a Kiswahili speaker, because listening to someone speak, there's a lot of nuance; I can potentially tell what part of the country \[unintelligible 00:31:33.07\] I can potentially tell if they're not Kenyan, or are Tanzanian, or are from the DRC. And then there's an additional level of nuance that is apparent among people for whom Kiswahili is their mother tongue. And this is a distinction that I'll say even I wasn't aware of, because many of us in Kenya and in Tanzania learn Kiswahili because it's a national language in the country, but then it's actually someone's mother tongue, and like many African languages, there are related dialects.

\[00:32:06.20\] So we are also learning a lot of the nuance, the fact that for people whom Kiswahili is their mother tongue, if they listen to someone speak, they know "Okay, you're originally \[unintelligible 00:32:15.00\]" or "You're from this particular part of the Coast", and they sort of label all the rest of us as off-country Kiswahili speakers. Off-country is like away from the Coast, the East-African Coast, which is the home of Kiswahili.

So learning about all this nuance and recognizing that it would be great if we could capture t his diversity in the dataset - that's also been an interesting journey. Working with the linguists... The way this work will -- at least the engagement with the linguists, that's currently shaping up as subsets of the datasets that are representative of the various dialects and variants of the language. So there's also nuance depending on what other language, because... To try and explain further, in Nairobi for example - Nairobians rely heavily on English, and it becomes apparent in our Kiswahili speech... Because Kiswahili and it sounds like it's a translation, as opposed to it sounding like speech that is naturally in Kiswahili... Versus someone from the DRC, now I imagine they would mix their Kiswahili with French, and that's another level of distinction. And to people who are native Kiswahili speakers, to them we are all just off-country Kiswahili speakers.

So there's layers, and it's super-fascinating, but again, at this point we are really thinking about it in terms of subsets of the entire dataset, which can be used to first fine-tune to various contexts, so that if you're building an application for the Coast, then we have datasets which make it easy for you to fine-tune to that context. Or if you're building for Nairobians, or if you're building for people in inland Tanzania, then there's datasets that you can use to fine-tune... But then beyond that, to evaluate performance. Because at the end of the day, I tend to think that Kiswahili could do to other African languages what Western languages have done to all African languages, which is to be the focus of research and funding and development, and at the expense of others. Now Kiswahili is being spoken in parts of Southern Africa, and I think that's amazing, that we are now pushing for potentially one language to be spoken across the African continent. But then I sort of worry that that may come at the expense of smaller languages, or other languages in general... Because now parents may start to think, "Hey, you should learn Kiswahili for upward career mobility." But then that may make the mother tongue come in second place, or be ultimately forgotten.

But going back again to the work with the linguists, we also want evaluation datasets, which can mean that we ensure that there's at least some minimum performance for all diverse speakers of Kiswahili. There's also a very strong gender thread in all our work. We realize that women tend to be -- well, I'll start with the fact that speech recognition systems generally perform worse on women. And this can probably be attributed to an imbalance in whatever the original dataset is. Fewer women contribute to this dataset, and that could be for a multitude of factors. So we're being very intentional about creating spaces for women to contribute to the dataset, because the challenges that they face may be unique. But beyond that, we would like for them to also be part of developing \[unintelligible 00:35:48.08\]

**Daniel Whitenack:** Well, Kathleen, I'm really excited to hear about the work that you're doing in terms of building these datasets, and the way that you're thinking about having things like a strong gender thread in all your work, and why that's important... I know myself, I've been challenged in this conversation to think about ways in which myself as a practitioner can be involved in creating more diverse datasets, getting involved in these types of communities.

\[00:36:18.23\] I was wondering if you could maybe close us out by talking about how from your perspective - like, if practitioners are listening to this podcast and they have a desire to maybe contribute to work related to this, either building language diversity into text or speech or other datasets, or maybe there's people in local language communities that are listening to this and wanting to get involved, wanting to build up datasets that could promote this set of technology with their language, what are ways that these two groups can get involved in this work? What recommendations would you make to them? How would you recommend that they connect with people doing this work and get involved, so that the community can grow?

**Kathleen Siminyu:** Thank you for this question. So first to the researchers who could potentially contribute to this work - I'll highlight the model I've seen with Masakhane, because I think that works great. It could be through mentorship. I think there's definitely ways to find groups of junior researchers who belong to these language communities, or are under-represented groups that could benefit from working or collaborating with you. So that's one thing \[unintelligible 00:37:32.20\]

Second is in the event that researchers are working or are keen to work on low-resource language, it's possible that they'll have funding to create these datasets, so I'd challenge them to - beyond looking for native speakers and having them create a dataset, which you then take away and go work on in your lab in isolation, I'd challenge them to use that as an opportunity, again, to mentor. So it may be that they're not only looking for a native language speaker, but they're looking for a native language speaker who is also a junior researcher interested in this field. And so they can start contributing by creating the dataset, but then you can also then create avenues for them to contribute to what comes next in terms of the analysis and the actual work that's good after the dataset has been created. I think that's another model that would be great, and \[unintelligible 00:38:24.21\]

Then turning back to language communities, I'm going to again at this point highlight Common Voice, because I think it's pretty amazing that Common Voice as a platform means that you as language contributor or a language community don't have to start thinking about this work from a standpoint of "Okay, what tools do I need to collect the data? Where am I gonna store the data? What's the infrastructure going to be like? How do I access the data?" and all those dynamics. I think it's as simple as if you have access to the internet and can access the Common Voice portal, then you can start creating, in this case a speech recognition dataset. It's as simple as that.

And if you look a little, I'm willing to posit that there's opportunities for you to identify other such free resources of platforms where you can start creating datasets. Beyond that, I like to think of language communities, particularly language communities that are not already \[unintelligible 00:39:29.15\] So look at Kiswahili, for example - it's a huge language, there's loads of speakers, there's loads of interest from people off of the continent in having Kiswahili resources exist. But I personally see it as an entry point to other local languages that are spoken in the places that Kiswahili is spoken. So if a speech dataset exists for Kiswahili, it's possible to then take that text and translate it into another local language that you speak if you're a Kiswahili speaker. And in that way, it could be a machine translation dataset that comes out of it. It could go on to become a speech recognition dataset.

\[00:40:06.11\] But then I'd also challenge these communities to then think about licensing. And licensing is a pretty interesting topic in the field of NLP, because on one end we have the very well-resourced researchers who don't ask for permission and just create everything off of the web, and then there's the language communities and the junior researchers who work very hard to create these datasets and then are not necessarily the ones who get fast publication or most interesting publication because of constraints like skills or resources.

So I would challenge them to think about licensing that can \[unintelligible 00:40:39.27\] their needs. And it may be that you say it's useful or it can be used for academic purposes, but non-commercial ones. Or it may be that you say you don't want the dataset used in any manner until individuals from your community can be the ones building the solutions. Or it may be that you say "Hey, this is the language that we speak, and there's 100,000 of us, and nobody cared about this language before we started building the dataset, so we actually reserve the right to control all the solutions that are built from this dataset." Because at the end of the day, you are the ones that will be directly affected by whatever those solutions are.

So basically, I think as we bring more languages online, we should empower those communities to start thinking about how they can center their needs. Because they don't need to just create resources and make them available for the most resourced or the most skilled to swoop in and build tools which they then package and resell to the language communities that worked hard to do it. And bringing these two together - I don't know. Maybe these things I've highlighted already in my response, but I'd like \[unintelligible 00:41:51.00\]

**Daniel Whitenack:** I definitely think that those are great jumping in points for our listeners who are interested. We will definitely include links to the Masakhane community and the Common Voice platform in our show notes. So please take a look at those, and get involved, and think about how you can start thinking about contributing in various ways, or mentoring, or whatever it might be.

Thank you so much for joining us, Kathleen. It's been a real pleasure to talk with you. I really appreciate you bringing your perspective, and the hard work that you're putting in on these problems. Thank you so much.

**Kathleen Siminyu:** Thank you for having me, Daniel, and everyone else of the Practical AI podcast.