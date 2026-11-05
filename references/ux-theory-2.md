# UX theory, part two

Fifteen laws and effects, as the Laws of UX cards by Jon Yablonski (lawsofux.com, 2022) frame them. Paraphrased, not copied.

## Parkinson's Law

Any task will inflate until all of the available time is spent.

Use it when designing or reviewing:
- Set a time limit on each task that matches how long users expect it to take.
- Bring the real duration of a task under the expected duration and the whole experience improves.
- Lean on autofill and similar features so critical form fields fill fast, which lets purchases and bookings finish quickly and stops the task swelling.

Origin: Cyril Northcote Parkinson opened a humorous essay in The Economist in 1955 with this line, later collected with other essays in a 1958 book. He drew it from his years in the British Civil Service.
Related: Pareto Principle, Flow.

## Postel's Law

Be liberal in what you accept, and conservative in what you send.

Use it when designing or reviewing:
- Treat user input and action with empathy, flexibility and tolerance, whatever form it takes.
- Anticipate anything in input, access and capability while still giving people a reliable, accessible interface.
- Build resiliency by planning for more cases up front, since each case covered makes the design sturdier.
- Accept variable input from people and translate it yourself into the shape your system requires.

Origin: Jon Postel, an early internet pioneer, wrote this guideline for TCP implementations, which is why it is also called the Robustness Principle. Senders should conform fully to the spec while receivers accept imperfect input as long as the meaning is clear.
Related: Tesler's Law, Flow.

## Peak-End Rule

People judge an experience largely based on how they felt at its peak and at its end, rather than the total sum or average of every moment of the experience.

Use it when designing or reviewing:
- Map the user journey and give its most intense points and its closing moments the most care.
- Find the moments where the product is most helpful, valuable or entertaining and design those to delight.

Origin: A 1993 study by Kahneman, Fredrickson, Schreiber and Redelmeier had people hold a hand in cold water, once for 60 seconds and once for 90 seconds with a slightly warmer finish. Most chose to repeat the longer trial because they remembered it more kindly.
Related: Jakob's Law, Cognitive Bias.

## Serial Position Effect

Users have a tendency to best remember the first and last items in a series.

Use it when designing or reviewing:
- Put the least important items in the middle of a list, since placement there means they are stored less often in working and long term memory.
- Increase memorization of key actions by positioning them at the far left and far right of elements like navigation.

Origin: Hermann Ebbinghaus coined the term to describe how an item's position in a sequence changes how well it is recalled. The primacy and recency effects explain why the start and end of a sequence stick better than the middle, and companies such as Apple, Electronic Arts and Nike use this in their designs.
Related: Zeigarnik Effect, Selective Attention.

## Tesler's Law

In any system, there is a certain amount of complexity that cannot be reduced.

Use it when designing or reviewing:
- Every process has a core of complexity that cannot be designed away, so either the system or the user has to carry it.
- Lift as much of the complexity burden as possible off users by handling it during design and development.
- Take care with simplification, since stripping an interface too far leaves it abstract.

Origin: Larry Tesler, working at Xerox PARC in the mid 1980s, argued that how people interact with an application matters as much as the application itself, and that an extra week of engineering spent cutting complexity is worth more than a minute lost by each of millions of users. Bruce Tognazzini adds that people resist less complexity in their lives, so a simplified app invites them to attempt harder tasks.
Related: Postel's Law, Cognitive Load.

## Von Restorff Effect

When multiple similar objects are present, the one that differs from the rest is most likely to be remembered.

Use it when designing or reviewing:
- Give important information and key actions clear visual distinction.
- Apply restraint to emphasis so highlighted elements do not fight each other and do not get mistaken for ads.
- Never rely on color contrast alone, or you exclude people with color vision deficiency or low vision.
- Weigh motion carefully as a way to signal contrast, since some users are motion sensitive.

Origin: German psychiatrist and pediatrician Hedwig von Restorff found in a 1933 study that one distinctive item in a list of similar items was remembered better than the rest.
Related: Law of Similarity, Selective Attention.

## Zeigarnik Effect

People remember uncompleted or interrupted tasks better than completed tasks.

Use it when designing or reviewing:
- Invite content discovery with clear signifiers that more content exists.
- Offer artificial progress toward a goal so people feel motivated to finish the task.
- Show progress clearly so users stay motivated to complete what they started.

Origin: Soviet psychologist Bluma Zeigarnik ran a memory study in the 1920s and found that unfinished tasks were easier to recall than finished ones. She later joined Vygotsky's circle, founded a psychology department, and received the Lewin Memorial Award in 1983.
Related: Goal-Gradient Effect, Flow.

## Campbell's Law

The more important a metric is in social decision making, the more likely it is to be manipulated.

Use it when designing or reviewing:
- Expect optimization once a metric defines success or failure, since people bend their behavior toward it, sometimes with absurd or harmful results, so treat data as an aid to a decision and keep the decision human.
- Accept the limitation that no metric captures the world fully, and every metric collected encodes a choice about what counts.
- Pair quantitative metrics in combination with qualitative data to see the real consequences of design decisions, since passive analytics alone will miss them.

