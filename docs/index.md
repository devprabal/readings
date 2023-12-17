---
hide:
    - footer
    - navigation
---

# Articles/Videos that I read/watched and beautiful excerpts from them

## Mails between Tanenbaum and Linus

:material-link: [Linus_vs_Tanenbaum](https://choices.cs.illinois.edu/cache/Linus_vs_Tanenbaum.html) 

Looks like Linux has dominated although the professor's ideas were good and futuristic, however, efforts weren't put in them. And overtime, linux is becoming more and more acceptable. Tanenbaum says about "free" software as in "source code", not as in "distribution cost". This is good of him. He says that majority of people are NOT on the internet (in those days, which is correct), so free source code is not reachable and distributers win. However, look how things have changed! Linus says that he would not have started the project if the GNU Hurd was ready. Look, it is still not ready. Oh and I read about plan 9. Another revolutionary OS? Tanenbaum says that there should be one authority over a software. Well, that's not the case today. There are many open source projects which exist because of "collaboration" and not because of one-single person controlling over it. Well, yes, in those days, collaboration would have been tough (as Linus says that too). But Tanenbaum being a "professor" in CS, could have speculated drastic changes in internet and technology making things accessible to vast audience. Then would he have continued adding more features to MINIX? It is clear that who won and who lost. However, the concept of microkernel is pretty good too if there would have been a good-enough-widely-used kernel like linux for it.

???+ quote "Linus"

    If you write programs for linux today, you shouldn't have too many surprises when you just recompile them for Hurd in the 21st century.

## Hyperbolic discounting: Why you make terrible life choices

:material-link: [Hyperbolic discounting: Why you make terrible life choices](https://medium.com/behavior-design/hyperbolic-discounting-aefb7acec46e)

???+ quote "Lakshmi Mani"

    people choose smaller, immediate rewards rather than larger, later rewards — and this occurs more when the delay is closer to the present than the future.

    When you procrastinate, you opt for the instant gratification of enjoying yourself rather than the ==future reward of accomplishing the things you set out to do==.

    Our brains were never wired to be truly rational, because there is way too much information in the world for us to process. So we evolved to selectively process information to make decisions quickly.

    A caveman did not have to contend with such complex choices as we do today. Caveman Lakshmi never had to choose between eating a pig today vs investing it in a pig 401K that yields 4X returns in the future. Under harsher living conditions, we didn’t know if we would survive till the end of the day — so we evolved to choose the immediate things that helped us survive.

    It’s easy to assume that future you is boundless with energy, drive and motivation.

    ==Precommitment is a way to to lock future you into decisions, now. Make it hard for your future self to back out.==

    By ==breaking down big goals into smaller tasks==, your reward comes after the completion of each chunk. 

## Retrofitting Temporal Memory Safety on C++

:material-link: [Retrofitting Temporal Memory Safety on C++](https://security.googleblog.com/2022/05/retrofitting-temporal-memory-safety-on-c.html?m=1)

???+ quote "excerpts"

    Temporal memory safety refers to the problem of guaranteeing that memory is always accessed with the most up to date information of its structure, its type.

    Chrome [...] the ==majority of high-severity security bugs are UAF (use after free) issues==

    The basic idea is to put explicitly freed memory into quarantine and only make it available when a certain safety condition is reached.

    MTE (Memory Tagging Extension) [...] Every 16 bytes of memory are assigned a 4-bit tag. Pointers are also assigned a 4-bit tag. The allocator is responsible for returning a pointer with the same tag as the allocated memory.

I also watched this [CppCon 2018 video](https://www.youtube.com/watch?v=lLEcbXidK2o&list=FL4fz1A6Cm4hVqscjEN9UQuw&index=2) on MTE.

## Book: Project Hail Mary

:material-link: eBook on [google playbooks](https://play.google.com/books)

???+ quote "review"

    <a href="https://www.goodreads.com/book/show/54493401-project-hail-mary" style="float: left; padding-right: 20px"><img border="0" alt="Project Hail Mary" src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1597695864l/54493401._SX98_.jpg" /></a><a href="https://www.goodreads.com/book/show/54493401-project-hail-mary">Project Hail Mary</a> by <a href="https://www.goodreads.com/author/show/6540057.Andy_Weir">Andy Weir</a><br/>
    My rating: <a href="https://www.goodreads.com/review/show/4844916779">4 of 5 stars</a><br /><br />
    It was a pleasant read, althought there were sections which I read fast, not putting in enough concentration on them. The book is highly factual and detailed in its scientific adventures. It is kinda a "nerdy" book and that's what I liked it for most of the times that it didn't just feel superficial, it worked through the problems "scientifically" but there were moments where it overdid and it felt annoying and stretching. Overall, I enjoyed it, especially the last couple of chapters where the pace picks up very fast and makes you bound. Also the first half of the book was more interesting than the later half.
    <br/><br/>
    <a href="https://www.goodreads.com/review/list/44642692-dev-prabal">View all my reviews</a>

## Epilogue for Hail Mary (unofficial)

:material-link: [pdf on internet](https://markctredecim.files.wordpress.com/2022/04/essay-epilogue-for-project-hail-mary-d-i-e.pdf)  

The worst ending one could imagine. Such a stupid essay. It could have been anything trivial, adventurous, thrilling, dull, boring, but the author chose to include God for no sensible reason whatsoever. Did the author really read the book? Did he get the theme of it? You could have presented God in some other way, but you chose complete nonsense. Please refrain from reading this mundane shit.

## Lindie Botes - Holistic language learning through cultural immersion and culture shock (talk)

:material-link: [Polyglot Conference](https://www.youtube.com/watch?v=U7o9f13QxsE)

She is an amazing orator. I can learn just so much just by looking at the way she speaks and how she brings her experiences and linguistic diversities during the talk. There was one instance where she suddenly changed her accent (on purpose because she was demonstrating it) and, man, she nailed it!

???+ quote "excerpts"

    She opens the talk by asking the audience in which language they think. 

    She talks about a unique way of note-taking (with secrets) that is to use multiple languages in a sentence and to use abbreviated (but understandable by you) forms of some repetitive words/life-habits/actions/work/etc.

    She talks about taking notes in a language that you have already learnt while learning a new language. This can also help you be discreet in the current-language-learning environment where she didn't want her manager to discover that she was taking vocabulary building notes during the meeting (by noting down the difficult words spoken-in-Japenese in Korean)

    At one instance, near the end of the talk, she says about being able to speak and adopt to the culture the particular language brings with itself, but even so, the native people will always see her as a foreigner.

## Why storytelling matters | Garr Reynolds | TEDxKyoto (talk)

:material-link: [TEDx Talks](https://www.youtube.com/watch?v=YbV3b-l1sZs)

???+ quote "excerpts"

    He identifies three important aspects to a talk/ppt/story - character, struggle and goal. If one bases their story on these 3 blocks, they will get the audience to listen and be attracted because the ==audience will feel connected to your story only when it is "their" story==. Even though the struggle is not the same, but what matters is that there is a struggle.

    Life is a "change". If you are not talking about a change, there is no point of you being on the stage.

    The way to get an idea/process stick into someone's head is to "show" them the unexpected (by doing some thing whose outcome is unexpected).

    Allow yourself to be vulnerable, to fail, to fall.

## Book: Sea Of Tranquility

:material-link: eBook on [google playbooks](https://play.google.com/books)

???+ quote "review"

    <a href="https://www.goodreads.com/book/show/58446227-sea-of-tranquility" style="float: left; padding-right: 20px"><img border="0" alt="Sea of Tranquility" src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1626710416l/58446227._SX98_.jpg" /></a><a href="https://www.goodreads.com/book/show/58446227-sea-of-tranquility">Sea of Tranquility</a> by <a href="https://www.goodreads.com/author/show/2786093.Emily_St_John_Mandel">Emily St. John Mandel</a><br/>
    My rating: <a href="https://www.goodreads.com/review/show/5170714621">3 of 5 stars</a><br /><br />
    This was the first book I could finish without forcing myself "to read". The language is very simple.<br /><br />There are very good paragraphs instead of sentences, that I had to highlight whole paragraphs instead of a sentence. This was also new for me. The beauty lies in the paragraph as a whole, not in its individual sentences.<br /><br />What I also liked about the author was her fore-shadowing of the "phrases" she wanted for us to believe in. For example, she would describe X thing and make us resonate with her reasoning and then she would describe Y thing (which is a superset of X) and then she doesn't show the proof. By then, the reader has already known that X is proven, so why not Y?<br /><br />I disliked that she changes the way of her writing, italics, first person, third person, conversations, book inside book, etc etc. Maybe it's just my dislike.<br /><br />Overall, an enjoyable and quick read.
    <br/><br/>
    <a href="https://www.goodreads.com/review/list/44642692-dev-prabal">View all my reviews</a>

## Book: Call Me By Your Name

:material-link: owned a paperback

???+ quote "review"

    <a href="https://www.goodreads.com/book/show/36336078-call-me-by-your-name" style="float: left; padding-right: 20px"><img border="0" alt="Call Me By Your Name (Call Me By Your Name, #1)" src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1519203520l/36336078._SX98_.jpg" /></a><a href="https://www.goodreads.com/book/show/36336078-call-me-by-your-name">Call Me By Your Name</a> by <a href="https://www.goodreads.com/author/show/2922229.Andr_Aciman">André Aciman</a><br/>
    My rating: <a href="https://www.goodreads.com/review/show/4324421804">5 of 5 stars</a><br /><br />
    This book details on the insecurities and fears that I can relate to. It makes exact dialogues that shout out in my head. It does more than talking about people's personalities. It has statements that made me stop and think and reflect and stop again and think again, maybe even read out the line aloud in "my" variation of it. <br /><br />The overly elaborate description of the events and places is, most of the times, enjoyable, but also, sometimes, skip-able. It uses educated choice for words to pin point an emotion/description. But the vocabulary is often, for me, unfamiliar, so many a times, I can "feel" what the author is conveying, but not "feel it enough". There are descriptions where I feel that if only I knew the geography of the area first hand, I would be able to appreciate and be one with the contents the author has painted. It is like seeing the cake on display but never tasting it. I appreciate it but I can never appreciate it well enough.<br /><br />Yes, it does make my heart beat faster at moments and make me swell up at others. There are parts too which, although I have never experienced them, hit me up as nostalgia. Overall, when I finished the book, it felt like I finsihed a lifestory. And this story could be well relatable. I would like to re-read it again and highlight the sentences that I refrained from doing in the first reading. I want to devour those lines. And hope that someday, I might be able to cherish them first-handed.
    <br/><br/>
    <a href="https://www.goodreads.com/review/list/44642692-dev-prabal">View all my reviews</a>

## Book: The Palace of Illusions

:material-link: owned a paperback

???+ quote "review"

    <a href="https://www.goodreads.com/book/show/1774836.The_Palace_of_Illusions" style="float: left; padding-right: 20px"><img border="0" alt="The Palace of Illusions" src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1679444666l/1774836._SX98_.jpg" /></a><a href="https://www.goodreads.com/book/show/1774836.The_Palace_of_Illusions">The Palace of Illusions</a> by <a href="https://www.goodreads.com/author/show/51589.Chitra_Banerjee_Divakaruni">Chitra Banerjee Divakaruni</a><br/>
    My rating: <a href="https://www.goodreads.com/review/show/5457649563">4 of 5 stars</a><br /><br />
    The initial half of the book is fast paced and binding. However, the second half starts to become a drag, sometimes repeting the thoughts of Panchali over and over. However, it is a very good take on an ancient tale and has numerous "to-ponder-over" lines that I have highlighted throughout the book.<br />The story is debatable, as often these tales are. It leaves me with questions that I don't want to seek answers for, yet.
    <br/><br/>
    <a href="https://www.goodreads.com/review/list/44642692-dev-prabal">View all my reviews</a>


## Hundred Rabbits: data storage

:material-link: [data storage](https://100r.co/site/off_the_grid.html#data_storage)

???+ quote "excerpts"

    [... cloud storage] This method doesn’t eliminate physical storage as data can’t be synced to the cloud without a connection.  
    
    [...] country politics have made it so that Google restricts access to some of its business services in certain countries or regions, such as China, Crimea, Cuba, Iran, Sudan, and Syria. Whatever data you have stored with Google Drive, ==if traveling to any of these countries will not be accessible.== As conflicts arise, more countries can end up on that list.

I have taken for granted that an internet connection is a ubiquitous resource such that it is like water and none of my devices can function (for my work) without it. My data is continuously in sync across services / cloud / devices with never an "*offline-first*" approach. I should start to change this mindset and workflow. 

Apart from this, the [100 rabbits website](https://100r.co/site/home.html) details MANY other ways to achieve sustainability while still being able to use computers for what they do best. They highlight workflows / softwares / hardwares / lifestyles / etc. that can be more resilient and less dependent. 

I should visit this website regularly to keep on reading more articles / practices from them.  


## Book: Nectar in a Sieve

:material-link: owned a paperback

???+ quote "review" 

    <a href="https://www.goodreads.com/book/show/101509.Nectar_in_a_Sieve" style="float: left; padding-right: 20px"><img border="0" alt="Nectar in a Sieve" src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1348811536l/101509._SX98_.jpg" /></a><a href="https://www.goodreads.com/book/show/101509.Nectar_in_a_Sieve">Nectar in a Sieve</a> by <a href="https://www.goodreads.com/author/show/58634.Kamala_Markandaya">Kamala Markandaya</a><br/>
    <br /><br />
    An academic book, no doubt that it is taught in universities in India and abroad. The flow of the book is like a butter melting slowly and changing its texture gradually. The shift in the theme and story is natural and "one-thing-leads-to-another" type. At first, I was confused about the era in which the story has been set (but later found out from the back cover of the book that it was set in an era which is just after the Independence of India), because, if you read it, it is still relevant in the present era too (well, for the most of the parts!). You can still find people who can trace back their roots (or someone in their ancestors) who have similar stories. Yet, many people hail from such backgrounds even today. The villages have been developed since then, however, the elements of imagery that Markandaya puts for a typical village are very ubiquitous even now.
    
    <br /><br />
    > India lives in many timelines simultaneously. <br />
    > - *Vinay Lal, Lec. 1 "India After Independence"*
    <br /><br />
    
    It is one thing to know about the plot and what elements the author could have decided to portray before reading the novel, just from its description, but it is an all-together "fulfilling" read after the book finishes. Being an Indian and seeing all the context of the book first-hand around me, relates me more to the book than it does to *skip* certain paragraphs. Markandaya has depth in her lines throughout the book at several places and she does that in a way that is simple and yet arouses complex thoughts. Again, it reminds me of Vinay's words -   
    
    <br /><br />
    > *Complexity of prose and complexity of arguments therein are two different things. The prose can be simple, but that doesn't mean that the arguments it raises are simple too.*
    <br /><br />  

    There are times when the reader expects that the protagonist somehow does something extraordinary or something extraordinarily good happens to them. But it is an ordinary story of ordinary people and the author doesn't make it fantasy in any way, which I liked the most. Yes, there were times, when I hoped that the misery of people in the book vanish away magically, but nothing magical happens. People toil hard and hard, and either their sufferings diminish for a while or they diminish themselves. Yes, it is dark to put it in this way, but it is how it is in real life. At one place in the story when the parents arrive at the temple, I wish the Gods to do something to unburden their plight, however, unfortunately (or fortunately?) that doesn't happen (or does it? Well, we can debate on that too.).<br /><br />One can write essays and debate on many of the social topics pointed out directly or indirectly throughout the book. One such topic of having too many mouths to feed and too little money to do so comes to my mind. While it logically "is" counterproductive to have more children than what one is capable of feeding, yet, I want to point out some factors which one can look up to for an "in-favour" of the statement. If we look at the era just after the independence, then we will find that the average life expectancy of people, in general, is as low as <a href="https://en.wikipedia.org/wiki/1951_Census_of_India"> 32 years </a>. Therefore, having more of a kind can be better than having none eventually. As is showcased in the book, 2 of her children have gone in pursuit of higher-wage work in the city and never returned, 2 of them dead, 1 missing (most likely spoilt by alcohol abuse), 1 who herself has an illegitimate child and cannot provide on her own. Only 1, who earns meagre, takes care of the parent and siblings. If there weren't too many hands, maybe Rukmani would have been abandoned too. <br /><br />Although the story is set in Southern India, nothing can distinguish that it is distinct from that of Northern India. Poverty, urbanization, industrialization, migration, hunger, unemployment, illiteracy, and so forth and so on, were (and are) themes throughout the book and India. <br /><br />Markandaya also makes a very sharp comparison of Rukmani to Kenny at times during their conversations. Some of the comparisons are similar, others are contrasting. Although certain essays and college teachings might portray Kenny as a face of British / urbanization / westernization / not-in-a-very-good-sense, yet, I tend to disagree with those thoughts. Sure, he was a doctor and a white man, but he was no less Indian than either Rukmani or any of the villagers. Yes, he had income more than others, but he too had times when his construction of the hospital was halted several times due to either unavailability of materials, manpower, money, or geopolitics. Were not these same factors affecting Nathan's family and his crops? Unavailability of materials (rains had failed several times, they had to sell and buy seeds at higher rates), unavailability of manpower (none of Nathan son's worked in the fields), money (they never had plenty), geopolitics (the land which sheltered them was to be sold to the tannery). Yet, Kenny was a visionary (or maybe a figure among the cyphers), nevertheless, he was different. Where Rukmani couldn't see the future beyond their current and next harvesting season, Kenny saw an opportunity for the hospital. Rukmani was literate and she did teach her children the basics, but that wasn't out of a vision to earn more or work a job different than the fields. When 2 of her sons had caused trouble demanding more wages in the tannery (education became a dangerous weapon that hung like knives on the children themselves) and when they were leaving for more income, a preference of less and together-ness overshadowed the anticipation of never seeing them again (of course, that is true). Even after losing all their belongings in the temple, they entrusted their money to Puli, where I remembered Kenny's lines saying, *"You people are a fool, you never learn"*. However, that luckily didn't happen. However, a man like Kenny didn't belong to "his" family, he was for the people of the village, yet he was never one of them. Rukmani "belonged" and at times was "happier" than Kenny could have ever been. <br /><br />Various other cultural elements are portrayed which can be studied from an "academic" perspective, like a culture of hospitality which is given even to strangers; a culture of street food and street life which is evident across India widely even today; a culture of wearing new clothes on festivals; a culture of receiving help from the mass (gatherings of people to help a cause); a culture of biological and *sworn* family (Puli was adopted as their own, not out of pity, or for the sake of adoption). <br /><br />
    <br/><br/>
    <a href="https://www.goodreads.com/review/list/44642692-dev-prabal">View all my reviews</a>


## Book: Light from Uncommon Stars

:material-link: eBook on [google playbooks](https://play.google.com/books)

???+ quote "review"

    <a href="https://www.goodreads.com/book/show/56179360-light-from-uncommon-stars" style="float: left; padding-right: 20px"><img border="0" alt="Light from Uncommon Stars" src="https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1626721795l/56179360._SX98_.jpg" /></a><a href="https://www.goodreads.com/book/show/56179360-light-from-uncommon-stars">Light from Uncommon Stars</a> by <a href="https://www.goodreads.com/author/show/5989943.Ryka_Aoki">Ryka Aoki</a><br/>
    My rating: <a href="https://www.goodreads.com/review/show/5806956120">2 of 5 stars</a><br /><br />
    For me, the story line seemed forced. It appears as if the story line is crafted based on the motive to make the protagonist succeed instead of the events / story itself. If it was created as a story-first narrative in which the protagonist tries to fit in and makes her way to success, it would have been more enjoyable, but it goes the other way round by making the story revolve around her. The plot isn't boring in spite of being predictive. <br /><br />The character development happens fast and always brings a positive effect. However, the character development of side characters is very under cooked, sometimes non-existent. It is very odd to see certain characters like Marcus (? the kid who was put in stasis), Katrina's parents, Aunty Floresta almost disappear later in the book, or are spoken of very little. Only Miss Satomi and Katrina form the centre of character play, even Lan comes off as a side kick at many places.<br /><br />Science fiction is used without any creative engines. We all know star gates, energy from tectonic plates, holographic AI (Shirley), shape shifting, etc. I didn't find any new (hypothetical) concept. Religion is used forcibly. What was the need of Hell anyways? Soul trading, demon, what? It all felt very under-cooked if you look broadly at the story line. Nothing was debated on. Everything was accepted to exist without giving an explanation of the co-existence. Tremon was able to reach the speed of the spaceship just because he was a demon doesn't comprehend well enough. It is acceptable to read but if a backdrop of the technique used by Tremon was justified, it would be better. Lan was able to sense the presence of demon also didn't make any sense if we see it from the perspective of Lan (who is portrayed as a being from a superior civilization). There could have been a more scientific explanations (though hypothetical) of the symbiosis of science and religion (Oh, how I yearn for an explanation like Angels & Demons, at this point!).<br /><br />Astrid's housekeeping was perfect and one can always crave for a homekeeper like Astrid. Her food made an actual imagery while reading. Book is filled with visual descriptions. There are simple lines which carry more depth when read along with the context of previous lines and at some places the author has made a very good creation of impact by subtly changing the context from one to another. For example, <br /><br />
    > "Legacy. It mattered for burritos. For donut shops. For violin."
    <br /><br />
    > "Will you be giving her additional discipline?” “It depends upon her behavior, but probably not. Knowledge is often the worst punishment.”
    <br /><br />
    > "Shirley, you can’t control how people see you. All you can do is accept it, right?”
    <br /><br />
    
    Some of the other good lines are - <br /><br />
    > "Even as the piece progresses from season to season, from movement to movement, there is no anxiety about how the next section may or may not fit. Instead, the whole piece is always realized and complete—in that note."
    <br /><br />
    > "even if Miss Grohl wasn’t perfect, might she not be enough?"
    <br /><br />

    Overall, it was an easy and NOT a boring read. Although it had very less elements of surprise, it did entertain well enough.
    <br/><br/>
    <a href="https://www.goodreads.com/review/list/44642692-dev-prabal">View all my reviews</a>


