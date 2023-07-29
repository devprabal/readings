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
