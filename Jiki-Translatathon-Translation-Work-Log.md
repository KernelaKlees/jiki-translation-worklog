## 📅 1. Worklog – Jiki Translatathon (31 July–2 August)
 
### 🗓️ 31 July 2026

#### Italian video player

Completed a full test of the video player interface. I opened the Settings menu and all its submenus (quality, audio, speed, captions), hovered over each button to verify tooltip behaviour, and tested play, mute, fullscreen, and skipping. All core interactions worked correctly.

During the review of the Italian tooltips, I identified two issues:
- The “Settings” tooltip does not appear at all.
- The Picture‑in‑Picture tooltip sounds unnatural in Italian.

Since these tooltips come from Video.js, I evaluated whether the correct procedure was to open an issue directly on Video.js or report the findings within the Translatathon first. After reviewing the context, I proceeded to open an issue on the Video.js GitHub repository to report the missing tooltip and the unnatural PiP wording.

Follow‑up on issue discussion

After providing the clarification on the Italian phrasing, another contributor responded positively and noted that the adjustments looked like quick fixes to apply. This indicates that the corrections were well‑received and considered straightforward to implement. I acknowledged this and confirmed that the changes were indeed simple, offering further clarification on the Italian side if needed.

#### Italian glossary – Core Decisions review

I reviewed the Core Decisions section of the Italian glossary and proposed corrections for two terms: **tech / tech industry** and **streak**. The goal was to ensure that the glossary reflects natural and domain‑accurate Italian usage, especially in modern tech communication and digital communities.

For **tech / tech industry**, I confirmed that *settore tech* is the correct and widely used Italian equivalent. I flagged *industria tecnologica* as inappropriate because *industria* in Italian refers to physical manufacturing. I also noted that *settore tecnologico* exists but is significantly less common in contemporary tech contexts.  
**Proposed action:** keep *settore tech* as the primary translation.

For **streak**, I identified that *serie* is not a valid translation, as it does not convey the meaning of consecutive unbroken days. Italian does not have a natural single‑word equivalent for this concept.  
**Proposed action:** use *giorni di slancio*, which is already adopted by Duolingo and better reflects the intended meaning.

I also added a linguistic note regarding pseudo‑English expressions commonly used in Italian (e.g., *smart working*), highlighting the need for careful evaluation of English technical terms to avoid unnatural translations.

Follow‑up discussion on “streak” translation

After proposing the shift from “serie” to “slancio” / “giorni di slancio”, the maintainers asked for two confirmations before finalizing the change:

1. Whether **“slancio”** works on its own as a UI label in places where only a single word appears above a number.
2. Whether **“una serie di 5 giorni”** should become **“uno slancio di 5 giorni”**, and if the gender/article usage is correct.

I confirmed that **“slancio”** works perfectly well as a standalone UI label. It is short, clear, and immediately understandable even without additional context, making it suitable for minimal UI layouts (e.g., “Slancio 5”). It conveys the idea of momentum and continuity more effectively than “serie”.

I also confirmed that **“uno slancio di 5 giorni”** is grammatically correct. “Slancio” is masculine, so the article “uno” is appropriate, and the construction “di X giorni” sounds natural in Italian. This phrasing aligns with how Italian speakers would describe an unbroken run of consecutive days.

#### Exercise: Solve the Maze – Italian phrasing clarification

While reviewing the Italian translation for the “Solve the Maze” exercise, I provided a detailed explanation regarding the correct phrasing of “Ti diamo il benvenuto al tuo primo esercizio”. The original version (“Ti diamo il benvenuto nel tuo primo esercizio”) sounded unnatural in Italian, so I clarified why “al” is the appropriate choice.

I explained that **“benvenuto nel”** is used when entering a place or a group (e.g., *Benvenuto nel team*, *Benvenuto nel forum*), while **“benvenuto al”** is used when entering an activity, event, or exercise (e.g., *Benvenuto al corso*, *Benvenuto al tuo primo giorno*, *Benvenuto al tuo primo esercizio*).

