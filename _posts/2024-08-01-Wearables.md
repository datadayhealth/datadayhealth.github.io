---
title: Beyond Steps - The Real Power of Smart Watches
layout: post
description: Your smart watch analyses your every move. How safe is that data? And how can it benefit your health?
Join Florence (@florencetownend) and Davy as they guide us through the world of wearable tech, exploring its implications for the future of medicine and the security of our data.
file: https://file-examples-com.github.io/uploads/2017/11/file_example_MP3_700KB.mp3 #Link to your .mp3 file
length: "57:14" # mm:ss
videoid:  #Copy here only the id of your YouTube video. Optional
---
Your smart watch analyses your every move. How safe is that data? And how can it benefit your health?
Join Florence (@florencetownend) and Davy as they guide us through the world of wearable tech, exploring its implications for the future of medicine and the security of our data.

### References and Websites
"Are wearable devices the new healthcare revolution?" by Emily Magee (2023) https://www.news-medical.net/whitepaper/20230110/Are-wearable-devices-the-new-healthcare-revolution.aspx

"Why consumers—and doctors—are wary about wearable data" by Chris Arkenberg (2021) https://www2.deloitte.com/uk/en/insights/industry/technology/wearable-technology-healthcare-data.html

Lu, L., Zhang, J., Xie, Y., Gao, F., Xu, S., Wu, X., & Ye, Z. (2020). Wearable Health Devices in Health Care: Narrative Systematic Review. JMIR mHealth and uHealth, 8(11), e18907. https://doi.org/10.2196/18907

"Top 10 High-Growth UK Wearable Companies" by Lily Ruaah (2023) https://www.beauhurst.com/blog/high-growth-uk-wearable-companies-2023/

"This CEO is out for blood" by Roger Parloff (2014) https://web.archive.org/web/20230105230617/https://fortune.com/2014/06/12/theranos-blood-holmes/

"How Playing the Long Game Made Elizabeth Holmes a Billionaire" by Kimberly Weisul (2015) https://web.archive.org/web/20230210082628/https://www.inc.com/magazine/201510/kimberly-weisul/the-longest-game.html 

"Meet The Healthcare Entrepreneur Set To Revolutionize Blood Testing" by David Prosser (2020) https://www.forbes.com/sites/davidprosser/2020/07/22/meet-the-healthcare-entrepreneur-set-to-revolutionize-blood-testing/ 

Vijayan V, Connolly JP, Condell J, McKelvey N, Gardiner P. Review of Wearable Devices and Data Collection Considerations for Connected Health. Sensors. 2021; 21(16):5589. https://doi.org/10.3390/s21165589

"Fitbit and Google merger: What happens to your health data now search giant owns it" by Adam Smith (2021) https://www.independent.co.uk/tech/fitbit-and-google-merger-what-happens-to-you-health-data-now-search-giant-owns-it-b1787865.html

"Where is all your health data going? The Google and Fitbit scandal explained" by Matt Evans (2023) https://www.techradar.com/health-fitness/fitness-trackers/google-and-fitbit-scandal-explained

"What is Google going to do with your Fitbit data? Anything it likes" by Michael Sawh (2019) https://www.wired.com/story/google-buying-fitbit-health-data-privacy/

"What Data Does Apple Collect?" by Chyelle Dvorak (2022) https://www.reviews.org/internet-service/what-data-apple-collects/

"IoT Forensics: Analyzing Apple Watch 3 File System" by Vladimir Katalov (2022) https://blog.elcomsoft.com/2022/02/iot-forensics-analyzing-apple-watch-3-file-system/

"Apple’s Empty Grandstanding About Privacy" by Ian Bogost (2019) https://www.theatlantic.com/technology/archive/2019/01/apples-hypocritical-defense-data-privacy/581680/

"HLTH23: Headspace, Oura partner to bring a high-tech approach to tackling stress, mental wellness" by Heather Landi (2023) https://www.fiercehealthcare.com/digital-health/hlth23-headspace-oura-partner-bring-high-tech-approach-tackling-stress-mental

StrivePD App https://apps.apple.com/us/app/strivepd/id1275051699

Reichmann, H., Klingelhoefer, L. & Bendig, J. The use of wearables for the diagnosis and treatment of Parkinson’s disease. J Neural Transm 130, 783–791 (2023). https://doi.org/10.1007/s00702-022-02575-5



### Transcript
Florence (00:05):
Welcome to Day's Day Health, a podcast all about machine learning and medicine, brought to you by two University College London, PhD students, me, Florence,

Davy (00:14):
and me Davy,

Florence (00:15):
And made possible by the Turing Roche Partnership. I'm Florence, I'm a PhD student and I research AI applied to neuroscience and I do my PhD at University College London.

Davy (00:28):
I'm Davy. I'm also at University College London. I'm looking at epistemic injustice and contested illnesses. So I'm in the philosophy of medicine side of things, and we are both community scholars for the touring Roche Health Partnership. I know very exciting. Lots of stuff to do with big health data and AI and the applications of that. And this podcast is going to be about multimodal health data and can you help me out with the definition for that?

Florence (00:56):
Sure. So health data is any sort of information that you can get from someone about their health. So it could be a brain scan, it could be blood tests, it could be how fast they're walking, anything like that. And the multimodal side of that multi is many. A modal is basically types of data. So if you've got a brain scan and you've got a blood test and you put 'em together, that's multimodal data.

Davy (01:20):
And we think this is really important and really interesting because health data is something that's very personal, but it's super interesting because as technology develops, there are more and more ways of collecting this health data and more and more different types of this data that we can collect. So in the course of this podcast, we are going to be covering everything from health apps to how hospitals implement AI systems and something super funky called data fusion that I don't know enough about yet. So Florence is going to walk me through that one near the time.

Florence (01:57):
Don't worry, we'll get there one day.

Davy (02:02):
So today's topic is wearables. So these are devices that you wear on your body that measure, track, analyse, and transmit health data. And they're usually like small, portable devices. And these are actually increasingly common in daily life. There's a good chance you might be wearing one right now if you own an Apple Watch or a Fitbit to track your activity, then you own a wearable

