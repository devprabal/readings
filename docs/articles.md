# Thoughts and exercpts from articles, magazine entries, blogposts  

## Mails between Tanenbaum and Linus

🔗 [Linus_vs_Tanenbaum](https://choices.cs.illinois.edu/cache/Linus_vs_Tanenbaum.html) 

Looks like Linux has dominated although the professor's ideas were good and futuristic, however, efforts weren't put in them. And overtime, linux is becoming more and more acceptable. Tanenbaum says about "free" software as in "source code", not as in "distribution cost". This is good of him. He says that majority of people are NOT on the internet (in those days, which is correct), so free source code is not reachable and distributers win. However, look how things have changed! Linus says that he would not have started the project if the GNU Hurd was ready. Look, it is still not ready. Oh and I read about plan 9. Another revolutionary OS? Tanenbaum says that there should be one authority over a software. Well, that's not the case today. There are many open source projects which exist because of "collaboration" and not because of one-single person controlling over it. Well, yes, in those days, collaboration would have been tough (as Linus says that too). But Tanenbaum being a "professor" in CS, could have speculated drastic changes in internet and technology making things accessible to vast audience. Then would he have continued adding more features to MINIX? It is clear that who won and who lost. However, the concept of microkernel is pretty good too if there would have been a good-enough-widely-used kernel like linux for it.

???+ quote "Linus"

    If you write programs for linux today, you shouldn't have too many surprises when you just recompile them for Hurd in the 21st century.

## Hyperbolic discounting: Why you make terrible life choices

🔗 [Hyperbolic discounting: Why you make terrible life choices](https://medium.com/behavior-design/hyperbolic-discounting-aefb7acec46e)

???+ quote "Lakshmi Mani"

    people choose smaller, immediate rewards rather than larger, later rewards — and this occurs more when the delay is closer to the present than the future.

    When you procrastinate, you opt for the instant gratification of enjoying yourself rather than the ==future reward of accomplishing the things you set out to do==.

    Our brains were never wired to be truly rational, because there is way too much information in the world for us to process. So we evolved to selectively process information to make decisions quickly.

    A caveman did not have to contend with such complex choices as we do today. Caveman Lakshmi never had to choose between eating a pig today vs investing it in a pig 401K that yields 4X returns in the future. Under harsher living conditions, we didn’t know if we would survive till the end of the day — so we evolved to choose the immediate things that helped us survive.

    It’s easy to assume that future you is boundless with energy, drive and motivation.

    ==Precommitment is a way to to lock future you into decisions, now. Make it hard for your future self to back out.==

    By ==breaking down big goals into smaller tasks==, your reward comes after the completion of each chunk. 

## Retrofitting Temporal Memory Safety on C++

🔗 [Retrofitting Temporal Memory Safety on C++](https://security.googleblog.com/2022/05/retrofitting-temporal-memory-safety-on-c.html?m=1)

???+ quote "excerpts"

    Temporal memory safety refers to the problem of guaranteeing that memory is always accessed with the most up to date information of its structure, its type.

    Chrome [...] the ==majority of high-severity security bugs are UAF (use after free) issues==

    The basic idea is to put explicitly freed memory into quarantine and only make it available when a certain safety condition is reached.

    MTE (Memory Tagging Extension) [...] Every 16 bytes of memory are assigned a 4-bit tag. Pointers are also assigned a 4-bit tag. The allocator is responsible for returning a pointer with the same tag as the allocated memory.

I also watched this [CppCon 2018 video](https://www.youtube.com/watch?v=lLEcbXidK2o&list=FL4fz1A6Cm4hVqscjEN9UQuw&index=2) on MTE.

## Hundred Rabbits: data storage

🔗 [data storage](https://100r.co/site/off_the_grid.html#data_storage)

???+ quote "excerpts"

    [... cloud storage] This method doesn’t eliminate physical storage as data can’t be synced to the cloud without a connection.  
    
    [...] country politics have made it so that Google restricts access to some of its business services in certain countries or regions, such as China, Crimea, Cuba, Iran, Sudan, and Syria. Whatever data you have stored with Google Drive, ==if traveling to any of these countries will not be accessible.== As conflicts arise, more countries can end up on that list.

I have taken for granted that an internet connection is a ubiquitous resource such that it is like water and none of my devices can function (for my work) without it. My data is continuously in sync across services / cloud / devices with never an "*offline-first*" approach. I should start to change this mindset and workflow. 

Apart from this, the [100 rabbits website](https://100r.co/site/home.html) details MANY other ways to achieve sustainability while still being able to use computers for what they do best. They highlight workflows / softwares / hardwares / lifestyles / etc. that can be more resilient and less dependent. 

I should visit this website regularly to keep on reading more articles / practices from them.  

## A Brief History & Ethos of the Digital Garden

🔗 [Maggie Appleton's essay on digital gardening](https://maggieappleton.com/garden-history)

??? quote "Maggie Appleton"

    [...] these sites act more like free form, ==work-in-progress wikis==. A garden is a collection of ==evolving ideas== [...] ==linked through contextual associations==. [...] ==half-finished== thoughts that ==will grow== and evolve over time. 

    Language [...] we expand it when our current vocabulary fails to capture what we're observing, or have a particular desire for how we'd like the future to unfold. Naming is a political act as much as a poetic one.

    The conversational feed design of [...][streams] is fleeting – they're only concerned with self-assertive immediate thoughts that rush by us in a few moments. [...]  only surface the Zeitgeisty ideas of the last 24 hours. [...] not designed to accumulate knowledge, connect disparate information, or mature over time. 

    Many of the people who jumped on the early digital gardening bandwagon were part of communities like [...] Followers of Tiago Forte's Building a Second Brain [...] People rallying around the Learn in Public ethos.

    Any kind of novel experimentation with the web requires knowing a ==non-trivial== amount of HTML, CSS, and JS. [...] Developers took to the idea because they already had the technical ability [...]

    The overwhelming lesson of the Web 2.0 social media age is that dumping millions of people together into decontextualised social spaces is a shit show. Devoid of any established social norms and abstracted from our specific cultural identities [...] We know nothing of their lives, backgrounds, or belief systems, and have to assume the worst. [...][gardens] They're the higher-fidelity version, complete with quirks, contradictions, and complexity.

I have to recommend this eassy. Every line in this is a line which is either a well-researched fact, a meticulous process, or a food for thought. The illustrations therein make it extremely enagaging (and the selection of those calm color tone of the entire garden. Ah! beautiful).

## The Expanding Dark Forest and Generative AI

🔗 [Maggie Appleton's essay on gen ai and LLMs](https://maggieappleton.com/ai-dark-forest)

??? quote "Maggie Appleton"

    Proving you're a human on a web flooded with generative AI content

    These new models are poised to flood the web with generic, generated content.

    We've already become skilled at sifting through unhelpful piles of “optimised content” designed to gather clicks and advertising impressions.

    How would you prove you're not a language model generating predictive text? 

    they (LLMs) do not have access to the same shared reality we do. They do not have embodied experiences, and ==cannot sense the world as we can sense it; they don't have vision, sound, taste, or touch==. They cannot feel emotion or tightly hold a coherent set of values. They are not part of cultures, communities, or histories. [...] Language models ==can decently mimic== this style of writing but most don't without extensive prompt engineering. They stick to generics. They leave out details. 

    Language models regurgitate text from across the web, which some humans read and recycle into "original creations," which then become fodder to train other language models, and around and around we go recycling generic ideas and arguments and tropes and ways of thinking. Hard exiting out of this cycle requires ==coming up with unquestionably original thoughts and theories==. 

    What we have left to play with is la parole. No language model will be able to keep up with the pace of weird internet ==lingo and memes==. I expect we'll lean into this. Using neologisms, jargon, euphemistic emoji, unusual phrases, ingroup dialects, and memes-of-the-moment will help signal your humanity.

    [...] offline-first future. We might see increased fetishisation of ==anti-screen culture==

She explores some possible ways to distinguish a bot from human when talking on the web filled with gen ai content.

## Interview: He conquers who conquers himself |  Adam Peaty

🔗 Men's Health Magazine July 2024 edition

??? quote "Adam Peaty to MH's interviewer Gordon Smart"

    'The answers can't be found in a nightclub, or some of the stuff that I'd been doing. It had to be found in true accountability, tough and deep conversations with people around me. It requires so much maturity to ==face yourself== in the mirror ==and admit that your behaviour is not acceptable.'==

    'I was within a hair of giving it all up, he says. What was going back for? Pride? It took a while to find the answer. But wanted to teach [my son] George and any other children I have in future that ==you don't give up when things get hard== or the world feels like it's against you. ==You give up when the time is right.== I can take losses, but I couldn't take regret. Regret whould eat any man inside out.

    The pool can be a very lonely place, he says. 'You're doing 12,000m a day, plus gym, plus nutrition, plus everything else in your life. I was a father, a partner, a business manager - trying to manage my own future at the same time.'

    he repeats a mantra about being =='better today than you were yesterday'==. That's a Herculean task for a man swimming sub-58s. So how exactly does he go about chasing those marginal gains? 'I've had to ==find different ways to attack the same thing==,' he explains. 'It's not about faster or better, it's actually more peaceful than that. [...] I used to be an emotional swimmer with a process-driven way of performing. Now, I'm ==process driven==, ==but== I can ==add emotion to the structure==. 'It changes when you get older as an athlete. I think I've mastered ==the art of staying present==. [...] Of course you're not going to be happy all the time, especially when your heart rate is at 200bpm and you're bleeding in the gym. But you can be at peace in those moments.'

    'My standards are so high because ==I take it to a place not many people have gone==. That mentality has got me medals, but it has cost me,'

    'I've got 34 international gold medals, 50-plus overall. The rest, I've given away. I'm not fussed by the material. ==I can relive any race because I remember them==. The memories are with me forever.' '"Medals are the coldest thing you wear because in pursuit of greatness, you'll destroy relationships." People will tell you there's a choice, but there is no choice; it's win or lose. I've got to be willing to go all in for a victory. Most of the time ==you have to be selfish to achieve the goals== I'm striving for.'

    Of course, I love material possessions, but I don't let them define who I am. Just because you have a nice watch, it doesn't make you a nice person. 'I want to be remembered as someone who was relentless in the pursuit of human excellence. ==Legacy isn't something I can decide for myself. The world decides my legacy==, it depends on how good I've been in the pool.'

    I've always relied on swimming to teach me valuable lessons, to humble me.

    I've got so much stamina and endurance in my body and that doesn't go away overnight. 'I don't like quiet, I like the chaos. I like having a busy brain. I've done this 1,000 times, ==I just need to flick a switch to engage that experience.=='

## Treat your to-read pile like a river, not a bucket

🔗 [blogpost by Oliver Burkeman](https://www.oliverburkeman.com/river)

??? quote "Oliver Burkeman"

    In a world of effectively infinite information, the better you get at ==sifting the wheat from the chaff, the more you end up crushed beneath a never-ending avalanche of wheat==.

    My challenge, information-wise, ==isn't about finding a needle in a haystack==. It's that I'm confronted on a daily basis, in Carr's words, by =="haystack-sized piles of needles.== 
    
    [...] "too many needles" [...] attempt to ==divide our finite time and attention among too many things that all have a legitimate claim on them==.
    
    To return to information overload: this means treating your =="to read" pile like a river (a stream that flows past you, and from which you pluck a few choice items, here and there) instead of a bucket (which demands that you empty it)==. After all, you presumably don't feel overwhelmed by all the unread books in the British Library – and not because there aren't an overwhelming number of them, but because it never occurred to you that it might be your job to get through them all.