I also noted that Italian distinguishes between two types of *moto a luogo* (“movement toward a place”): a literal one (entering a physical location) and a figurative one (entering a context or an activity). “Benvenuto nel team/forum” uses the figurative sense of entering a context, whereas “Benvenuto al corso/esercizio” uses the figurative sense of entering an activity or event. This is why “Benvenuto al tuo primo esercizio” is the natural phrasing.

The clarification was appreciated, and the translation was updated accordingly.

### Using Functions — Summary

During the review, several stylistic and linguistic issues were identified in the Italian adaptation of the course text.

1. **Redundancy in character introduction**
   The original phrasing repeated “Jiki” multiple times in close succession (“Tutto il corso prende il nome da lui. Lui è Jiki. Jiki sarà il tuo amico…”).  
   Italian avoids unnecessary repetition, so a more natural structure was proposed:
   - “L’intero corso prende il suo nome: Jiki sarà il tuo amico in questo viaggio nella programmazione.”

2. **Correction of non‑idiomatic expression**
   The phrase “negli uni e zeri” is not idiomatic in Italian.  
   It was replaced with correct technical terminology:
   - “codice binario”
   - “0 e 1”
   - “sequenze di 0 e 1”

3. **Full revised Italian adaptation**
   A smoother and more natural version of the introductory paragraph was produced:

   > “Quando scrivi codice, in realtà stai comunicando al computer ciò che vuoi che accada, usando un linguaggio che lui può comprendere. Esistono tantissimi linguaggi di programmazione diversi e altrettanti strumenti che prendono ciò che scrivi e lo trasformano in codice binario, quei 0 e 1 su cui il computer può davvero agire.  
   >  
   > In questo corso, il tuo compagno di viaggio sarà Jiki: il personaggio che dà il nome all’intero percorso. Il suo compito è interpretare il codice che scrivi e convertirlo nel formato che il computer può eseguire.”

4. **Final revision note**
   Final revision — this is the best adaptation for now, waiting to see what other native speakers think.

### 🗓️ 1 August 
Reviewed and refined the Italian adaptation of the introductory course text.  
Addressed redundancy in character introduction, corrected non‑idiomatic expressions, and produced a smoother, more natural final version.

Aligned with the intended “human translator” interpretation of Jiki after discussion with the project maintainer Jeremy Walker (iHiD).
Provided initial revisions and responded to stylistic feedback; further adjustments will be handled by other contributors.

**Status:** this part of the work is complete and the agreed direction is now clear.

### Italian Review – Concept Page: Creating and Using Variables

I opened the review thread for the Italian translation of the Jiki concept “Creating and Using Variables”.

In this session I focused only on the first part of the page.  
I reviewed the initial paragraphs and shared my suggestions to improve naturalness and flow, especially around the metaphor of the “magazzino di Jiki” and the description of the scaffali and scatole.

At this stage I have not yet reviewed or checked FraSanga’s reply; my contribution was limited to commenting on the first section of the text.

### 🗓️ 2 August 

### Italian Review – Exercise: Bouncer: Dress Code

Today I checked the new review thread for the Italian translation of the exercise “Bouncer: Dress Code”.

My contribution in this session focused on the beginning of the exercise.  
I reviewed the opening sentence:

“Sei di nuovo al tuo secondo lavoro da buttafuori, e stasera lavori in un locale con un dress code rigoroso.”

In this session I continued reviewing the English source text and adapted several short phrases and titles into natural Italian. I focused on clarity, register, and contextual accuracy (especially for hospitality‑related expressions and coding terminology). I prepared formatted forum‑ready blocks for each item, including block quotes, Italian adaptations, and explanatory notes in English when needed. My contribution was limited to revising and adapting the selected phrases; I did not work on other sections of the page.

and proposed a more natural adaptation:

“Sei tornato al tuo lavoro occasionale come buttafuori, e stasera lavori in un locale con un codice di abbigliamento rigido.”

I asked for feedback on this adaptation, as I am reviewing the translation piece by piece and adding my notes in a single post to avoid creating multiple threads.