Florence (02:26):
Also kind of if even own a phone, it will track your steps and stuff. So I guess maybe most of us have wearables at this point.

Davy (02:33):
Excellent point. Yeah. So in this episode we are going to be focusing in particular on wearables that record and then store and or transmit your health data. So something that records your data, like a phone in your step count as Florence just said, or something that then transmits your data to a healthcare professional, to a cloud storage service.

Florence (02:56):
So basically you were just not looking at things like insulin or artificial kidneys. Those are wearables technically, but we're not really looking at them in this episode.

Davy (03:05):
Fabulous. Let's get stuck in. Great.

Florence (03:08):
So looking more at the kind of what's happening right now in the commercial sector. So huge companies like Apple, Google, Samsung and Amazon are some of the world's leading wearable tech companies. And the wearable tech market is valued at 115.8 billion in 2021. And it's predicted to be worth 280.5 billion by 2028.

Davy (03:27):
That's big money.

Florence (03:28):
That's big money. And the number of patent applications in wearable tech increases every year, and this is really a growing industry. And according to the 2021 Deloitte survey, 39% of Americans own a smartwatch or a health and fitness tracker. And these trackers are increasingly collecting more and more types of data. There's even a UK company that makes what is essentially a Fitbit for dogs, but that it has GPS trackers in it and activity monitors for our little furry four-legged friends. And it's meant to enhance dog's wellbeing, detect and prevent health issues later activity and also promote longevity. So if dogs have them and humans have them, why are they so popular? So there's an argument to be made that they're fashionable. I mean, apple watches, they kind of market themselves as being an accessory. There's also an element of wanting the latest tech. It's another thing to go get the newest version of.

(04:21):
There are also a number of other reasons why they're attracted to people. I think it's part of human nature that people kind of want to monitor stuff about their own lives. So the ability to monitor your own health and track changes over time. You can see progress if you're working on your fitness. You can see how various measurements linked to your fitness are changing over time and it's also not something that people have been able to do for a really long time without access to really intense medical equipment. Also, there's satisfaction of making those rings close on your Apple watch, hitting your 10 K step goal.

Davy (04:52):
I've got to say on my phone I've got a step counting app where whenever it hits the 10,000 mark in a day, it goes like bling and makes this little happy noise and it makes me feel so good.

Florence (05:04):
I honestly can't relate. I think I never look at my step counter let ever become depressed for the day. And also their ability to monitor and manage chronic health conditions like diabetes and pulmonary conditions and hypertension. And we're going to be looking at more specific medical applications of wearables later on in the episode. But there's a systematic review in 2020 by Lou Etal, which looked at different categories of what wearable tech devices can be used for. So you can use 'em for health and safety monitoring, chronic disease management, disease diagnosis and treatment and rehabilitation. So I guess the most common way of using it for everyday people will be under will be health and safety monitoring. But there are loads of different other ways that wearables can be used in our lives. So what tech do these wearables use to get all of this data?

(05:52):
So you use sensors, medical chips, wireless communication, information technology. And to be honest, I don't understand a lot of that stuff, which is testament to how really quite incredible these devices are. They're so small and they can do so much. And often this real-time data that's collected using these sensors translate to the internet. So for personal analysis or maybe transmitting it to some sort of healthcare provider to look at it for you. But there is new ways that wearables can be made happening all the time or about biosensors that are like sticky patches that collect biological and chemical data whilst you go about your daily lives.

Davy (06:28):
So these types of sticky sensors that go on the skin are called epidermal biosensors, and there's a type called a graphene electronic tattoo or GET. And this is an emerging field in electronics, but it allows wearers to disguise the fact that they're wearing a sensor from the public eye. So it's the idea of a more subtle wearable experience, especially for people who might feel a little bit, I suppose, wearing a medical sensor. And it is these exactly resemble a tattoo. It's not identifiable as a sensor. And I think that is super cool.

Florence (07:05):
Yeah, pretty badass. Get a whole dragon on your back and you're like, actually

Davy (07:08):
This is a medical wearable.

(07:15):
So yeah, so there is amazing technology coming out all the time, creating different types of wearables, finding new types of data to collect and analyse. And I just wanted to chuck in here a little bit of a historical interlude. You've probably heard of the Theranos scandal where we have an American woman, Elizabeth Holmes, who created this startup with the idea of fantastical medical technology around blood testing. Her original idea that led to the whole saga of the company was a wearable patch that could administer a drug and at the same time monitor the levels of that drug in a person's bloodstream and then wirelessly send that data to a doctor

Florence (07:59):
Mad.

Davy (08:00):
Yeah, unfortunately, just like her apparently revolutionary blood testing machines, it didn't work. So the reason she ended up arrested at the end of this saga is she was extremely good at the business side of things. She raised $945 million in investments for her idea, but her equipment straight up did not work. So she ended up getting done on fraud charges. But her first ever idea was for a blood testing wearable, so a small wearable patch with a microchip that could administer drugs, monitor how the patients respond to them in real time and transmit that data to a doctor and be able to adjust the dosage as required. And her big idea here was to include a mobile phone chip to allow it to transmit the data with the idea that the patch would let the doctors watch the movie of what was happening in patient's blood.

(08:53):
So this is a very sort of early idea for the type of wearables that we are talking about today. Unfortunately in 2003 when she first pitched this idea, the technology was not there. It did not work. It sounded cool, it sounded cool enough to get a lot of people to spend a lot of money investing in her, but the science, the medicine didn't back it up at the time. However, something I think is super cool is now 20 years later, we actually have similar types of tech in development and actually quite far along the development process. So for example, there's a team at UCLA who've created a patch that caveat in rats uses microneedles, which analyse the fluid found between cells less than a millimetre under the skin and can continuously record concentrations of medicine in the body and can predict how much of a drug will be delivered to the body over a period of time. So the idea there is to help doctors give precise doses, which is important in terms of some drugs that have a thin margin of helpful to harmful. For example, some cancer medications, obviously they are helpful to help you fight off the cancer, but they can also be very detrimental to your physical health and wellbeing. So this would allow them to be extremely precise with these doses.

Florence (10:14):
There's that old adage, the dose makes the poison.

