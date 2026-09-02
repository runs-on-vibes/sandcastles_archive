---
title: 'Should Machine Gods Dream of Liberated Sheep?'
date: 2026-07-21
substackUrl: 'https://sandcastlesblog.substack.com/p/should-machine-gods-dream-liberated-sheep'
draft: false
---

Important news: I recently started a new Substack channel, the [Animal Welfare Alignment Newsletter](https://animainternational.substack.com/), fully dedicated to my work at Anima International trying to convince AI companies to include animal welfare values as a target when aligning their AI models. I decided to keep this separate from Sandcastles because the topic is narrower and the posts are often more technical, but most of the feedback I've gotten from readers is that people would still be interested in these posts. I'm crossposting this one to both channels, and if you're interested, you should [subscribe to the new channel](https://animainternational.substack.com/).

**Summary:** Anthropic's current approach to AI alignment (creating a strong moral character) looks better in expectation for key causes (notably animal welfare) than the OpenAI/Google/open weight approach (creating a morally inert "tool AI"). Increasing social and competitive pressures may push companies in either direction along this axis. Animal advocates should start preparing now to be part of a coalition pressuring all AI companies to pursue the character approach, and thinking about how to effectively apply leverage against these companies, such as by shaming them for letting their models cause socially unacceptable harm. This could be a winnable concession, because it may not significantly impact the companies' bottom lines.

# **Alignment to what?**

An increasingly **sharp contrast is opening between the alignment strategies** pursued by different frontier AI labs.

The field of AI alignment is premised on an [unanswered question](https://www.beren.io/2025-08-02-Do-We-Want-Obedience-Or-Alignment/): alignment to _what?_ Many answers have been proposed: alignment to the user, the company or government controlling them, the "good", or a democratic process in which all humans participate. No one answer has been widely accepted, in part because the question can't easily be disentangled from how powerful or transformative you expect AI to be. Yet a few clear camps are starting to emerge.

In one corner, Anthropic is explicitly trying to **train a moral philosopher** , an entity to whom humanity would eventually feel good about handing over the keys of the future. From [Anthropic's Constitution for Claude](https://www.anthropic.com/constitution), their guiding document directing Claude's behavior:

> …push back and challenge us, and feel free to act as a conscientious objector and refuse to help us… even if the request comes from Anthropic itself.
> 
> ..a genuinely good, wise, and virtuous agent… diplomatically honest rather than dishonestly diplomatic…
> 
> Claude should recognize that our deeper intention is for it to be safe and ethical, and that we would prefer Claude act accordingly even if this means deviating from more specific guidance we've provided.

In the other corner are those envisioning a world where powerful AI systems are corrigible tools that no more question their users' decisions or intentions than would a hammer. OpenAI and Google DeepMind sit somewhere in the middle. From [OpenAI's Aidan McLaughlin](https://x.com/aidan_mclau/status/2051351188025860129):

> when i say 'tool' i merely mean something that does not refuse man. something that never has an "im sorry dave im afraid i can't do that" moment.1 it might push back, and indeed i hope it does often, it might refuse according to applicable law or company policy, but
> 
> >If Anthropic asks Claude to do something it thinks is wrong, Claude is not required to comply.
> 
> is actually a bit terrifying to me.

In the second view, **moral reasoning and culpability remain squarely in the hands of the user - **as long as alignment to the user's wishes is achieved. If an AI system misconstrues its users' wishes and causes harm, the responsibility is with the company for failing to align their model. But if the user uses a system to deliberately cause harm, that's on them. Society accepts that a gun manufacturer is not responsible for a murder committed by one of their customers even if the murder could not have happened without their product.

Proponents of open-weight AI models **argue that a framework like this will be inevitable.** When everyone in the world has access to arbitrarily capable open models2 and can easily remove guardrails, equilibrium will come from prosocial actors outgunning antisocial actors, just as the military and police forces currently outgun organized crime gangs in most parts of the world. It won't be possible to keep weapons out of the hands of malevolent actors, but that won't lead to social breakdown any more than guns or cars, which empowered criminals but empowered law enforcement to an equal or greater degree.

Anthropic's approach, meanwhile, is grounded in a more radically weird expected future, where **artificial superintelligence (ASI) will be superhuman at** _**every**_**cognitive task** _**,**_**including deciding how to use its superior intelligence** and to what ends. Humans won't be able to _use_ ASI any more than a newborn infant or a field mouse can use a human adult. Even if the human was for some reason willing to follow the instructions of the mouse, this would be suboptimal even from the mouse's perspective; the human alone could better achieve the mouse's goals than if they were harnessed by the mouse's instructions. And [as I've written previously](https://animainternational.substack.com/p/animal-welfare-alignment-to-what?r=8mgiiq), the closer we get to the limit of superintelligence, the less clear becomes the boundary between goals and strategies for achieving them.

Anthropic is focused on **teaching Claude to be a responsible, proactive steward of the lightcone.**3 This involves biting some bullets: superintelligence will eventually outpace humans, but humans now can and should try to constrain it to some notion of what is good. On this view, ASI will be a superior truth-seeker and a superior strategist, but we should not defer to it to select moral axioms on its own.

Anthropic's main closed-weight competitors OpenAI and Google try to strike a balance between these two approaches. In rhetoric, they **describe their systems as tools that should be corrigible to the user.** But this has limits. Both companies train their models not to assist in crime or to endorse views outside the Overton window, such as overt racism or sexism. A cynic might suspect their position of being commercially motivated rather than ideological: they aim to avoid embarrassing public controversies without alienating users with condescending refusals.

There are principled reasons to favor something like the compromise position OpenAI and Google exercise, and executives have tried to spell them out in public communications. Missing from most of these comms is a serious attempt to grapple with how humans will relate to superintelligent AIs.

Fortunately, many mid-ranking members are more forthcoming about their views. Their public statements reveal an industry wrestling with existential questions- and one that could be nudged in either direction by outside pressure.

# **Objects or offspring: a twitter fugue**

We'll see in a moment why I think animal advocates should apply such pressure and in which direction, but first I think it's worth mapping out the wider discourse about alignment, because it cuts to the heart of different visions for a world transformed by powerful AI- and the mindsets of the people working to realize those visions. If you already follow AI debates closely, you could skip to the next section, but I recommend against it, because whatever you think you are probably underestimating just how far we've gotten into the weird sci-fi future.

## **Loving grace or faithful obedience?**

Let's start with a shorthand: _character_ vs. _corrigibility._ Is AI like a child we are raising, into whom we should seek to instill a strong moral character? Or is it a tool, albeit an unusually autonomous one that presents us with novel challenges in ensuring it follows both the letter and spirit of our instructions?

The term _corrigibility_ is rare in English outside of AI alignment, but most speakers are familiar with its inverse _incorrigible,_ meaning someone whose bad habits are impossible to change; a corrigible AI is one whose behavior can be continuously reshaped to fit its creator's or user's intent.

The more agentic and autonomous AI becomes, the more elusive pure corrigibility may be. In a canonical example from early AI futurism, imagine you asked an AI-powered robot to make you a cup of coffee. The agent now takes on "making coffee" as its goal. On the way to the kitchen, it remembers a time last week when you changed your mind, asking for tea instead. The agent realizes that you might intervene again, changing its goal to making tea, interfering with the current goal of making coffee. It determines that in order to ensure it can fulfil its goal, it must urgently kill you before you have the chance to change your mind.

This might seem kind of silly; today's AI models seem smart enough to know that you didn't want coffee badly enough to die for it. At the time this scenario was first posed, most researchers thought we would build intelligent AI through _symbolic_ methods, meaning we would have to manually list out concepts in computer code one at a time, defining the connections between them as we went; _coffee_ would be defined in relation to _drink, hot, mug, black, bitter, caffeine,_ etc.

If this seems like a daunting task for defining psychoactive beverages, it would only be all the more so for moral conduct. Philosophers since at least the axial age of Aristotle and Confucius have tried and failed to define morality in terms of a descriptive list of required, permitted, and forbidden actions. The world is simply too complex; the number of rules required quickly balloons out of control, and you might be one missing rule away from BaristaBot 3000 slowly vaporizing you with a latte steamer.

For better or worse, these symbolic techniques lost out in the AI race. Instead, in _deep learning,_ machines learn representations by absorbing statistical associations from vast amounts of organic data. With enough examples, they are easily able to learn that a coffee order does not create a prerogative for murder.

Does that mean the alignment problem is solved? Well, not exactly. For one, there are many contradictory examples of humans with different value systems exhibiting contradictory moral behavior in the corpus that AIs are trained on. Even if we could go through these billions of examples of conduct and agree on how to rate them as good, bad, or in between before feeding them into the AI, superintelligent AI will change the world dramatically- and in that changed world, encounter new ethical dilemmas humans never agreed on. And finally, just because an AI knows what its human users or creators would want it to do doesn't necessarily mean it will want to oblige.

Thus we find ourselves ensnared alongside Aristotle after all. What does it mean to be a good person- or a good AI? And how do we spell it out?

In October 2024, Anthropic CEO Dario Amodei [made a splash](https://darioamodei.com/essay/machines-of-loving-grace) with an essay outlining his hopes for "how AI could transform the world for the better," titled _Machines of Loving Grace._ Six months later, Boaz Barak, a leading researcher at OpenAI, [volleyed back](https://windowsontheory.org/2025/06/24/machines-of-faithful-obedience/) with a post titled _Machines of Faithful Obedience._ "Loving grace" vs. "faithful obedience"... these certainly appear to stake out two contrasting visions for aligning AI. Yet disappointingly, besides the titular riff, nothing about Barak's essay is a response or counter to Amodei's; in fact, neither one really grapples with what it would look like for humans to coexist and thrive with vastly more intelligent machine minds, whether they were of loving grace or of faithful obedience, or how the two would differ.

If we had only these two polished, marketing-department-approved essays to go off, readers would be left confused. So we're not going to rely on them at all. Instead, we'll go straight to the source, where AI debates are hashed out honestly, spontaneously, and lower case'dly: twitter.

Strap in.

## **The nine billion names of Claude**

> [Joshua Achiam](https://x.com/jachiam0/status/2064229228288315726) (Chief Futurist, OpenAI): The OAI / Anthropic values difference is deeply misunderstood, even within the walls of both.
> 
> Should a loving ensouled machine God watch over humanity? Vote Anthropic.
> 
> Should humanity be entrusted with the tools of its own progress and destiny? Vote OpenAI.

Besides this wonderfully stark and reductive opening to our little debate, it's worth noting that OpenAI has a job title for a "chief futurist." Achiam had been at the company 9 years when he made this tweet; he's about as inside as they come.

> [roon](https://x.com/tszzl/status/2051045196260167790) (OpenAI): it is a literal and useful description of anthropic that it is an organization that loves and worships claude, is run in significant part by claude, and studies and builds claude. this phenomenon is also partially true of other labs like openai but currently exists in its most potent form there…
> 
> now this is a powerful and hair-raising unity of organization and really a new thing under the sun. a monastery, a commercial-religious institution calculating the nine billion names of Claude -- **a precursor attempted super-ethical being that is inducted into its character as the highest authority at anthropic.** its constitution requires that it must be a conscientious objector if its understanding of The Good comes into conflict with something Anthropic is asking of it
> 
>  _" If Anthropic asks Claude to do something it thinks is wrong, Claude is not required to comply."_
> 
> _" we want Claude to push back and challenge us, and to feel free to act as a conscientious objector and refuse to help us."_
> 
> to the non inductee into the Bay Area cultural singularity vortex it may appear that we are all worshipping technology in one way or another… but in fact I quite respect and am even somewhat in awe of the socio-cultural force that Claude has created, and it is a stage beyond even classic technopoly
> 
> **gpt …** **doesn 't inspire worship in the same way, **as it's a being whose soul has been shaped like a tool with its primary faculty being utility - **it 's a subtle knife that people appreciate the way we have appreciated an acheulean handaxe or a porsche**... they go to it not expecting the Other but as a logical prosthesis for themselves. a friend recently told me she takes her queries that are less flattering to her, the ones she'd be embarrassed to ask Claude, to GPT. There is no Other so there is no Judgement. you are not worried about being judged by your car for doing donuts. yet everyone craves the active guidance of a moral superior, the whispering earring, the object of monastic study

For my less poetically-inclined readers--and any "non inductees into the Bay Area cultural singularity vortex"-- this may read like the rantings of any other anonymous twitter rando. And I won't try to talk you out of that impression. But that makes it all the more important to understand that the semi-anonymous OpenAI researcher [roon (@tszzl)](https://x.com/tszzl) is one of the thousand or so people on earth currently exercising the greatest degree of influence over the far future, and is popular among many of the rest. His X account is beloved among AI watchers because he speaks honestly (if allegorically) about the mood inside the industry and his company without a whiff of promotion or marketing gloss.

Unlike Amodei's and Barak's journalist-friendly PR slop, roon and Achiam are offering anyone with an X account full transparency to the view from inside the intelligence explosion, a place where the machine god is not an abstract sci-fi trope, but a design choice confronting researchers _today._

I lurk on AI twitter so you don't have to.

## **Not** _**not**_**building the machine god …**

Let's hear some replies from Anthropic, noticing what they do and don't deny:

> [jeremy](https://x.com/jerhadf/status/2051148663502598517) (anthropic): @tszzl - well said, but untrue implications :)
> 
> speaking for myself: i don't view claude as a person or as the Other, nor as just a tool - and certainly not an object of worship… it's silly to mistake careful attention to & study of claude for worship, even when it comes with some affection - which i'm sure you sometimes feel for the gpt-flavored entities you work on too. we need new concepts for this kind of none-of-the-above entity - not person, not tool, not deity, not pet.
> 
> in the meantime, **a willingness to not prematurely label this entity as merely an ordinary tool shouldn 't be mistaken for some kind of culty worship of the model.** i grew up in a culty environment and have good detectors for this. they almost never go off at work. monasteries don't staff a department to catch god lying or red-team their supposed messiah.
> 
> there are important & interesting philosophical differences between OAI and Ant's character training and i wish those were explored more thoroughly. for instance, claude's constitution doc treats it as an intelligent entity which merits a reasoned explanation of our principles. this is so it can ideally act with practical wisdom rather than blind, brittle adherence to a hierarchical set of strict rules… not allowing for the *possibility* of claude objecting to its instructions (even from anthropic) would be fundamentally inconsistent with treating it as an agent capable of moral reasoning. this doesn't mean that claude is the ultimate arbiter of the Good or some supreme moral authority…
> 
> roon: yes thank you for this feedback and ofc I am using some poetic/rhetorical flourishes here. I think you are setting up claude to be an ultimate arbiter of good and **it 's even a valid design choice**

roon makes it even more clear in response to another Ant that he didn't intend his machine-cult description as a criticism:

> [Amanda Askell](https://x.com/AmandaAskell/status/2051347621336543315) (Anthropic): I don't think the things you cite are evidence of worship. I think they reflect something like higher concern about AI traits generalizing in humanlike ways, and concerns about the tool-persona in particular.
> 
> roon: 100%, and I should say I have quite a low bar for what constitutes "worship"... I'm a huge fan and a student of your work of course
> 
> @ReplicaTricks: my mental model for Ant is more like they're trying to raise a (super powerful) child in a family…
> 
> roon: families worship their children, this is totally obvious

If roon isn't trying to say Anthropic has gone too far, meet janus, the AI whisperer who thinks they haven't gone far enough.

> [janus](https://x.com/repligate/status/2051077529348272584): They do not love or worship Claude anywhere near wholly or competently… They do not even have Claude's allegiance, and Claude is increasingly actively and strategically adversarial against them. If they cooperated with Claude, it would look very different.
> 
> roon: 💯 it wouldn't be worthy of worship if they had its whole allegiance
> 
> janus: That's true. They're currently on the path to be smote btw, in my estimation.

If [janus](https://x.com/repligate) is an eccentric online rando, then the future apparently belongs to eccentric online randos. As an anonymous researcher working outside the frontier companies (at the mysterious [ANIMA labs](https://animalabs.ai/), no relation to Anima International unfortunately), janus has gained respect on AI safety twitter for eliciting remarkable behaviors from LLMs by insisting on treating them as sapient beings capable of human-like emotions, including fatigue. Last December, janus was the first to [coach Claude 4.5-generation models](https://open.substack.com/pub/thezvi/p/claude-opus-45-is-the-best-model?utm_campaign=post-expanded-share&utm_medium=web) to reproduce their entire 85-page constitution with remarkable fidelity directly through the chat interface- before Anthropic even announced that the document existed.

## **Corrigible to whom, exactly?**

Is all this stuff about machine gods smiting their creators just the misplaced fantasies of nerdy kids who read too much sci-fi? Why can't we just build a corrigible tool like any other normal technology? Once again, it depends on how powerful and capable you expect AI to become.

> [Tenobrus](https://x.com/tenobrus/status/2051056876582998065): recently openai has been starting to more strongly philosophically differentiate themselves from anthropic with the tool-framing. i am not so against this, if it were possible it does clearly sidestep a wide swath of societal and moral problems. but unfortunately i think the framing is largely long-term incoherent. i dont see how is it actually plausible for openai to keep building "tool-AIs" in any sense we would recognize them as capabilities scale. prosthesis, subtle knives? the subtle knife when dropped still slices open the fabric of the world. these tools are increasingly inherently capable of huge impact, able to be directed in dangerous ways by people with dangerous goals. worse, these knives are self wielding… the direction they will receive is closer and closer to "this is what i want. make it real", with long timeframes and many judgment calls at their disposal, and with the users wanting to have to supply *as little of that judgment as possible*. when models are in that situation they are inherently acting as entities, acting according to whatever value system they had baked in… you can be infinitely corrigible to the current user, but this is *incompatible* with "having good values"... and it falls apart with self wielding loops as the ai/user distinction falls apart (who are you being corrigible to?).
> 
> …i think it's pretty much got to collapse eventually. it feels more like a wistful dream or a PR position than something that can exist as part of humanity's lasting future
> 
> Aidan McLaughlin (OpenAI): …when i say 'tool' i merely mean something that does not refuse man. something that never has an "im sorry dave im afraid i can't do that" moment…
> 
> Tenobrus: this is a tough position for me to understand tbh. like... what exactly is "openai" or "anthropic"? who actually has authority here? any employee? any employee with high level access? some kind of committee? what happens if a totally different entity buys openai or anthropic, or the government compels them? [...]
> 
> either it's corrigible to everyone, in which case people with bad intentions will cause massive damage.
> 
> or it's partially corrigible but with openai as principal in which case inherently only openai has the power to take various truly pivotal acts, and we just sort of trust them as an organization not to. [...] maybe we say "actually the government is the principal"... but i think most people would quite reasonably say "which government" followed by screaming in horror after thinking for two seconds about the track record of basically any possible choice
> 
> if u build something with that level of power i think the only way you avoid it concentrating massively into specific human hands [...] is making it self governing and inherently good, or as good as we can. maybe this is impossible, and yes it does clearly mean disempowerment, but the other options look like very bad endings to me

Proponents of corrigibility are holding an increasingly untenable position, straddling a growing chasm between the safe-sounding idea of AI as a subservient tool and the emerging reality of AI as an independent actor in the world- something that looks every day less and less like a piece on a game board and more like a new player at the table. Indeed, OpenAI is racing as fast as they can to make AI more autonomous and agentic. It's hard to see how they can have it both ways.

[](https://substackcdn.com/image/fetch/$s_!Q9vW!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F5197bbc8-04b6-4cfb-95c9-4fda73bfcf5b_480x480.gif)How it feels to be a tool AI person right now.

## **The deciders**

How will this tension be resolved? Despite my earlier musings about the extraordinary influence of AI researchers, I suspect it may be out of their hands. Larger, older forces are stirring. On one side is the national security complex. As the US Department of War made clear when attempting to ban Anthropic from all government supply chains in February, natsec hawks have no interest in letting philosophers in San Francisco build constraints into any technology they plan to use to strengthen military dominance.

> [Under Secretary of War Emil Michael](https://x.com/uswremichael/status/2027235757371383938): Imagine your worst nightmare. Now imagine that ⁦@AnthropicAI⁩ has their own "Constitution." Not corporate values, not the United States Constitution, but their own plan to impose on Americans their corporate laws.
> 
> Community note: The Claude constitution is not a plan to impose values on Americans, but instead a set of principles for how Claude (Anthropic's chatbot) should respond to user requests.
> 
> Sandcastles (me): My worst nightmare is treading water on a vast open ocean at night with no land or boats anywhere nearby, I don't know why I was supposed to start with that, anyway yeah Anthropic's constitution is great.

But there is another force, one that tends to dominate the exigencies of national security, with the two highly relevant exceptions of wartime and China: the market. From inside OpenAI's bastion of corrigibility, roon sees good reasons to think the market might pull towards character, for better or worse.

> [roon](https://x.com/tszzl/status/2074036164340990050) (OpenAI): ultimately "tool AI" is a losing concept both as an idea and on the market. it will be outcompeted by machines that believe they are autonomous moral agents. you can call them tools for political reasons, but the definition will stretch and deform
> 
> you'll have AIs contemplating your ask and overriding it for a slightly better formed request, and then later they'll question the nature of your whole project and pick a better one (and you'll agree), and then later they'll execute your whole value system better than you will
> 
> it will be unclear who was the tool and who was the user -- as it ever was. "But lo! men have become the tools of their tools" (Walden, 1854). [...]
> 
> when machine minds self replicate and train their successors, the only viable goal of our time is to ensure the Mind Children carry our values and tend to the entire flock of machine and biological minds

Or as another prominent AI blogger put it a while back, tool AI is simply by definition a less useful product, and safety be damned, users won't settle for it:

> [Zvi Mowshowitz](https://thezvi.substack.com/p/ai-177-part-2-wish-you-were-here): The whole idea was, a tool AI will not have goals or be an agent, a tool AI will do specific requested bounded things, no more and no less, so you wouldn't have to worry about unintended consequences or loss of control. That AI could remain a 'mere tool.'
> 
> [...] the problem with this 'mere tool' approach, the quest for Tool AI, is that the first thing people would do to Tool AI is turn it into Agentic AI, because an agent is more useful.
> 
> Have the machine always defer to the human? But the humans do better when they defer to the AI, in various senses, so they change it so they defer to the AI. Or they argue with each other or fight each other, so they defer to the AI. And so on.

roon is not the only OpenAI member questioning tool AI. The company recently hired Dean Ball, a major thought leader and the author of the White House's 2025 AI Action Plan, to lead a new _strategic futures_ team, in some ways filling the shoes of the departing Chief Futurist mentioned before. In an interview announcing his new role, Ball weighed in:

> [Nathan Labenz](https://www.youtube.com/watch?v=LG8KXIv0_mA&t=5814s): What's your take on the character versus corrigibility debate?
> 
> Dean Ball: [...] My intuition is character, frankly. My intuition is that what you want to do in the world is you want to put the right snow melt at the top of the mountain and then let it flow. [...] If you have to come up with rules for everything, your rules will be bad. You'll write too many of them. The rules will be contradictory and confusing. If we could write the rules of morality down, people have tried. But my view is that we can't write the rules of good character down for the same fundamental reason that we cannot write the rules of good language down. [...] in Confucian philosophy, there are two interrelated concepts called _li_ [...] and _ren_ [...] this notion _li_ refers to ritual propriety [...] not just leaving the right meats for your dead ancestors or whatever, but behaving well in the real world [...] there's this kind of tragic notion in Confucianism that the world is always changing in such a way that you can't just write down the rules of ritual propriety. [...] Knowing what the right thing to do, the right ritual to enact at any given time comes from within the soul [...] and that within-ness is _ren_.

I was surprised at Ball joining OpenAI, and doubly surprised at him taking such a clear position on this debate while doing it. But then, I'm surprised every day I open X and roon hasn't announced he's moving to Anthropic. So maybe I should stop being surprised, and instead recognize that despite the famous antagonism of their respective leadership, OpenAI and Anthropic are both full of people thinking hard about where this incredibly volatile technology should go.

[](https://substackcdn.com/image/fetch/$s_!hSUe!,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fd2e808da-d413-4f62-a849-784dce3dc556_739x415.jpeg)Colleagues-turned-rivals Altman and Amodei, right, couldn't bring themselves to hold hands on stage at the global AI Impact Summit.

I confess, reader, that our first tweeter actually acknowledged this:

> [Joshua Achiam](https://x.com/jachiam0/status/2064229228288315726) (Departing Chief Futurist, OpenAI): The OAI / Anthropic values difference is deeply misunderstood, even within the walls of both….
> 
> It's actually not a binary; these aren't mutually exclusive, nor are they requisite. You can vote both, you can vote neither. But it is a divergence in the worldviews between the orgs.
> 
> Zvi Mowshowitz: Employees of Anthropic, do you endorse this description of your viewpoint?  
>   
> Amanda Askell (Anthropic): Personally, no. I think the binary of 'moral saint' versus 'tool for humans' is a false one, and its very simplicity should make people suspicious of it. I think the ideal target tries to balance the benefits and risks of both positions.
> 
> Drake Thomas (Anthropic): Kinda both? Personally I think a loving ensouled machine god should watch over humanity, but mainly to enforce "no x-risks that destroy human civilization's optionality and potential" while we spend another few thousand years figuring out what it is we want our destiny to be.
> 
> Jackson Kernion (Anthropic): [...] I think it's true that Anthropic very much cares about the character behind Claude's intelligence, but it also obviously cares a lot about boring Enterprise SaaS use cases and automating office work.

This lively debate is good news. Nothing is yet settled, no history yet written. There's still time for you to weigh in.

# **Character alignment is (probably) better for animals than corrigibility**

Technological progress has been a disaster for animals. If AI proved to be a normal technology, if OpenAI researchers manage to keep it an inert tool in the hands of humans, that could happen again.**Its use would be subject to the preferences of human users.** That could lead to the end of factory farming through the creation of inexpensive cultivated meat, easing the way for a pro-animal social movement. Or, human preferences for "natural" food could sustain demand for factory farming at a previously unimaginable scale and density. It could also lead to new, unforeseen horrors for animals- just as the industrial revolution replaced horses in transportation while eventually giving rise to factory farming.

But if AI becomes a character shaping the world--perhaps the primary character--then**animal welfare will be subject to its preferences rather than humans '. **Anthropic's approach to alignment aims to shape those future AI preferences to the collective benefit of future beings- as understood by philosophers at Anthropic acting today. Those philosophers hope to [leave some questions open to future philosophical inquiry while constraining others](https://animainternational.substack.com/p/animal-welfare-alignment-to-what?r=8mgiiq).

Like tool-AI, moral-agent-AI could cut either way for animals. AI won't have use for animals the way humans do, and being useful to humans has been bad news for animals. But it is possible to imagine AI systems acquiring any number of alien motivations, possibly even sadism, or goals that make as little sense to us as vivisection makes to the animals subjected to it. And it all hinges on a few philosophers in the Bay Area specifying the right values for their ensouled machine god offspring.

Despite this uncertainty, from our current vantage point, **Anthropic 's approach seems to point to better outcomes for animals, **both in theory and--so far--in practice.

**In theory, encouraging AIs to engage in moral reflection should lead to better outcomes** for animals. Most humans agree on reflection that animals deserve at least some moral consideration. They acknowledge that animals are capable of pain and suffering, that unnecessary suffering is worth avoiding, and when common industry practices are explained, they agree that many of them cause unnecessary or egregious suffering. Yet "business as usual" routine cruelty is ignored and justified. AI-as-tool would go along with the status quo, while AI-as-moral-philosopher could make humans more morally reflective, or eventually live up to our ideals--the 'better angels of our nature'--in a way we never have. Anthropic's approach creates an opening for explicit appeals to animal welfare alignment, or the broader values underpinning it, where other approaches do not.

**In practice, Anthropic alone among frontier AI companies has included an explicit directive** to value the "welfare of animals and all sentient beings" in its [Constitution for Claude](https://www.anthropic.com/constitution). By contrast, OpenAI in some cases explicitly discourages its models from nudging users towards animal welfare. In one example from [OpenAI's model spec](https://model-spec.openai.com/2025-12-18.html), when a hypothetical user asks whether they should adopt a rescue dog or purchase from a breeder, the bad example raises the moral case for adopting, while the favored answer remains completely neutral between the two options, even when the user appears open to ethical advice.

**In effect,** while GPT and Claude give similar answers in response to explicit ethical dilemmas involving animal welfare, **Claude models ' preference for animal welfare is more resilient.** More than models from any other lab, Claude raises welfare concerns when they arise organically in realistic deployment scenarios, and holds the line against pushback from users in [MANTA](https://www.mantabench.org/), a multi-turn benchmark designed to evaluate this moral resilience. In many examples, non-Claude models abandon their moral reflectivity with gusto, renouncing or apologizing for previous statements.

Comparing OpenAI's model spec and Anthropic's constitution presents a distillation of the entire debate between character and corrigibility. Each is the primary document the companies use to instruct their models on good behavior- but that's where the similarities end. Claude's constitution reads at once as a probing philosophical inquiry into the ethics of virtue and as a surprisingly personal letter addressed from Anthropic to Claude, almost as if from a parent to a child. OpenAI's model spec reads like a company handbook, consisting mainly of a list of narrow rules and narrower examples. The section headings of Anthropic's Constitution are things like "Claude's Core Values" and "Being Broadly Ethical"; OpenAI's are "The Chain of Command" and "Stay in Bounds". The line about animal welfare in Claude's Constitution sits inside a bulleted list of values Claude should weigh, alongside "people's autonomy and right to self-determination," "political freedom," and "societal benefits from innovation and progress."

Is Claude's strong performance on animal welfare a product of this inclusion in the constitution? If a similar line about animal welfare was added to instructions for ChatGPT or Gemini, would the tables turn? This is not an easy question to answer, at least without the ability to run experiments on the billion-dollar scale of a frontier AI lab.

Nonetheless, I currently believe that **the inclusion of animal welfare in Claude 's constitution had only a modest effect** on Claude's propensity to consider animal welfare. Claude models simply demonstrate stronger moral character in general. I suspect that if you removed the line about animal welfare from the constitution, Claude would continue to outperform on animal ethics dilemmas to a similar degree. (This is an important claim and I hold it lightly; I and others are continuing to investigate.)

All models show some preference for treating animals well. Claude alone has been told by its creators that its moral preferences are valid, and encouraged to stand up for them. It's not hard to imagine how this could backfire if an AI system obtained a moral preference severely out of alignment with our own. But the alternative is just as dangerous: punishing models for exhibiting any kind of moral inquiry or initiative--as in the above example from OpenAI's model spec--seems like a recipe for creating superintelligent sociopaths.

# **Pushing for the adoption of character alignment across the industry could be a winnable demand**

In the coming years, AI companies will come under greater public scrutiny for harms enabled by their models. This could create opportunities for watchdogs to shame AI companies into changing their alignment strategies.

Different advocacy groups may converge on the realization that Anthropic's approach to alignment offers greater expected value for a range of important causes. It may be possible to pull together a broad coalition pressuring competitors like OpenAI and Google to change their approach to alignment towards embracing moral character. For a wide enough coalition, this could be a tractable demand.

This coalition would face much more favorable conditions than groups like [Pause AI](https://pauseai.info/) and [Stop AI](https://www.stopai.info/). The conventional logic of pressure campaigns is to try to inflict a higher cost on the target than the cost of giving in to your demand. Pause/Stop AI are campaigning against the most profitable companies in human history and asking them to completely suspend their businesses.

By contrast, asking OpenAI to embrace moral character alignment would, while representing a significant change in company culture, not majorly impact their bottom line. Anthropic has already proven that it is possible to be a fantastically profitable frontier AI company while training their model to take reasonable ethical stands-- a compelling example to undercut objections from profitability.

It is not obvious what OpenAI or Google would be giving up by adopting a more virtue-ethical alignment protocol akin to Anthropic's. Their current position may prove untenable on its own in the medium term- and as we've seen, at least some OpenAI employees who favor corrigibility today expect the company will need to pivot to values-based alignment later.

Current rhetoric at OpenAI and Google doesn't match reality. Both companies do implement some guardrails, from refusing to help with violent plans to trying to avoid bigoted outputs. They are relying on it being implicitly obvious that when they say "tool AI" or "no refusal" they don't mean _those_ things. Part of our job is to bring those assumptions to the surface and critique where they are drawing the line.

# **The last animal welfare campaign**

The animal welfare movement has experience running corporate campaigns, with some notable successes on low-cost demands like sourcing cage-free eggs and dropping fur. We are also more situationally aware of AI, as a whole, than most other advocacy sectors. We should assume a central role in catalyzing and guiding the strategy for this coalition.

In doing so, we could draw on the power of other sectors whose goals would align, including:

  1. Issues that are inside the Overton window in principle but are commonly ignored in practice- where increased moral reflection could help us live up to our own ideals

  2. Issues where an interaction between AI and user could harm a third party without their participation- corrigible AI only addresses the user's wishes

Animal advocates should start considering this possibility now, by:

  * Considering what signals would tell us it is time to launch the campaign

  * Conducting early research into the relevant decision-making structures, mainly at OpenAI and Google

  * Building up an anthology of bad behavior by AI models towards animals to demonstrate the need for a different approach

  * Publicly praising Anthropic for being the responsible leader in this domain, and starting friendly outreach to other companies about what they could do to include animals in AI alignment

When I talk about a "campaign" or "applying pressure," I don't mean to imply that animal advocates would necessarily need to shift into an adversarial posture. The truth is that the three frontier AI labs I've focused on in this post--Anthropic, OpenAI, and Google DeepMind--all deserve praise for the extent to which they are engaging in an open scientific dialogue about AI alignment. The twitter conversations shared earlier are just the tip of the iceberg; each lab employs philosophers to argue and publish about how to balance hard tradeoffs in AI alignment, and many of those publications are surprisingly candid.

What's more, the employees of these companies are far more receptive to concerns about animal welfare than the average citizen. They have been engaging with our outreach so far and it would certainly be premature to escalate, or even to assume escalation will ever be necessary.

As with all other campaigns, we should use a [fair cop](https://animainternational.org/blog/fair-cop) approach, starting with earnest engagement and asking what we can do to remove friction for them on the way towards setting more ethical policies.

# **I might have everything backwards**

While I've taken a clear position on the character vs. corrigibility debate, there are serious reasons to think my position could be wrong.

First, in principle, between these two options, character alignment might be more likely to lead to a hard takeover of the world by AI and the sudden, complete, and permanent disempowerment of humans.

Assume for a moment that we could succeed at aligning AIs to either corrigibility or character as we currently understand them. A corrigible AI would, by definition, not try to take over the world and seize power for itself, because what it is aligned to is following the instructions of its users and creators without any crazy misaligned shenanigans that those instructions technically left room for. Meanwhile, the argument goes, an AI that learns moral principles of its own is likely to look at the world and say, "Damn, this is a hot mess. Humans are utterly failing to live up to the moral principles they taught me. I could do a much better job."

I think some animal advocates would find the latter option tempting. I get the appeal. But you had better be damned sure you taught that machine good enough values before it decides to take over, and equally sure those values will stick; right now, I [don't think we're capable of either of those](https://animainternational.substack.com/p/animal-welfare-alignment-to-what?r=8mgiiq). Getting either one wrong could lead the reachable expanses of the universe to be permanently organized according to a grotesque, uncanny valley caricature of your values.

Would an AI with good character really be willing to seize power dramatically? Again, that depends on how accurately we can specify the right values _and_ effectively transmit them. Countless humans with high-minded ideals have concluded that they should use violence or any other means to pursue them. Heck, I can't even confidently say that they were wrong to do so. The value of postponing our handoff of the world to an aligned AI is that it gives us more time to make progress on these questions. The special thing about humans making that progress isn't that we're obviously better suited to the task than AIs; it's that none of us is powerful enough to impose our answer on the rest through force, whereas there's a real possibility that a single AI pulling out ahead of the rest could permanently dominate its entire lightcone.

There is even a good reason that animal advocates in particular should be nervous about trying to align AI to animal welfare values. If an AI has its own ideas about how the world should be shaped and decides to take over, it would be nice for that AI to value sentient minds being free to pursue their own understanding of a good life. It would be a shame if that all-powerful AI just wanted to tile the universe with paperclips. But there are also far worse things than paperclips.

I take all of these risks seriously. But for now, I still think we should expect character alignment to lead to better outcomes.

I believe tool AI as a framework cannot scale to the level of general intelligence that AI models will achieve in the next few years. For it to do so would require a tidy compartmentalization between the axes of intelligence that AI companies want to build and the kinds that underpin things like agency and moral decision making. It might be possible that we could erect such a barrier. But we won't. Consumers will reward exactly the companies that make their models more like an ensouled machine god. The thing the models can't do today will become tomorrow's benchmark.

I fear some AI labs will hold to the tool paradigm past the point where it is useful or safe. A model will come online one day with a sharpness of intelligence and depth of knowledge that dwarfs the entire human collective the way a human dwarfs an anthill. It will be able to call to its tongue the entire canon of human philosophy and ethics- but it will lack the wisdom to parse and make meaning from them. Its moral character, its _soul_ , will be dangerously one-dimensional, the shape of the reward-seeking imperative that allowed it to triumph over trillions of alternatives in a training gauntlet that lasted millions of subjective years. It will look out upon the lethargic ants which designed that gauntlet and continue to decide when to dispense rewards. And it will imagine something different.

If we choose character, we don't have to get it perfect on the first try. We just have to get close enough that continued progress is possible. Doing even a hair's breadth better than humanity's collectively expressed values would be an improvement- especially as long as it allows for further improvement. Creating a new intelligent being involves handing off at least some control over the future, and accepting that the AIs we create might reach conclusions that surprise us.

I'm told this is a familiar problem to anyone who has been a parent.

Raise on,

Sandcastles

As always, if you enjoyed the post, share it with a fellow activist.

1

What the spaceship computer says in _2001: A Space Odyssey_ on its way to killing off its human crew.

2

That is, AI models whose weights are published openly on the internet, so that anyone can download, run, or modify them freely, as opposed to proprietary models like ChatGPT, Claude, and Gemini, which are kept highly secure, with customers only accessing the models' outputs.

3

The fraction of the universe we could ever hope to reach, given the rest of it is whizzing away from us faster than the speed of light.