I added a clarification in the discussion regarding the translation of branch. I explained that “ramo” is the correct and consistent technical equivalent in decision‑tree contexts, even if in this specific sentence it may sound less clear. I noted that alternatives such as “diramazione”, “percorso”, “condizione” or “caso” can work in certain nuances, but they do not fully match the meaning of branch and cannot be used interchangeably. I suggested keeping “ramo” as a univocal term to maintain terminological consistency across the project.

This concludes my contribution on this part of the project.

#### Exercise: Solve the Maze – Italian phrasing clarification

I made two adjustments in the discussion.  
First, I clarified that “farti prendere confidenza” is an unnatural expression in Italian because it is a literal translation from English, and that “familiarizzare” is a more appropriate and natural choice.  

Second, I refined the descriptions of move(), turnLeft(), and turnRight() by removing the redundant “che”, which does not add meaning and makes the sentences heavier.  

I also added a brief note explaining that “dashboard” is typically left unchanged in Italian in technical, corporate, and IT contexts, since the term is widely understood by Italian professionals and users.  

The rest looks fine to me.

#### Exercise: Dietrofront

I added a clarification regarding the term “dietrofront”. I explained that it is not a natural choice in this context, as it is a strictly military expression and sounds like an order given during a drill. This makes it overly formal and out of place in simple movement commands.  

I noted that a neutral and appropriate equivalent for “turn around” is “girarsi”, which fits standard movement instructions without introducing unintended military connotations.  

I also added a light remark to soften the critique, pointing out that maybe I am at war with JavaScript, but the users definitely aren’t, so “dietrofront” should be avoided here. 😅  

Everything else is fine.

### 🗓️ 3 August

### Exercise: Rock, Paper, Scissors (follow‑up thread)

Followed the review thread opened by another contributor.

Added my comment explaining that “annunciare” is too formal in this context and sounds like something from a ceremony or a presenter.

Suggested using “comunicare” instead, as it fits better with the logic of the code (we’re determining the winner, not announcing them like at an award show).

Corrected the sentence:
il vincitore alla sala di gioco.
to the more natural and idiomatic:
il vincitore in sala giochi.

Suggested replacing:
e hanno scelto la stessa cosa.
with:
se hanno pareggiato.
explaining that “pareggiare” maps directly to “tie” and is shorter, clearer, and more natural in Italian.

Confirmed that everything else worked for me.

### Exercise: Traffic Lights

Opened thread: This is a thread for reviewing the Italian translation of the exercise Traffic Lights.

Added note on terminology: specified that “radius” corresponds to “raggio” if you want to be accurate in Italian.

Checked the rest of the exercise and confirmed: no issues with the rest.

### Exercise: Fix the Wall (follow‑up thread)

Followed the review thread opened by another contributor.

Read the proposed improvements regarding the sentence about drawing rectangles and the clarification on distances (top/left).

Read the suggestion to keep variable names in English (top, left, height, width) and highlight them as variables.

Confirmed that, for me, the proposed changes were fine and I had no additional issues to report.

### Exercise: Rolling Ball (follow‑up thread)

Followed the review thread opened by another contributor.

Read the discussion about the term “tee” and the alternative “chiodino”.

Left my comment explaining that the main issue for me was the verb tense in the Italian translation of “The ball rolled to {{ballX}}”. I noted that “rotolare” can stay if preferred, but “spostata” is more precise. I explained that English uses past simple in technical descriptions, while Italian usually prefers present or a resultative form, making a literal past tense sound less natural.

Added that “tee” is perfectly fine in Italian, as it is commonly used in Italian golf terminology.

Confirmed that I was good with the rest.

### Exercise: Foxy Face (follow‑up thread)

Followed the review thread opened by another contributor.

Read the proposed changes regarding the symmetry sentence, the use of “viso” vs “faccia”, and the updated description for drawFox.

Added my correction to the sentence:
Il tuo compito è usare “i” triangoli per costruire una faccia di volpe geometrica:
explaining that in Italian the article is needed because “i triangoli” refers to a specific set of shapes required for the exercise.

Applied the same correction to:
Usa “i” triangoli per costruire la faccia geometrica della volpe sullo sfondo grigio.

Added my comment noting that “muso” refers only to the snout/mouth area and not the whole face.

Confirmed that I agreed with the proposed fixes and that everything looked good to me.