Davy (10:17):
Yes, no, very relevant in this case. And I mean also because these drugs are on that borderline of helpful, harmful, but also because people differ so much, people's height, weight differ and that means that their tolerance and reaction to drugs differ. And this would allow them to get sort of a bespoke amount of a drug and to be monitored while it's in their system. And I will explain to you how this works very briefly, but I need you to know that I also don't fully understand this explanation-

Florence (10:50):
And neither do I.

Davy (10:51):
Exactly. So we're on a shaky ground here. But so the way this patch is supposed to work is it uses engineered strands of aptus, which is artificial DNA, and when it comes into contact with the target molecule, these chain shape, so on one end of the aptus we've got golden nanoparticles at the end of the microneedle, and then the other end is attached to molecules that make signals when the aptus chain shape thereby detecting the drug. It sounds very clever and very out of my league.

Florence (11:26):
Elizabeth Holmes absolutely fuming at this. It's actually working.

Davy (11:32):
And another really cool technology, which is similar to what Theranos was trying to create. In fact, this does one better than Theranos because Theranos big idea was to be able to do about 200 blood tests just by taking one drop of blood from a person. But now Cambridge medical technologies are actually developing form of bloodless blood tests. So they've not only, they've surpassed Theranos big idea here. So their device is able to extract fluid from the body without using a needle via advanced electrochemical techniques to measure biomarkers in blood. It also monitors health in real time. And again, I'll be honest with you, I don't fully understand how this works, but pain and needle free blood test sounds pretty good to me.

Florence (12:22):
I know a lot of people who'd be very happy to use that instead of a regular blood test. Yeah,

Davy (12:26):
15-year-old me who fainted at the side of a needle would've loved this.

Florence (12:30):
I had a friend who if she got a blood test out of one arm, she'd be fine. The other arm she'd throw up. Every single time left arm, she couldn't hack it, so this would be great for her.

Davy (12:43):
So yeah, so this blood test, apparently, again, speaking from a place of non expertise, it uses a chip that's held in place by a bandage and it generates a tiny electric shock that disrupts cells in the top layer of skin, which breaks down the skin's waterproof properties and allows some fluid from capillaries to be tested by the bandage that holds the chip. The chip in the bandage device is constantly analysing biomarkers and they bill it as an electronic bandaid, which I quite like. And they actually got a lot of funding from the US government because this can be used to potentially monitor alcohol consumption and blood alcohol levels.

Florence (13:23):
I bet a bandaid with needles in it is way more painful to take off than a regular one as well.

Davy (13:29):
You're not only riffing off your arm hair, you're getting a few microneedles under the skin.

Florence (13:32):
Yeah, you take two steps forward and one step back, don't you. Alright, so let's get into the nitty gritty of actually what a wearables doing. So wearables can usually be classified into what part of the body that they're working on. So you can have head wearables, limb wearables, torso, wearables. So if you're thinking, God, what are wearable devices for the head? Well, hearing aids, smart glasses, if you remember the Google glass era of, I dunno, 2013 where everyone was like, this is going to change the world. And then it absolutely flopped. The Snapchat glasses! I don't remember those.

Davy (14:12):
Wait, Snapchat

Florence (14:13):
Glasses, Snapchat glasses. They were really ugly and they were giving them out in a bunch of shopping centres and I think you could take Snapchats with them. I dunno if those technically count as wearables, I feel like they might, maybe we should know. But those also flopped. And you can have wearable headbands devices for the limbs are obviously smart watches, but also other measuring devices. You can have ones for lower limbs like shoes and socks to monitor movement for rehab purposes. And then torso devices can be belts, suits, and even underwear. And the wearable underwear, well I guess all underwear is wearable. Wearable tech underwear. Wearable tech underwear uses biosensors that we were talking about before the sticky patches. They have those sticky patches in your underwear and it will look at kind of basically what you're sweating throughout the day. So it's trigger when a bit gross.

Davy (15:02):
I'm not sure I like the idea of a pair of underpants that records my sweating throughout the day.

Florence (15:09):
Well yes, you would think that unless you were a pro athlete and you need to know exactly what's come out of your bloodstream at every point and you don't want to have blood tests all the time. Those bloodless blood tests aren't ready for mass consumption yet, I'm assuming. So you've got to take a look at your underwear and see what's happening inside your body.

Davy (15:28):
Well thank heavens I'm not a professional athlete.

Florence (15:31):
Amen. So belt suits and underwear, all of this tech development has also focused around sensors that can be embedded within fabrics and also around fabrics. And this is called electronic textiles. So let's get into what data wearables can collect. And again, I'm going to reiterate it's important to note that a lot of advices can be classed as wearables from a whole artificial kidney and the underwear that we talked about. We're concentrating this episode on the most classic wearable that comes to mind when you say wearable tech. And that is the smart wristwatch. The smart wristwatch. It's hard to say the smart wristwatch.

Davy (16:09):
Say that 10 times faster.

Florence (16:12):
So different brands of smartwatches or different sensors in them, but the vast majority have the box standard that you'd expect. So accelerometers, heart rate measurement systems, pedometers, which measure everything to do with your walking gyroscopes and also get an overall view of someone's day-to-day health and activity. And you might recognise that a lot of these things are also in smartphones, but I guess the difference between a smartphone and a wearable wristwatch is that because the wristwatch is right up against your skin constantly, it has better chance of measuring these things accurately to do with your own body. But there are things that smartwatches can't measure. They're not a catchall for everything. So currently it's looking at measuring blood pressure is proving tricky. Both Samsung and Fitbit have claimed a couple of years ago that they're looking into it if they could accurately detect high blood pressure with their wearables. And that is a super important factor and marker for a lot of health conditions. So right now Samsung offers it, but you have to get an additional cuff accessories. To me that's basically how blood pressure tradition is traditionally taken. You just have luxury of doing it in your own home. But to be fair, there's also quite a few GP surgeries where you can go in and do your own blood pressure testing there. So I dunno

Davy (17:28):
If you've already spent out on the smartwatch, do you really want to be spending more money to get more medical equipment when the GPS just round the corner?