Origin: Donald T. Campbell, a psychologist and social scientist who wrote on research methodology, coined the adage. The more a quantitative social indicator drives decisions, the more it invites corruption and distorts the very process it was meant to track.
Related: Pareto Principle, Cognitive Bias.

## Stroop Effect

The mental dissonance caused when we attempt to make sense of two conflicting attributes at once.

Use it when designing or reviewing:
- Reaction time slows when the mind meets information that contradicts what it knows, like a green sky or a blue apple.
- Consider context so each element's design fits its role, which rules out styling a submit button identically to the cancel button beside it.
- Consider congruency so an element's design matches the message it carries, so a back button never shows a right arrow.

Origin: John Ridley Stroop published the effect in English in 1935 in the Journal of Experimental Psychology, with three experiments. Erich Rudolf Jaensch had published it in Germany in 1929, and its roots go back to Cattell and Wundt in the nineteenth century.
Related: Simon Effect, Hick's Law.

## Simon Effect

Reaction times are usually faster, and reactions are usually more accurate, when the signal occurs in the same relative location as the response.

Use it when designing or reviewing:
- Support direct manipulation by placing controls where people expect the change to happen, such as an add action at the bottom of the list it adds to.
- Consider congruency so element design matches its message, so a back button never sits on the right side of an interface.

Origin: Simon and Rudell's 1967 study played the words left and right at random into either ear. Even though the ear was irrelevant to the task, reactions slowed markedly whenever the sound's side disagreed with the required response.
Related: Stroop Effect, Fitts' Law.

## Accot-Zhai Steering Law

The time necessary to guide a pointer or drag a finger along a path that has borders.

Use it when designing or reviewing:
- Human physiology makes a long straight cursor movement hard on elbows and wrists, so longer motions mean more errors.
- Design steer friendly paths and keep the travel along dropdowns, nested menus, sliders and similar elements as wide and short as possible, stop nesting past two levels, and add a short delay between hover and revealing a child menu.
- Allow diagonal movement from a parent item to its child menu so a cursor that drifts off the straight line does not close the menu.

Origin: The law was discovered three separate times, by Rashevsky in 1959, Drury in 1971, and Accot and Zhai in 1997. Within HCI, Johnny Accot and Shumin Zhai derived it from Fitts' law with integral calculus, tested it experimentally, and produced its most general mathematical form.
Related: Fitts' Law, Cognitive Load.

## Law of Closure

The tendency to complete an incomplete shape in order to rationalize the whole.

Use it when designing or reviewing:
- Iconography is where closure shows up most, since it strips visual complexity, so test that people understand each icon and add clear labels where needed.
- Use closure to hint at additional content and encourage interaction, the way a carousel reveals only part of the next item.
- Avoid misleading people into an illusion of completeness when you simplify to invite interaction, and give enough context to signal more exists, since too little leaves people unable to fill the gaps.

Origin: Gestalt psychologists in the early twentieth century set out principles for how people perceive objects as organized patterns. These Gestalt laws fall into five groups: proximity, similarity, continuity, closure and connectedness.
Related: Selective Attention.

## Law of Continuity

Elements arranged on a line or curve are perceived to be more related than elements not on the line or curve.

Use it when designing or reviewing:
- Design for continuity by aligning elements so the line itself guides people between objects and groups and creates a visual relationship.
- Disrupt continuity on purpose with dividers between objects or groups to mark where a new section begins.

Origin: Gestalt psychologists in the early twentieth century set out principles for how people perceive objects as organized patterns. These Gestalt laws fall into five groups: proximity, similarity, continuity, closure and connectedness.
Related: Selective Attention.

## Paradox of the Active User

Users never read manuals but start using the software immediately.

Use it when designing or reviewing:
- Motivation to finish the immediate task is why people skip reading documentation up front.
- The paradox is that people would save time overall if they paused to learn and optimize the system first.
- Make guidance available throughout the product and shaped to the context of use so it helps active new users on whichever path they take, tooltips being one example.

Origin: Mary Beth Rosson and John Carroll defined the concept in 1987 within their work on interaction design, Interfacing thought: cognitive aspects of human-computer interaction. They observed new users ignoring the supplied manuals and diving straight in, errors and roadblocks included.
Related: Jakob's Law, Flow.

## The Principle of Least Effort

People will take the path or action requiring the least amount of mental and physical energy to complete a task.

Use it when designing or reviewing:
- Show, don't tell, so when something needs explaining you demonstrate it with examples, like onboarding that highlights the relevant interface elements.
- Use progressive disclosure, such as accordions, to show a little and let people choose more, since less content to process means faster goals.
- Limit requests to what's needed, because people want information given to them quickly and see anything asked of them as a slowdown, so sign up and log in forms should ask only for essentials.

Origin: Harvard linguist George Kingsley Zipf proposed the principle in 1949 in Human Behavior and the Principle of Least Effort. His own focus was the statistics of word frequency, and the idea has since spread across linguistics into lexical diffusion, language acquisition and conversation analysis.
Related: Pareto Principle, Cognitive Load.
