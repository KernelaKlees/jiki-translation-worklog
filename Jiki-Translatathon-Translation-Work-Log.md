## 1. Work Sessions

### 31 July 2026

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