Florence (17:36):
So maybe the wearable watch claims, it can measure aspects of your health, but it's kind of doing it in a roundabout way, which means it's not super accurate. An example of this is measuring VO2 max and VO2 max is the amount of oxygen your body uses while exercising as hard as you can cannot relate, but it's an important indicator of cardiovascular health. Another example is measuring blood glucose levels. So wearables that aren't specifically designed to look at blood glucose levels, they might look at metrics that can indicate prediction to someone's blood glucose, which actually is a huge area of research, but for really accurate readings it might not be enough. So if you're relying on those readings, maybe you need to go something more specialised. And of course there are aspects that make up a human's health that are always difficult to measure. How can someone's pain level be measured and fatigue that someone is feeling? So your smartwatch might say you've got exercise to do, come on, you've got to close those rings. But if you are in pain, if you're feeling fatigued, your smartwatch can't know that and it won't know how feasible it's for you that day.

Davy (18:37):
Just to add in very briefly regarding the blood glucose levels, I've seen those patches that you pop on your skin and then they transmit to an app. Those seem really cool,

Florence (18:47):
Very cool.

Davy (18:47):
And probably more accurate than anything a smartwatch can do right now.

Florence (18:52):
And there's a lot of research looking into how those sorts of diabetes specific wearables can be used to predict what glucose or insulin you need in the future. And you could do personalised dosages based off your previous kind of glucose spikes throughout the day. Very handy. Very handy.

Davy (19:12):
Yeah. So despite the fact that these wearables might not be wholly accurate and they might not measure everything relevant to our overall health and wellbeing, they still can collect, analyse, and transmit increasingly sophisticated data and a lot of it. But where is that data going and how is it being used currently? So one of the ways that we've touched on already is personal use. Consumers may use data from wearables as displayed on devices like smart smartwatches or transmitted from devices to apps on their phones in order to track changes in personal health and fitness. Things like tracking step count improvement over time, weight changes, changes in blood pressure, even sleep tracking. And a term that I found really interesting and I was doing a bit of research into this, there's two terms actually the concept of the quantified self. Yeah, I know. Which refers to the process of collecting personalised data about your life and your wellbeing using these wearable devices.

(20:13):
And also the idea of life logging. So tracking your own data over a long time. And these are things that are becoming increasingly popular with people. People like to have this information to be able to see it, track it, maybe make changes. And as we mentioned before, this is not something that people have been able to do prior to the current day without having access to hospital equipment and things like that. But aside from say, health consciousness or vanity, which is not necessarily a negative, these wearables could help people with little to no access to regular medical care actually gain a degree of control over their health or alert them to changes that might need medical intervention. So here, I suppose I'm referring to people say for example in the US who don't have health insurance or don't have regular access to doctors, although I could also be referring to the UK with the very long wait time for any sort of medical appointment and how oversubscribed services like gps are. This could be a sort of stock gap measure or a way to just keep an eye on yourself if there aren't medical services that can do that for you reliably.

Florence (21:30):
If you aren't on that phone at 8:00 AM making that appointment, I'm sorry, you're done for, got to look at your Apple Watch instead.

Davy (21:39):
And another use could be for people who work really remotely, for example, like on oil rigs, not just for monitoring, but to provide additional context and to improve the quality for remote consultations. So for example, if you've got a Zoom meeting with your GP and you work on an oil rig, it's going to be helpful if the GP can also see, say something like a readout of your blood pressure. But this data that's being collected, so it'll either be stored locally on the device or which is what usually happens on cloud services. And this is secure ish

Florence (22:14):
Ish

Davy (22:15):
Somewhat

Florence (22:16):
Secure, secure ish,

Davy (22:19):
although we will be discussing the extent of this shortly. However, one thing that I wanted to flag is that if people choose to involve third party apps to, for example, analyse their health data, this can drastically compromise security, which yeah, we'll get to in a second.

Florence (22:37):
Don't just be tapping, allow access to every single app on your phone. You've got to think, bro, you've got to think about it.

Davy (22:42):
So one of the things that I had a look at while I was doing research for this podcast was a review paper of wearables by Veja et all 2021 and they pause that wearables could be really useful for doctor patient communication specifically in reducing the number of in-person checkups and appointments that you might need. So for example, you don't need to go in to get your blood pressure tested if a wearable can do this and transmit the result to a healthcare practitioner, but they also suggest that, well maybe the data that wearables collect is actually better quality in that wearables give a view of a person's health and fitness over a long period of time. Whereas something like a checkup produces a little snapshot of a person's health on that particular day and that may not be representative of their overall health.

Florence (23:33):
Have you ever gone to the doctor and you've been feeling rubbish for two weeks and the day you go to the doctor, your appointment's finally there and you're like, oh, I'm actually feeling fine. And I'm like, well, is anything wrong with you? You're like, yes, no, it's I promise.

Davy (23:45):
Sods law. Absolutely. You get there and you're suddenly in the greatest health of your life.

Florence (23:51):
Yeah. So I guess that's the way that wearables could be useful is that you could be like, no, no, no, I promise I actually was sick. You can see it, right?

Davy (23:57):
Yeah. Yeah. They also point out that things like self-report questionnaires rely on patients accurately remembering and reporting their symptoms and other medical tests can take a lot of time and can be quite costly. Saying that, I will briefly caveat by saying that wearables really can't do everything yet. They can't do all the tests yet. So that time and cost is going to be a factor at least for the near future. But another big application that they brought up is the remote monitoring of patient rehabilitation. Instead of having to be observed in a clinic or in a hospital setting, a person could just be monitored remotely by a wearable with that data being sent back to a medical team or to medical personnel. I'll briefly point out now that the way that this data is transmitted to healthcare providers is usually by wifi, which isn't hugely secure.

(24:58):
So wearables tend to have limited storage and computing capabilities and therefore can't really process the data locally. So on the wearable, and as a result, they transfer it to a powerful remote computer or to a cloud where the information is then deciphered and analysed. But wireless communication channels can be quite vulnerable and this can result in data loss during transmission as well as errors in analysis and prediction. And this hints at the data security discussion that we are getting to, but I will just quickly highlight some other medical applications. So this ties in with what we said about medical tests taking a long time and being expensive, but wearables generally have a small footprint and cost less than expensive and bulky hospital equipment. It means patients can be monitored outside of the hospital and don't have to stay there taking up a bed. And there's some cut costs for the hospital and and for things like rehabilitation, so for example, there's a thing called the e physio wearable system which remotely monitors you and actually gives you virtual coaching to help you complete rehab tasks at home and it collects some processes data in real time.

(26:10):
I will say very briefly that as an SDS person, which is, so this is my department, the science technology and society department here at UCL as an SDS person, as someone who is taught to look critically at science and medicine and think about it in terms of say social justice, I do have some concerns here. I think that the art of medicine is a really important part of medicine. There's something to be said for that doctor patient relationship and certainly things like the placebo response. So I'm not talking about giving someone a sugar pill and telling them it's a real medication. I mean the placebo response of being listened to and being asked questions as if a doctor cares and understands about you, this markedly improves how patients fair in the long term. And I'm slightly concerned that if we go all gung-ho on wearables and making everything be remote, that we might lose this aspect, this sort of care aspect.

(27:14):
And I think particularly for older populations that might be quite a harsh transition away from the type of medical care that they're used to. I would also say I have some concerns around who might be, say, alienated or disenfranchised if we do go all out on using these wearables. So like I mentioned, elderly populations, populations of people who have reason to be a bit wary of technology and also we're looking at things that are supposed to work by sending you home and having you monitored remotely who's being sent away and who's being allowed to stay in the bed. I think there is an important conversation there around how marginalised populations may or may not be treated with this shift to wearables. However, of course this is all theoretical and I won't go into it very deeply now because that's not the point of this episode, but couldn't resist how to bring that up. Just food for thought. We think of tech and stuff like that as some sort of fantastic utopian sort of solution. And it's worth really thinking those things through because

Florence (28:27):
Yeah, and you definitely get disenfranchised when you're working in tech yourself, then you realise it's just maths. Just maths.

Davy (28:37):
And it's that whole thing about, oh, technology and science are unbiased and - Who is the person programming these algorithms? Who's the person making the tech? Oh, they come with their own biases and things like that and it all gets built in anyway. There's also use for these things in clinical trials. So depending on the trial participants might be given a sensor to wear and then told to perform certain movements. An example in the Veja Etal 2021 paper is of a clinical trial looking at the disease progression of AAL spondyloarthritis because yeah, doctors knew that changes in spinal mobility are a marker of the progression of this disease, but until now they've not been able to accurately monitor these changes.

Florence (29:26):
And of course there are also commercial uses of this wearable data and something that we should consider for committing to a brand or a type of commercial wearable is does the company sell your health to third parties? Does keep your health data secure. One would hope that bigger brands would have really excellent privacy agreements and robust data protection plans and place sensitive data. I mean they've got the money to do it, but they, so in this bit I want to kind of compare the data security measures of the two huge brands in the wearable marketplace, the Apple Watch and the Fitbit, which is now Google owned. I'm sure many of you will have heard the phrase in relation to internet, social media, whatever, that if you're not paying for the product, you are the product. We all know about Facebook scraping user data, selling it to third parties. Like, oh my god, how did this advert come up? I just spoke about innocent smoothies the other day, not #spon.

(30:23):
And how did it know? It was like, well it's looking at your search history, health data is sensitive and could have extreme ramifications for a person's life is managed improperly. What if an insurance company got hold of the fact that your health data is doing something funky? So we need to consider how the data is stored, handled, and used by the companies and devices access it. So looking at Fitbit way back in 2012, which makes me feel old, Google bought Fitbit and there was a lot of concern about what Google were going to do with users data. I mean Fitbit's chief executive as predicted assured customers that users retain control of their data, remain transparent about what the company might do with it, but there are concerns that the moneymaking potentially user data would, it would probably trump privacy and data protection rights under EU law.

(31:12):
Google would not be able to use user data for things like advertising for 10 years. But concerns were kind of high considering how data-driven Google's targeted ad system is. And to be honest, 10 years for a company like Google is not that long. Google said they would create a data silo for the Fitbit data separate from the other data and users would have a choice to allow or deny access their data to other Google products like Maps, YouTube, et cetera. But nevertheless, many experts were pretty concerned about the lack of transparency from Google and Fitbit about where data was going, what it was used and what it was used for. Kind of beyond the reassuring platitudes of don't worry we've created a silo. No, don't ask what that means, it's fine.

(31:58):
So there are 29 million active users of Fitbit and Google probably saw that and went, yeah, I want to slice in that pie. The health data won't be used for ads yet. What about all the other data location data, non-health personal data that is all within your wearable tech, a wide article from 2019 with the headline, what is Google going to do with your Fitbit data? Anything it likes notes that Google has changed its tune after marriage in the past. Who's to say it won't happen here? And looking at privacy experts in the field, they've pointed out that health data being owned and potentially accessed by a huge company is inherently problematic, which I feel like we do know, but it's nice to hear an expert say it's quoting somebody from Privacy International, enabling any company through acquisition and merger to embed itself so deeply into so many aspects of our lives is deeply troubling. And yeah, we can hear that and say, yep, that's true, but let's be real, we're still going to buy a Fitbit. And why not directly related to the Fitbit acquisition or data, it is perhaps worth mentioning that in December, 2022, Google was fined 57 million dollars for failing to acknowledge and disclose how its users data was being processed

Davy (33:06):
Concerning.

Florence (33:07):
That's concerning, but maybe that's a drop in the ocean. I don't know Google's finances that well.

Davy (33:13):
Let's have, so the market value of Google is apparently at 863.2 billion. Yeah,

Florence (33:20):
I feel, I think they're okay. That's chump change for them surely. And also there's an article that pointed out on tech creator that Fitbit can freely send data to be processed by corporate partners and third parties. Who are these corporate partners and third parties, your guess is as good as mine. Alright, so that was the Fitbit. What about the Apple Watch? So it was pretty hard to find information about how the Apple Watch uses your data and what happens with the data after it's in it. The good news is that you can make the privacy setting more strict. Obviously the bad news is that you actually have to do this. It isn't default. So you've got to go into those settings and change it around. But to be fair, apple have a pretty decent track record of standing up to law enforcement requests for user data, but they're not necessarily safer than Fitbits. And Silicon Valley has a habit of changing its mind quite a lot. People do point out quite rightly that Apple and other big companies - not just pointing the finger at Apple, often collects more data than you might think. And these kind of companies collaborate with other companies that use that user data in unscrupulous ways.

Davy (34:26):
That is concerning because Apple can be as good as it likes. And then the second it's sharing your data with someone else.

Florence (34:33):
Well exactly, and then they're not really liable for that either. And interesting that we found while researching for the podcast, there are also companies that purposefully hack or crack, depending on the word that you want to use Apple device security in order to help with investigations. So yeah, these devices are protected, but anyone can find a way in with enough time or expertise or if they're being paid to a company called Elms Croft build itself as the only company on the market to obtain a decrypt end-to-end encrypted health data from Apple iCloud. They say that huge amounts of data can come from looking at just one area. So for example, an app watch has an automated workout detection and starts monitoring your biometrics but also your exact location. So if they can get into your workout data, they can get this data too so they can show up whenever you're at the gym.

Davy (35:26):
That's a little terrifying, especially because the watch has already started recording you without you necessarily real, say you start running for a bus,

Florence (35:35):
The agent's going to pick you up on that bus. They're like, I saw you running, I saw your VO2 max go through the roof.

Davy (35:44):
Something that I mentioned a little bit earlier as well is when third parties get involved. So this is in regard to both Fitbit and Apple watches. If you use a third party, say Apple website to analyse your data, this can undo the security and privacy that you get from using these branded watches intentionally or not. And for an example of this 61 million fitness tracker users, which include Fitbit and Apple Watch users had their health and personal information, which includes their date of birth, their weight height, gender location, all sorts. They have this personal information exposed because a third party that syncs user data from these trackers didn't properly secure the data. They had no passwords and no encryption on their database and 61 million people had their personal data leaked.

Florence (36:37):
I mean I'm pretty sure I could make an app ask it to give me access to Apple Watch data and then I could be like, cool, don't worry about securing it. You already said I have allowed access to it,

Davy (36:48):
So this is why you've got to read the fine print.

Florence (36:50):
Yeah, people like me could be making apps, God forbid.

Davy (36:57):
Okay, so now let's look at some limitations of these devices and also the very important data security concerns beyond what we've just discussed with Fitbit and the Apple Watch. So the ways in which data is transferred between devices or between, say your wearable on your phone really poses some risks to data safety. You need to be thinking about where your data goes in terms of cloud services or where it's being stored. If we look at a list of the 10 biggest wearable companies in the uk, the listing for Anthropos, which is a company that has raised 9.12 million pounds,

Florence (37:38):
If I could whistle, I would whistle

Davy (37:42):
They've raised 9.12 million pounds. And what do they say about where their data goes? It says the data their technology tracks is transmitted to a remote care provider seamlessly via the anthropos platform, which gives us no information about where it goes.

Florence (37:57):
What does that mean exactly?

Davy (37:59):
So a lot of these wearables store data locally, so on the device without encryption or data protection, which means there is a high risk of losing confidential health data. Devices also often communicate to apps on smartphones. And these might be using Bluetooth or wifi, which can be unsecured connections. So this doesn't do enough to guard against, for example, a brute force hacking like attack. And as we've said, third party apps on smartphones increase susceptibility to data hacking. One particular area of huge concern privacy and safety with these wearables is that many fitness trackers track your GPS coordinators.

Florence (38:42):
Yikes. Yeah.

Davy (38:42):
Which could be dangerous if hacked, I dunno if you remember this story from a little while ago, but there was a thing where I think it was American. There was an American army base in another country and the location of it was leaked because the soldiers would be doing laps of it wearing their Apple watches or their wearable, which meant that there was all this data showing these people running around in the exact shape of their private army base.

Florence (39:10):
To be fair, even looking at people publishing their Strava runs on their Instagram like cool, I can see exactly where you live. I can see you leaving your house and returning to your house and

Davy (39:20):
Were I a murderer?

Florence (39:21):
Were I I a murderer? And allegedly, God, that would be an absolute, the kid in a candy shop.

Davy (39:30):
Yeah, no, I suppose it's something I don't even think about when I'm going off on a run. I'm glad I don't put that information anywhere.

Florence (39:38):
I'm glad I don't go on runs. That's for purely safety reasons.

Davy (39:48):
And another thing is privacy violations can occur when you are switching tracked location data between devices via Bluetooth or wifi. Another concern as well is that these wearables often have integrated cameras or microphones, so there is a privacy risk there of capturing unauthorised audio or personal information by these means.

Florence (40:12):
Goodness. Imagine people looking at pictures of you taking from your wrist, oh, I can't imagine anything worse. It's like opening a selfie camera on your phone.

Davy (40:18):
The worst angle physically possible

Florence (40:20):
The worst angle.

Davy (40:21):
Also you are mid run or something. So you are red, you are sweaty.

Florence (40:23):
God, the horror

Davy (40:26):
And maybe you're also chatting about personal secrets as you do your 10 K.

Florence (40:32):
Who's to say all my governmental secrets I always talk about out loud on my 5K.

Davy (40:40):
So yeah, overall a collection of economists from European universities pointed out that data collection from health trackers like Fitbit can actually make a fairly complete picture of you as a person. And they say that the combination of Fitbit's health data with Google's other data creates unique opportunities for discrimination and exploitation of consumers in healthcare, health insurance and other sensitive areas. These things might be collecting all of your demographic data and if it gets out there that could be used against you. There is a charity called none of your business N-O-Y-B-I know.

Florence (41:18):
Yeah, good name.

Davy (41:20):
And they have pointed out that as of 2022, the freedom of information requests as to how your data is being used by these big trackers aren't getting anywhere. They're being sort of blocked at every turn. So we really don't have a good idea about where the data is going. And just sort of remember again the old adage of like you are the product, big data is big business, you might be getting something out of these wearables, but the companies are getting something out of your data at the same time.

(41:50):
And then there are some other limitations to consider beyond data security. A lot of wearables in the US at the moment are not HIPAA compliant. HIPAA being their health insurance portability and accountability act, which is to do with what happens with your health data and is involved keeping that private and secure. These apps are not bound by HIPAA obligations. They might have to be in future, but as the industry is in its early stages, they are not bound by these rules that are set up basically to protect you and your health data A bit more sort of like nuts and bolts here is the battery life is a huge factor. Most devices won't be able to give you 24 7 coverage because they need to be removed and charged.

Florence (42:37):
Another thing to charge.

Davy (42:39):
Yes. Yet another thing. And also these things only have so much battery life because they generally need to be small and wearable and some of them that last for a longer time are going to end up coming with larger batteries, which can be uncomfortable for you to wear, which you might not be able to hide under clothing

Florence (42:59):
And kind of ugly as well.

Davy (43:01):
Yeah, exactly. Which is exactly why I think those tattoo biosensors are the coolest things since sliced bread.

Florence (43:08):
I want one now. Yeah,

Davy (43:11):
There's also things to do with the limitations of the tech itself. I'm thinking of terms of noise and errors in their data capture here. These sensors are not a hundred percent accurate. They can make simple errors like your heart rate might be recorded incorrectly if the strap of your apple watch is a little bit too loose. And there are bigger things like sensor misreads, like when they misread what action you just made. If they're trying to measure arm movement and you, I don't know, shifted on the sofa or something and it said, yep, that's an arm movement, they can just simply miscategorize data, which affects the analysis of your data. Even things like nearby magnetic signals can affect measurements. Generally speaking, the accuracy of a wearable device varies depending on the device and its use. And in terms of commercial wearables, again looking at our smart watches, things like that, unfortunately a correlation has been found between price of the device and accuracy of measurements. So you want a super accurate step count, you're going to have to pay the big

Florence (44:12):
Bucks or do it for free and count every step yourself and ruin your life

Davy (44:16):
Manually with a clicker. I just got to know,

Florence (44:20):
Got to know. I can see you doing that one day

Davy (44:25):
And then I'll make my own little noise at the end. I'll go bing! Well this has produced my own serotonin.

Florence (44:33):
Lovely.

Davy (44:35):
There was also something I found. So going back to this review paper via Jan et al, they point out that devices that measure activity or movement can become unreliable when the person's gait is slow or uneven. Which is kind of concerning because I would think the people whose gates are slow and uneven are the people you might want to be monitoring in this way for the aforementioned remote monitoring for the physiotherapy rehab kind of thing. But yeah, so their steps in their movements might be measured incorrectly. And I mean, yeah, we all know examples of this. If you move your arm about and your Apple watch counts it as a step that these are quite common errors. Yeah, so there are various workarounds, there are filters, there are other bits of tech that can be incorporated to reduce errors and noise, but they still happen. Nothing is perfect medical like hospital grade wearables are generally more accurate and have had more testing. The commercial ones less. But yeah, nothing is perfect and wearable device accuracy and validity are the most difficult challenges to overcome and we're just not there yet. There's also potentially some psychological aspects to think about here. So not just in terms of you are becoming increasingly conscious and maybe nervous about the state of your health, there's potentially an obsessive aspect to this constant tracking and monitoring. But also there's concerns around if you need to wear one of these sensors for a medical reason, feeling self-conscious in public, especially if it's an unusual sensor or wearable

Florence (46:14):
Like underpants?

Davy (46:16):
I would hope you aren't walking around with your underpants out in public

Florence (46:19):
Superman style.

Davy (46:21):
But yeah, say like a headband or a belt or something like that, that looks a little off, you can get away with a smartwatch because everyone has them. I say that I don't, I

Florence (46:32):
Also don't. Maybe we should do that as a heads up, just as like a disclaimer. Neither of us own any smart watches.

Davy (46:39):
Then finally, we will probably go over this more in our health apps episode, but I did just want to bring this up quickly that after the June 2022 overturning of Roe v. Wade in America, which has allowed certain US states to illegalize abortion if those so choose, people have suggested that any device that tracks your menstrual cycle is potentially risky. In 2022, Fitbit said, as we describe in our privacy policy, we may preserve or disclose information about you to comply with a law regulation legal process or governmental request. They say that they will notify users if they have to do this, but it means that someone seeking a necessary health procedure like an abortion might face legal ramifications if say Fitbit data implicates them. And obviously this isn't just Fitbit, I'm talking about any sort of tracker that tracks this sort of thing. But it is something to bear in mind and it is quite scary, but it is a reality for certain people. So we have to bear that in mind.

Florence (47:41):
It is indeed. But looking at a positive spin on wearables, there is some recent industry and research news to do with health AI and wearables is quite exciting. So looking at existing wearables in market and commercial applications, Headspace, which you might know of as like a meditation guiding app is partnering with Aura. And Aura is a company that makes smart ring wearables that measure small changes in biometrics like heart rate and temperature. And the idea of this partnership is that people can understand what causes them daytime stress. So Aura has added an AI powered journaling function and when high levels of stress triggers are recorded on the aura ring, it triggers Headspace to offer you a meditation. And Aura and Headspace have both said that this is increasing access to mental health resources. Personally I think that is slightly questionable to me. This seems more of a wearable triggered advertising technique

Davy (48:41):
A little bit. Yeah,

Florence (48:42):
Which is interesting. It's interesting. It's it's novel. It's an interesting way to use a wearable and I'm sure it's helpful for people if you don't realise you're getting stressed and then Headspace is like, whoa, take a chill pill, then I can see that would be useful.

Davy (48:56):
It doesn't replace actual psychiatric or psychological care.

Florence (49:00):
It, it also feels a bit like a mood ring. Do you remember mood rings?

Davy (49:04):
Oh, it was all about the mood ring!

Florence (49:05):
I feel like this is a very high tech mood ring, which we felt I'm here for. And looking at more kind of medical applications. Samsung is partnering with Korea's ministry of Food and Drug Safety to use the galaxy smartwatches to spot signs of potential sleep apnea. And if you don't know, sleep apnea is a sleep disorder which involves breathing to kind of go in repeated stops and starts while someone's sleeping. This is really tricky for someone to spot early because you are asleep when it is happening, but it's also really dangerous if you let this go on for a long time without noticing that it's happening. So it's interesting that you might be able to diagnoses early using your smartwatch.

(49:41):
 And Parkinson's! You can use wearables to monitor Parkinson's and maybe you even diagnose early. So Parkinson's is a degenerative disorder, which involves loss of voluntary motor control along with many other things.

(49:54):
It's quite a multifactorial disease that's not completely understood. And a key part of Parkinson's is the tremors that patients experience. And understanding these tremors is a really key part of panning treatment and monitoring symptoms. And there's an app called Strive pd, which is designed for people living with Parkinson's to log their symptoms and also also at the Apple Watch. So the Apple Watch can be used to track these tremors, notice them instead of the patient having to remember them themselves. And it can be ease useful for tracking when different therapies are given and the effects of them, which can't really be done with regular doctor's appointments. And potentially these wearables could be able to spot tremors early and use as a biomarker for early diagnosis. And in a recent review article, kind of looking at how the management of Parkinson's disease can be aided by wearables, the combination of the two was described as a new window of opportunity for patients with pd, Parkinson's disease that are easy to use and accessible to most of the population. And moving on to another neurodegenerative disease gait in Alzheimer's has been shown to be a non-invasive early symptom of the disease and not only in Alzheimer's as well. This is common in other neurological conditions like motor neuron disease work is being done in monitoring gait through wearable devices, commercial ones, and in-house produced wearables.

Davy (51:14):
That's so interesting that someone's gait could be an early indicator for one of these illnesses

Florence (51:20):
And often people might not even notice and you could only notice through repeat measurement, which is what wearables can do.

Davy (51:29):
So that is our episode on wearables. We've done sort of whistle stop talk through the topic and I think before we end here, we are going to leave you with some things to keep in mind, like the fact that if you're using this for health purposes, a doctor will need to review the data. The device is not a replacement for a doctor. Yeah, don't stake your life or important decisions on what your Apple Watch says. Go see a GP or whatever healthcare provider you have. And also just because your wearable says to do a certain type or amount of activity, you really shouldn't be straining or hurting yourself to meet these goals or doing anything beyond your abilities. You and your health are unique and these recommendations are very one size fits all. And also if you're feeling sick, if something hurts you to do, if doing 10,000 steps one day means you can't get out of bed the next day, don't do it. I would say take these things with a pinch of salt. They're guidelines, not rules.

Florence (52:33):
And putting a mental health and philosophy hat on for once is the constant monitoring of our health a hindrance or a help. And I think that's a different answer for every single person. For me personally, I think it wouldn't be good for me to constantly know what's happening in my health. I feel like that would freak me out a little bit. But also do these wearables give false assurance of healthy behaviour? Like you said, I've closed my rings today, so that's me good. I don't need to do anything tomorrow. People might think that, I don't know, that's probably an oversimplification, but the idea of gamifying health and activity is an interesting concept,

Davy (53:11):
Especially if it is looking at one particular thing. You've closed all your rings today, but you also paused to have a vape break 20 times.

Florence (53:19):
Well, exactly. And the wearable doesn't know that. And also does it put mental stress on the, to be constantly thinking about health, getting notifications going, you are in the workout zone, your heart rate's a bit elevated, all this sort of stuff. Is it increasing your health anxiety? And I think there is something to be said for ignorance is blitz. There's not in the wearable sphere, but in imaging there is a idea of an incidentaloma, which is an incidentally found asymptomatic tumour. It has an excellent name. And these are often found during routine MRIs. Say if you've got a headache and you're like, oh, let's just check it's not anything else, and you'll find these incidentalomas, the significance of these kind of growths in the brain is unknown and I don't even know if it's going to cause you any problems. But now that the person is aware of an incident loma, it has more confusion than clarity. In fact, the same could be kind of applied to wearable tech.

Davy (54:13):
Also, I would say the healthcare system as it currently is, is not set up to be using these wearable devices as their main way of getting health data. There might be difficulties in standardising the data from a bunch of different wearables into a way that healthcare providers can look at it and make sense of it. Certain manufacturers won't necessarily say what exact sensors they're using and how they're getting certain data. So how could a healthcare provider accurately analyse this? Is this too much to keep track of? Is this going to bombard healthcare systems with so much extraneous data that's not actually particularly necessary for monitoring patients just on a daily basis?

Florence (54:59):
Have they got the time?

Davy (55:02):
They're already leading busy lives!

Florence (55:02):
Also new things get introduced into the healthcare system, more training needs to get done, different hospitals or different aspects that had different attitudes towards training. And we'll get onto that also in our episode about AI using hospitals. But could there be you healthcare inequality introduced by some hospitals embracing tech from wearables and some not?

Davy (55:23):
Absolutely. And also who's responsible if the wearable tech leads to a misdiagnosis or a missed diagnosis? Is it the failing of the wearable or a failing of the healthcare provider? These are sort of thorny issues that we don't have answers to,

Florence (55:41):
And they are completely ubiquitous through all of tech applied to healthcare.

Davy (55:48):
So anyway, I hope you've enjoyed listening to this little walkthrough of what wearables are, and I hope this has given you some food for thought as to what's collecting your data, what it's doing with it, where your data's going. I hope you, I don't know any of you are one of those people who's absolutely obsessed with doing everything. The Apple Watch or Fitbit says. Maybe this gives you a chance to consider how much weight you want to put on that and if it's necessarily making you a happier, healthier person or not

Florence (56:20):
Release yourself from the shackle of the rings!

Davy (56:26):
So thank you so much for listening. We hope you found this interesting. And our next episode is going to be all about the potential use of AI in hospitals.

(56:41):
Thank you very much for listening to this episode of Day-to-Day Health. If you've got any questions or comments, please hear us on our Instagram at day-to-Day Health or email us at day-today health gmail. Also, this podcast was created as part of the Turing Rush Community Scholar Scheme, but all of these expressed, aren't those of the Allen Institute or Rush the show notes.



