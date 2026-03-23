# HARTWELL PARK — Revision Guide

## Project Overview

This is a completed ~118,000-word historical fiction manuscript set in 1813-1814 England. Five books (39 chapters + epilogue), organized seasonally. The story follows parallel healing arcs: Sage Morrison (17, recovering from sexual assault) and Promise (a brutally abused stallion), set at Hartwell Park, an unconventional estate run by women who practice gentle horse training.

The manuscript is in comprehensive revision. This file contains cross-chapter revision instructions organized by pass. Each pass targets a specific characterization or structural issue. Work chapter-by-chapter, making surgical edits — preserve existing prose wherever possible, add/modify only what the revision requires.

## General Principles

- **Historical voice**: 1813 England. No modern therapeutic language, no anachronisms. Characters speak circumspectly. Philosophy emerges through practical statements about work, not manifestos.
- **Show don't tell**: These revisions add behavioral beats and subtle cues, not exposition or diagnosis.
- **Surgical edits**: Use str_replace to modify specific passages. Don't rewrite scenes that are working. Most chapters need 3-8 small additions or tweaks, not wholesale revision.
- **Preserve what works**: The prose quality, pacing, and emotional arcs are strong. We're adding texture, not restructuring.
- **Track your work**: After completing each chapter, note what was changed in a brief comment at the end of the file or in a separate log.

## File Structure

- Chapters are markdown files: `chapter_01_the_rescue.md` through `chapter_32_winters_end.md`
- Book V chapters: `hartwell_park_book5_ch33.md` through `hartwell_park_book5_ch39.md`
- Epilogue: `hartwell_park_epilogue.md`
- Reference files: `hartwell_park_bible_updated.md`, `book_[1-5]_summary*.md`
- Reference files should be updated AFTER all chapter revisions in a pass are complete

## Known Continuity Issues (Fix Opportunistically)

- **Promise's age**: Bible says 6 at arrival (born 1807). Book 1 summary incorrectly says "three-year-old." Chapters correctly say six. Fix the summary.
- **Jennifer's age**: Bible says 43. Book 1 summary says "approximately 37." Use 43.
- **Horse colors in Book 1 summary**: Summary has Clover/Thunder colors swapped vs. bible. Bible is correct: Clover = chestnut mare, Thunder = grey gelding.
- **Two Chapter 14 files**: `chapter_14_rebuilding.md` and `chapter_14_returning_to_the_saddle.md`. The latter ("Returning to the Saddle") is the current version. The former can be archived/deleted.

---

# REVISION PASS 1: Rebecca's Characterization

## The Problem

A beta reader noted Rebecca seems inconsistent — sometimes kind, sometimes harsh to the point of cruelty. This reads as a character flaw in the writing rather than a character trait in the person.

## The Solution

Rebecca is a highly functional woman on the autism spectrum who has built her life around horses because they communicate honestly and completely through body language — something she's naturally brilliant at reading. Human social signals (subtext, emotional modulation, knowing when someone has heard enough) are harder for her. She's not unkind; she's *always operating from the same place* — absolute honesty, complete directness, and a brain that processes the world through systems and observable signals. What reads as harshness is the same trait as what reads as wisdom. The difference is context, not character.

Jennifer is Rebecca's partner of 15 years and functions as her social interpreter — softening Rebecca's impact, explaining Rebecca to others, and gently redirecting Rebecca when needed. This is a loving dynamic, not a corrective one. Jennifer understands and loves Rebecca's mind; she's not trying to fix her.

## Critical Rule

**Never name or diagnose the condition.** This is 1813. There is no framework for autism. Rebecca and Jennifer have simply worked out their dynamic over 15 years. The reader should *recognize* the pattern without it ever being labeled. The word "autism" or "spectrum" must never appear in the text.

## Layer 1: Rebecca's Behavioral Beats

These are small physical and behavioral details woven into Rebecca's existing scenes. 3-6 per chapter where she appears. They should feel natural, not clinical.

### Physical tells (use sparingly, vary across chapters):
- Hands placed deliberately — on knees, flat on table, gripping fence rail. Not fidgeting, not clasping. Positioned with intention.
- Eye contact that's slightly too direct, held slightly too long. She doesn't naturally modulate it.
- Precise physical movements — no wasted gestures. Economy of motion in everything.
- Specific spots for things: her chair, her mug, her pen placed parallel to the ledger edge. Order in her physical environment.
- Discomfort in unstructured social situations (meals, celebrations) vs. comfort in structured ones (training sessions, planning meetings).
- Slight physical rigidity when emotional — the fence-rail grip. Tension held in stillness rather than expressed.

### Communication patterns:
- "Instructional register" — clear, methodical, each point building sequentially. This is her default when explaining anything.
- Weighs words for *precision*, not delicacy. She pauses to get the word exactly right, not to soften its impact.
- Follows logical chains to completion before attending to emotional impact. When Thunder is hurt (Ch 13), she must finish analyzing what went wrong before she can address Sage's feelings.
- Delivers information completely — doesn't edit for audience capacity. Lists every detail of Thornton's methods without gauging whether Sage can absorb it.
- Flat, precise delivery under stress. Voice gets colder and more systematic, not louder.
- Socratic questions used for teaching — this is a genuine preference for how she processes and transmits knowledge, not a pedagogical choice.

### Relationship to horses vs. humans:
- "Patient with animals, less so with humans sometimes" — this is the key line from the existing bible. Make it visible.
- With horses: infinite patience, reads the smallest signals, endlessly creative problem-solving. This is her native language.
- With humans: direct to the point of bluntness, doesn't read emotional cues instinctively, needs to be told (usually by Jennifer) when she's been too much.
- At arrival in Ch 1 and throughout: her body orients toward horses like a compass needle. She checks the horses before greeting people.
- Her philosophy about horses — consent, partnership, reading signals — is partly projection. She's articulating what she wishes humans would offer each other.

### Routines and systems:
- Numbered lists, schedules, structured plans. The heat-schedule in Ch 13. Training progressions laid out systematically.
- Comfort in predictable structures. Recites daily routines with ease.
- Desk organized with careful stacks. Handwriting small and precise.
- Estate finances, breeding records, training logs — she tracks everything.

### Vulnerability and self-awareness:
- She KNOWS she's this way. She's had 47 years to figure it out. She doesn't have a name for it, but she knows she's different.
- Key self-aware moments (add or enhance where appropriate):
  - Ch 13 evening: "When an animal is hurt, I become very focused on the animal... I don't always attend to the rest of it. The human part. Jennifer tells me this is a failing."
  - Ch 13: "Being right and being kind aren't always the same thing, and I'm not always good at managing both."
  - Ch 23 (colic guilt): Her guilt is genuine but she processes it through self-analysis rather than emotional expression. Jennifer has to draw it out.
- She tries. She comes back and repairs damage. The effort is visible and constitutes its own kind of love.

## Layer 2: Jennifer as Interpreter/Bridge

These are moments where Jennifer actively mediates between Rebecca and the world. 2-4 per book, placed at key emotional junctures.

### Types of Jennifer interventions:
- **The prompt**: Jennifer tells Rebecca to go talk to someone, sometimes with guidance ("Gently, Rebecca"). Usually off-page or overheard.
- **The signal**: During conversations, Jennifer touches Rebecca's arm = "enough, she's heard enough." A look or raised eyebrow = private communication about how things are landing.
- **The translation**: Jennifer explains Rebecca to Sage after the fact. "She cares enormously. She just hasn't the faintest idea how to show it without a horse in the room." Or: "It wasn't natural for her... But she watched me the way she watches horses, learned what I needed, and then did it."
- **The warmth after the blow**: Jennifer appears after Rebecca's harshest moments to provide emotional context. Not undermining Rebecca, but helping Sage understand.
- **The private language**: Looks exchanged between Rebecca and Jennifer that Sage can see but not fully decode. "Something passed between them—a conversation without words, the kind that came from years of partnership."

### Placement guide:
- **Book I**: Plant seeds. Jennifer's kitchen scene in Ch 3 (already revised). Ch 1 arrival (already revised). Ch 7 evening after first touch — Jennifer providing emotional warmth Rebecca can't.
- **Book II**: Ch 13 is the critical scene (already revised — "Gently, Rebecca"). Ch 14-15 recovery — Jennifer mediating. Ch 17 after the hunt — Jennifer translating Rebecca's pride.
- **Book III**: Ch 21 (swift progress) — Jennifer noticing Rebecca's enthusiasm overriding her own rules. Ch 23 (after colic) — the dinner scene where Jennifer draws out Rebecca's guilt.
- **Book IV**: Ch 26 (financial meeting) — Rebecca in her element with systems and numbers. Ch 28 (Christmas) — "Brilliant with horses, utterly lost with a potato" already there; enhance with Rebecca's discomfort at unstructured celebration vs. comfort giving her systematic grace. Ch 31 — Rebecca's pride expressed through practical assessment rather than emotion.
- **Book V**: Ch 34 (fair) — Rebecca overwhelmed by crowd chaos, orienting toward horses. Jennifer steadying her. Ch 37 (confrontation) — Rebecca's most articulate and powerful moment because she's defending a horse, which is where she's most fluent. Ch 38/39 — Rebecca's satisfaction expressed through plans and systems for the future rather than overt emotion.

## Layer 3: Key Scenes for Direct Acknowledgment (1-2 total, later in manuscript)

These are moments where the dynamic is discussed more directly. Still period-appropriate, still no clinical language.

**Option A — Jennifer to Sage (Ch 28 Christmas kitchen, already a confessional scene):**
Something like: "Rebecca has always understood horses better than people. It's not a choice — it's simply how her mind works. Horses are honest in a way she was built for. I learned early on that when she says something that cuts, she hasn't felt the edge of it. She's just being precise. My job, if you like, is to feel the edges for her."

**Option B — Rebecca to Sage (late Book IV or early Book V, when their relationship has deepened):**
Something like: "I have never been good with people. Jennifer will tell you I'm too direct, too certain, too focused on the thing in front of me to see what's happening around it. Horses make sense to me in a way people never have. They don't hint. They don't expect me to read between lines I can't even see. Everything I know about gentleness, about meeting a creature where it is — I learned from horses first, and then Jennifer taught me to try it with humans. I'm still learning."

## Chapters Where Rebecca Appears (Reference)

Rebecca has significant scenes in: 1, 3, 7, 8, 9, 13, 14, 15, 17, 19, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 31, 32, 33, 34, 35, 36, 37, 38, 39, Epilogue.

Rebecca/Jennifer together: 1 (arrival), 3 (mentioned in kitchen), 9 (morning), 13 (evening), 22-23 (colic), 26, 27, 28 (Christmas — major), 31, 32, 34, 38.

Promise POV chapters (2, 12, 18, 20, 27 opening, 30, 37 split) — Rebecca appears as "tall-calm-human." No Layer 1/2 changes needed in Promise's voice, but his observations of her can reinforce the pattern (she is predictable, systematic, consistent — which is exactly what a traumatized horse needs).

## Already Revised Chapters

The following chapters have already been revised in this pass. Use them as style/tone references:
- **Chapter 1** — Seeds planted: hands on knees, precision vs. delicacy, compass-needle toward horses, Jennifer reading Rebecca at arrival, tray placed centered, schedule comfort, Thornton-details paragraph with Jennifer-signal foreshadowing.
- **Chapter 3** — Jennifer's "it wasn't natural for her" kitchen addition, Rebecca's ledger/pen precision, instructional register named, recitative quality during Thornton account, terror/viciousness as personal distinction.
- **Chapter 13** — Major revision: heat-schedule list, methodical injury check, attention tracking to Thunder before Sage, flat/precise confrontation delivery, fence-rail grip, Riley's "everything else goes away for her" explanation, Jennifer's "Gently Rebecca" prompt, Rebecca's self-aware vulnerability ("Jennifer tells me this is a failing"), "being right and being kind," parting "you are not Thornton" line, Jennifer's approving tone through the door.

---

# REVISION PASS 2: Chapter Endings — Kill the Epiphanies

## The Problem

Nearly every chapter ends with the same structure: a multi-paragraph reflective monologue where Sage (or Promise) articulates the lesson of the chapter in explicit thematic language. This is a process artifact — each chapter was written as a standalone unit and given a "satisfying conclusion," which means the reader gets the same emotional cadence 39 times. It's repetitive, it's didactic, and it prevents chapters from flowing into each other.

The manuscript tells the reader what to feel at the end of every chapter instead of trusting them to feel it from the scene itself.

## The Core Principle

**End on the concrete, not the abstract.** The best chapter endings in this manuscript are Ch 21 (Promise in moonlight, head slightly lower — pure image, no commentary) and Ch 22 (Sage buries her face in his neck and cries — pure emotion, no analysis). These work because they trust the reader. The worst endings are the ones that take a perfectly good scene and then add 3-6 paragraphs explaining what it meant.

## What to Cut

### The Reflective Monologue Pattern
Most chapters end with some version of this structure:
1. A scene or conversation concludes
2. Sage goes to the window / Promise's fence / her room
3. 2-6 paragraphs of interior monologue restating the chapter's themes
4. A poetic closing line summarizing the lesson

**Cut step 3 almost entirely. End on step 1 or 2, or replace step 3 with a single concrete image or brief thought.** The scene itself has already done the work. The reader doesn't need the essay.

### Specific Phrases to Eliminate or Drastically Reduce
These phrases recur across many chapter endings. Most should be cut entirely; a few can survive once or twice across the whole manuscript in moments that truly earn them.

- **"The work continued."** — Appears in Ch 14, 15, 16, Epilogue. Cut from all but one instance (Epilogue, where it serves as the series' closing philosophy).
- **"That was enough. / It was enough. / It was everything."** — Appears in Ch 4, 7, 26, 32, 38, Epilogue. Keep in Ch 32 (night before the fair — it's genuinely earned there) and Epilogue. Cut from all others.
- **"And she was ready for it."** — Appears in Ch 8, 15, 16. Keep only in Ch 8 (Book I closer).
- **"Tomorrow would come/bring..."** — Appears in at least 15 chapters. Cut from all but 2-3 instances maximum across the whole manuscript.
- **"Both of them learning..."** — Appears in Ch 7, 8, 11, 12, 17. Cut from all but one.
- **"Healing isn't/wasn't linear"** — Stated explicitly multiple times. Cut all explicit statements. The non-linearity should be shown through the narrative, not declared.
- **"One breath/choice/moment at a time"** — Appears in Ch 13, 14, 20. Keep in Ch 13 (where the lesson is most visceral). Cut others.
- **"Small things / small victories"** — Reduce to 2-3 uses across entire manuscript.
- **"Showing up, day after day"** — Reduce to 1-2 uses maximum.

### The Window-Watching-Promise Beat
Sage stands at her window watching Promise in the moonlight in chapters 1, 4, 6, 7, 8, 9, 10, and 14. This should happen no more than 2-3 times across the whole manuscript. Keep it in Ch 1 (establishing the image) and Ch 8 (Book I closer, where it carries symbolic weight). Cut or transform in all other instances.

## How to Revise Each Chapter Ending

### Step 1: Identify the last SCENE moment
Find where the actual scene or conversation ends — the last piece of action, dialogue, or concrete image before the reflective passage begins.

### Step 2: Evaluate what the reflection adds
Ask: Does the reader already understand the emotional significance from the scene itself? If yes (usually), the reflection is redundant. If the reflection contains a genuinely new thought not present in the scene, consider keeping that single thought as 1-2 sentences, not 3-6 paragraphs.

### Step 3: Choose a new ending point
Options, in order of preference:
- **End on dialogue.** The last line of a conversation, especially if it's resonant. No commentary after.
- **End on an image.** A single concrete visual — Promise grazing, snow falling, a candle guttering. No interpretation.
- **End on an action.** Sage closes the curtains. Walks inside. Gives Promise an apple. Something physical.
- **End mid-motion.** Cut before the resolution. Let the reader carry the tension forward into the next chapter. This is especially powerful for crisis chapters.
- **End on a single brief thought.** One sentence of interiority, not a paragraph. "She didn't know what tomorrow would bring. But she slept anyway." NOT six sentences building to a poetic crescendo.

### Step 4: Check the transition
Read the new ending of this chapter followed by the opening of the next chapter. Do they flow? Is there a natural current pulling the reader forward? If the new ending feels abrupt, it's probably working — abruptness creates momentum.

## Chapter-by-Chapter Guidance

**Chapters that can end much earlier (cut 3+ paragraphs):**
- Ch 4: End on Rebecca's line "from where he's standing, it's everything." Cut the final three paragraphs.
- Ch 5: End on Promise's "What if?" The preceding "And somewhere in his chest..." paragraph already does the work. Cut the final four paragraphs of chewing on the question.
- Ch 6: End on Rebecca's "You could have gone many places. You chose here. That matters." Cut the entire "Later, in her room" section (10+ paragraphs of reflection restating Ch 6's lesson).
- Ch 7: End on "Promise lowered his head and returned to grazing, comfortable in their presence. Not approaching. Not retreating. Simply there." Cut "For now, that was everything."
- Ch 9: End on Jennifer's "That means you understand what the work is really about." Cut the final three paragraphs.
- Ch 10: End on "Trusting—just a little more each day—that tomorrow would come and it would be okay." Cut the final three lines about work and falling and flying.
- Ch 11: End somewhere in the Promise section — his decision to stay close. Cut the final passage about "Wondering—just a little, just enough—"
- Ch 14 (Returning to Saddle): End on "That evening, she made her way to Promise's fence..." and his greeting. Cut the 5-paragraph reflective monologue that follows.
- Ch 15: End on Riley asking if she's ready for Promise and Sage saying no. That's the powerful moment. Cut everything after it.
- Ch 16: End on Riley's grin about sidesaddle over fences. Cut the bath reflection.
- Ch 17: Book II closer — can keep slightly more reflection, but cut it to 1-2 sentences after "The work continued." Remove the final six lines.
- Ch 26: End on the household scene — fire, evening, belonging. Cut the final "Tomorrow would bring more work" paragraph.
- Ch 27: End on Sage going inside. "Sage smiled and went inside." Full stop. Cut the following paragraph.
- Ch 29: End on the exchange "I do love you. I'm just still learning what that means." / "We'll learn together." — or very shortly after. Cut the Jennifer "roots go deeper" ending.
- Ch 30: End on "He could wait for tomorrow. He had learned how to do that now." Cut "And that, more than anything, was how he knew he had healed."
- Ch 35: End on the moment — Sage's small smile, Promise's neck under her hand. Cut the "Tomorrow" paragraphs.
- Ch 38: End on Promise's head on her shoulder. "And Sage stayed too." Cut the following paragraph.
- Ch 39: End on "Then she went inside, to the warmth and the light and the people waiting for her, and closed the door on the spring darkness." Cut the final three sentences — they state what the reader already feels.

**Chapters with endings that already work (minimal changes):**
- Ch 1: The unfinished thought and "Perhaps it was enough" — this works because it's the FIRST time, and the thought is genuinely incomplete. Minor trim possible but not essential.
- Ch 2: "Hope is the most dangerous thing of all." — Perfect. Leave it.
- Ch 8: Book I closer — earns its reflective passage. Trim slightly but keep the emotional arc. "Chose hope" is a good final beat.
- Ch 13: Crisis chapter — the ending with the lesson is appropriate here because the lesson IS the action of the chapter. But trim the final 4 lines after "Even when—especially when—it hurt to learn it."
- Ch 21: "But who would notice, in the dark, when everything had been going so well?" — Perfect. Don't touch it.
- Ch 22: Sage crying into Promise's neck. — Perfect. Don't touch it.
- Ch 32: Night before the fair — "That was enough. That had always been enough." — Earned. Keep it.
- Epilogue: "Spring had come again to Hartwell Park. And all was well." — The series closer. Keep it.

**Book endings (Ch 8, 17, 25, 32) get slightly more reflective latitude** since they're closing a structural unit. But even these should be trimmer than they currently are.

## Interaction with Other Passes

This pass should be done AFTER Revision Pass 1 (Rebecca characterization) since some of the new Rebecca/Jennifer beats may appear near chapter endings and shouldn't be accidentally cut. When trimming endings, preserve any Layer 1/2 material that was added in Pass 1.

## The Goal

When this pass is complete, no two consecutive chapters should end the same way. The manuscript should have a mix of:
- Chapters that end on dialogue (at least 8-10)
- Chapters that end on image (at least 6-8)
- Chapters that end on action (at least 5-6)
- Chapters that end on brief interiority (at most 4-5)
- Chapters that end on a reflective passage (at most 3-4, reserved for book closers and major turning points)

The reader should feel pulled forward into the next chapter, not settled into a chair with a cup of tea and a blanket. Momentum over closure. Trust over explanation.

---

# REVISION PASS 3: Replace Colic Arc with Riley's Fall

## The Problem

The colic storyline (Ch 21-23) doesn't work well for two reasons: the link between overwork and colic is medically unconvincing, and the setback is a *medical event* rather than a *training decision*. The story's themes are about choices, judgment, and consequences — the setback should come from a decision someone makes, not from a horse's digestive system.

## The Replacement Arc

Remove the colic entirely. Instead, have the setback come from the decision about who rides Promise first. Rebecca decides Riley should be the first rider because Riley is more experienced. Sage pushes for this — eager, enthusiastic, believing Promise is ready. Riley has reservations but defers to Sage's passion and Rebecca's judgment. When Riley mounts astride, Promise's trauma response is triggered by the unfamiliar rider — he spooks, rears, spins, and throws Riley. Riley is injured. Promise regresses significantly.

This is stronger because:
- The setback comes from a **training judgment call**, which is what this story is about
- It **parallels the Thunder crisis in Ch 13** — once again, Sage's enthusiasm leads to someone getting hurt, but this time it's someone she loves
- It creates the **romantic catalyst** — seeing Riley hurt forces Sage to confront her feelings
- Promise's regression is **psychologically specific** — he associates the astride riding position with throwing Riley, which makes the sidesaddle solution deeply logical rather than arbitrary
- Sage becoming the primary rider is **earned** — she's the one he trusts, and they have to go back to basics together

## What This Changes

### Chapters That Need Full or Major Rewriting:
- **Ch 21** (Swift Progress) → becomes the decision chapter
- **Ch 22** (Something Wrong) → becomes Riley's fall
- **Ch 23** (After) → becomes aftermath and guilt
- **Ch 24** (Weight) → becomes Sage mounting Promise (restructured)

### Chapters That Need Minor Adjustments:
- **Ch 25** (A Different Way) → sidesaddle discovery reframed around astride-trauma
- **Ch 20** (Learning to Lead) → keep the "pushing too fast" warning; adjust/remove colic foreshadowing
- **Ch 26-32** (Book IV) → remove all references to colic; adjust backstory references
- **Ch 33-39** (Book V) → remove colic references
- **Bible and summaries** → update after chapter revisions complete

### Chapters That Stay Unchanged:
- **Ch 18-19** (halter introduction, patience and progress) — no changes needed
- **Ch 1-17** — no changes needed (no colic foreshadowing exists before Ch 20)

## Detailed Chapter Plans

### Chapter 20: Learning to Lead (MINOR REVISION)
**What stays:** Promise leaving paddock, longe line work, Sage knocked down when he surges, Rebecca's warning about pushing too fast. All of this still works.
**What changes:** Remove or soften any specific foreshadowing of colic/belly issues. The "pushing too fast" warning should now foreshadow the backing decision, not a medical crisis. Rebecca's line "I'm seeing a pattern. You're pushing faster than careful would dictate" can stay — it applies equally well to the new arc.

### Chapter 21: Swift Progress (MAJOR REWRITE)
**New content:**
- Keep the golden autumn setting, the training montage (bit, long-lining, surcingle). Promise IS making fast progress — this is real and earned.
- Riley's "That's fast" observation stays — it's perfect as-is.
- Remove the belly sensitivity subplot entirely (the Tuesday grooming scene, the "girthy" conversation).
- **New second half:** Rebecca announces Promise is ready to be backed. The question of WHO rides him first. Rebecca's logic: Riley is the most experienced rider, has the best seat, is most likely to stay calm if something goes wrong. Sage agrees enthusiastically — she wants this to happen, believes Promise is ready.
- Riley's reservations: "He doesn't know me the way he knows you. I'm not the one he trusts." But Riley defers — Rebecca has decades of experience, and Sage is so certain. Maybe Riley is being overcautious.
- End on preparation: saddle work progressing, the plan to attempt backing in the next session. Sage excited, Riley quietly uncertain. The ominous final image should be about the decision, not Promise's health.
- **Promise POV thread:** Promise comfortable with saddle, with weight. He knows small-human. He trusts small-human. The tall-one-with-quiet-eyes (Riley) is familiar but different. Not-his-human. Close-to-his-human but not-the-same.

### Chapter 22: Something Wrong (FULL REWRITE)
**Title could stay or change to something like "The Fall" or "Wrong Rider"**
**New content:**
- Morning of the backing attempt. Sage grooms Promise, talks to him, gets him ready. She's excited, believes in this.
- Round pen setup. Rebecca holding lead rope. Sage nearby to comfort Promise. Riley approaches with saddle.
- Saddle goes on — Promise tolerates it (he's been wearing it in training). Girth tightened. Walk with saddle — fine.
- The weight progression: Riley leans across. Promise tenses but holds. Riley's weight is different from Sage's — heavier, differently distributed, unfamiliar smell. Promise is processing but managing.
- **The mount:** Riley swings leg over. Settles into the saddle astride.
- **Promise's POV:** The weight is WRONG. Not small-human weight. Different-weight, different-smell, different-balance. Legs on both sides like before-time. The position triggers deep body-memory — this is how the man-who-hits rode. This is how the pain-riders sat. The logical mind that has learned to trust is overwhelmed by the body that remembers.
- **The explosion:** Promise doesn't just rear — he spooks sideways first (prey animal response), then rears, then spins. The combination is impossible to sit. Riley is thrown. Lands badly — shoulder/collarbone injury, or hard fall that knocks the wind out completely and bruises ribs badly (mirror of Sage's Thunder fall but worse).
- Promise bolts to the far corner of the round pen, shaking, sweating, eyes rolling. He is TERRIFIED — not of what he did, but because the body-memory has flooded back. Every terrible thing that ever happened with a rider astride on his back.
- Sage's reaction: horror. She runs to Riley first (not to Promise — important character beat). Jennifer called. Rebecca manages Promise in the round pen, giving him space.
- Riley's injury assessed: serious but not life-threatening. Dislocated shoulder, or badly bruised ribs and a wrenched back. Out of riding for weeks. In significant pain.
- **The guilt:** Sage pushed for this. She was the one who said Promise was ready. She encouraged Riley to do it. And now Riley is hurt and Promise is back in the corner, trembling, and everything they built is threatening to unravel.
- Chapter ends on the concrete aftermath — Jennifer helping Riley to the house, Promise still shaking in the round pen, Sage standing between them not knowing who to go to first. NOT a reflective monologue.

### Chapter 23: After (MAJOR REWRITE)
**New content:**
- Days after the fall. Promise has regressed — won't allow the saddle near him. Flinches from the surcingle. Barely tolerates the halter. He's gone back weeks, maybe months in his training.
- Riley recovering. Jennifer's medical care. Riley frustrated, in pain, trying to be stoic. Sage helping care for Riley — this is the first extended intimate time they've spent. Sage realizes how much Riley means to her through the act of caring. Bringing meals, helping with tasks Riley can't do one-handed, sitting with Riley in the evenings.
- **Sage's guilt is double:** She hurt Promise (pushed him past his limit) AND she hurt Riley (pushed Riley into something Riley wasn't sure about). The parallel to Ch 13 is explicit but not stated — Sage's enthusiasm causing harm, again.
- Rebecca's response (with new Layer 1 characterization): She's focused on Promise's regression, analyzing what went wrong with systematic precision. "It wasn't about Riley's skill. It was about the position. Astride. Legs on both sides. That's how every rider who hurt him sat. His body remembered what his mind had learned to set aside." This is Rebecca at her most perceptive — she reads the horse's psychology accurately because that's where her gift lies.
- Jennifer's role: translating between the emotional crisis (Sage's guilt, Riley's frustration) and the practical path forward. Caring for Riley while also gently pushing Sage to forgive herself enough to get back to work with Promise.
- **Riley's insight from the injury bed:** "He didn't throw me because he's vicious. He threw me because I wasn't you." This is the key realization — Promise trusted SAGE. Putting a different rider on him, even a skilled one, was asking him to generalize his trust before he was ready. The trust was specific, not transferable. Not yet.
- New training protocol: back to basics, but with a crucial difference — Sage, not Rebecca, will be the primary handler going forward. If anyone rides Promise, it will be Sage first, because she's the one he's built his trust with.
- **Sage/Riley emotional beat:** Sage caring for Riley, perhaps helping Riley dress or undress with the injured arm/shoulder, the enforced intimacy of injury care. Sage realizes: "I was more afraid when you fell than I've been of anything since Bath." This is the turning point in the romance — not a declaration, but a recognition.
- End on Sage going back to Promise's paddock for the first time since the fall. Sitting at the fence. Promise in the far corner, not approaching. Back to where they started. But Sage sits anyway. Because that's what you do.

### Chapter 24: Weight (MAJOR REWRITE)
**New content:**
- Weeks of rebuilding. Sage patiently re-earning Promise's tolerance of equipment. Halter first (again). Leading (again). Surcingle (again, and this takes longer now — he associates girth tightening with what came after).
- The saddle reintroduction is slower, more careful. Promise freezes when it approaches his back (just like the original Ch 24, but now with the added layer of the Riley-fall trauma).
- Eventually, saddle accepted again. Walking with saddle. Trotting with saddle.
- **The weight progression — Sage this time:** Leaning across. Hanging from stirrup. Promise nervous but managing because it's HER — her weight, her smell, her voice.
- **The mounting moment:** Sage swings her leg over. Promise tenses — the astride position is the trigger. But it's HER. His small-human. The one who has never once caused him pain. He's caught between body-memory (astride = danger) and trust-knowledge (small-human = safe).
- He tolerates it. But he doesn't relax. He's "obedient but not present—tolerating, not accepting." This is the bridge to Ch 25's sidesaddle discovery.
- **Promise POV sections:** The internal battle between what his body remembers and what his mind has learned. Small-human-weight feels different from other-human-weight, but the POSITION is the same — legs on both sides, weight across his spine. His body can't tell the difference between this and before-time. Even though his mind knows this is small-human-safe, his body is screaming.
- End on the problem clearly stated but not solved: Sage can sit on him, but he shuts down. They've hit a wall they don't know how to get around.

### Chapter 25: A Different Way (MODERATE REVISION)
**What stays:** The sidesaddle discovery, the irony of Sage hating sidesaddle, "meet him where he is," the snow, the hopeful ending.
**What changes:**
- Rebecca's insight now has the specific backing of the Riley incident: "Up there, you're not you anymore. You're a rider. And every rider who's been on his back has had their legs on both sides of him. That's the position that hurt him — not just Thornton's riders, but what happened with Riley. His body has learned: astride = danger."
- The sidesaddle solution isn't just about different weight distribution — it's about being NOTHING LIKE the thing that hurt him. Different position, different balance, different feel. No legs on both sides. No reminder.
- Riley can be present for this realization, healed enough to watch from the fence. Seeing Promise relax under Sage in sidesaddle when he couldn't relax under Riley astride — this could sting, but Riley's response should be generous: "He's not rejecting me. He's choosing the position that doesn't frighten him. That's smart. That's him protecting himself."
- The emotional weight of the scene is greater now because the sidesaddle solution is born from real trauma, not just a general preference.

## References to Remove Throughout Manuscript

After rewriting Ch 21-25, search the entire manuscript for references to the colic and remove/replace them:

### Specific references to find and remove:
- "the colic" / "colic crisis" / "gut-pain-time" (Promise's POV term)
- "the night we almost lost him" or similar
- "three sessions per day" leading to overwork → can become "the decision to let Riley ride"
- "belly sensitivity" / "girthy" — remove entirely
- "we invented the urgency" — this line is great but needs reframing. Could become about the urgency to prove Promise could be ridden by anyone, not just Sage
- "walking him all night" — remove (colic treatment)
- "linseed oil drench" — remove
- Any reference to Promise being physically ill

### References to add/adjust:
- "Riley's fall" or "the backing accident" as the touchstone event
- Promise's regression after the incident
- The discovery that astride position is the specific trigger
- Riley's recovery arc and what it meant for Sage's feelings
- "He trusts you. Not people — you" as the lesson learned

### Chapters likely containing colic references to check:
- Ch 24 (current version references "after the colic")
- Ch 25 (may reference recovery)
- Ch 26-32 (Book IV — check all for backstory references)
- Ch 33-39 (Book V — check for any mentions)
- Bible and all summary documents (update last)

## The Emotional Arc This Creates

**Ch 20:** Warning (enthusiasm overriding caution)
**Ch 21:** Decision (who rides first — the wrong choice made for logical reasons)
**Ch 22:** Crisis (Riley thrown, Promise regresses, Sage's world fractures)
**Ch 23:** Aftermath (double guilt, caring for Riley, back to square one with Promise)
**Ch 24:** Rebuilding (Sage as the rider — because she was always the right one)
**Ch 25:** Solution (sidesaddle — meeting him where he is, born from specific trauma)

This arc does everything the colic arc was supposed to do (provide a setback, teach humility, force recalibration) but does it BETTER because:
- It comes from a human decision, not a random medical event
- It deepens two relationships simultaneously (Sage/Promise AND Sage/Riley)
- It creates the specific psychological logic for the sidesaddle solution
- It parallels the Thunder crisis in a way that shows Sage's pattern (enthusiasm → harm)
- It makes Sage the right rider for Promise for EARNED reasons, not default ones
- Riley's generous response to being "replaced" as rider shows character depth

## Interaction with Other Passes

- **Pass 1 (Rebecca):** Rebecca's response to this crisis should use her Layer 1 characterization — focused on the horse's psychology, systematic in her analysis of what went wrong, with Jennifer helping process the emotional dimensions.
- **Pass 2 (Endings):** New chapter endings should follow Pass 2 principles — end on concrete moments, not reflective monologues.

---

# REVISION PASS 4: Thunder Injury — The Tack Inspection Chain

## The Problem

In the current Ch 13, Sage's injury to Thunder comes from a single moment of frustration — she pulls too hard on the reins. This reads as a momentary lapse in emotional control. While the lesson about controlling your emotions is valid, the injury itself is somewhat generic: any rider could lose their temper once. It doesn't carry enough weight to justify Rebecca's severity or the magnitude of the consequence.

## The Revision

Sage's failure with Thunder should be a **chain of negligence**, not a single moment. Three linked failures:

1. **Weeks before:** Riley teaches tack inspection as fundamental. Check every piece of equipment before every ride — run your fingers along the bit, check the leather for cracks, feel for sharp edges, examine stitching. "The horse can't tell you his bit is broken. That's YOUR job." Sage learns this, does it at first, then starts cutting corners as she gets comfortable and confident.

2. **Morning of the crisis:** Sage tacks Thunder in a rush because of the heat schedule. Doesn't run her fingers along the bit the way Riley taught her. There's a rough spot on the edge of the bit — a burr of metal, possibly from Thunder mouthing it against his stall door, possibly there for days. Proper inspection would have caught it instantly. Sage doesn't check.

3. **The fall:** When Thunder rears, Sage's instinct is to grab the reins and hold on — arm strength, full body weight, trying not to fall. She hangs on his mouth with everything she has for those terrible seconds before gravity wins. The combination of the sharp burr + her full weight on the reins is what creates the actual cut and the inflammation. The injury isn't from one hard pull in frustration — it's from a defective bit she should have caught, made catastrophically worse by her instinctive grab during the rear.

## Why This Is Stronger

- **Thunder's "difficult" behavior is recontextualized.** He was heavy in her hands from the first stride because the burr was already irritating his mouth. He wasn't being lazy — he was trying to get away from the pain. Every signal Sage reads as "testing" or "being difficult" was actually "something is wrong with my bit." She missed all of it because she'd skipped the inspection.
- **The lesson expands.** It's not just "control your emotions in the moment." It's "every part of this work matters. The unglamorous preparation matters as much as the performance. The shortcuts you take when no one's watching are the ones that hurt someone eventually."
- **Rebecca's severity is more justified.** A momentary lapse of temper is forgivable. Failing to do a basic safety check — something she was explicitly taught — is a more fundamental failure of care. Rebecca's harshness lands harder because the failure is more systemic.
- **The Thornton parallel deepens.** Thornton's cruelty isn't just rage — it's systematic neglect of the horse's wellbeing in pursuit of results. Sage's failure is obviously far less severe, but it's on the same spectrum: prioritizing the exciting work over the boring care.
- **It sets up the Riley-fall pattern (Pass 3).** Sage's character flaw is now clearly "skipping the foundation work out of eagerness." With Thunder, she skips tack inspection. With Promise's backing, she pushes past Riley's reservations. Same pattern, escalating consequences.

## What Changes

### Chapters That Need New Content (Seeding):

**Ch 5 (Lessons and Watching) — Plant the lesson:**
Add a passage during Sage's first riding lesson where Riley teaches tack inspection as part of the pre-ride routine. Riley should be specific and emphatic: run your fingers along the bit, check for rough edges, examine every buckle and strap. "The horse can't tell you his equipment is wrong. He can only tell you it hurts, and by then the damage is done." This should feel like one detail among many in the overwhelming flood of new information Sage is absorbing.

**Ch 6 (Three Weeks) — Reinforce briefly:**
A brief beat of Sage doing her tack inspection properly, perhaps mechanically, as part of the montage of her growing competence. She's doing it right because it's still new and she's still careful about everything.

**Ch 9 (First Day of Summer) — Show compliance:**
When Sage tacks Thunder for the first time, she should do the inspection carefully. Perhaps she finds nothing wrong, but the act of checking is visible. Riley watches and nods approval. This establishes that she knows how and has been doing it.

**Ch 10 or 11 — Show the shortcut beginning:**
A brief moment — one or two sentences — where Sage is in a hurry and does a faster, less thorough inspection. Maybe she checks the girth but skims over the bit. Nothing goes wrong. The shortcut is rewarded with efficiency and no consequences. This is how complacency builds.

### Chapter 13 (Summer Heat and Tempers) — The Crisis Chapter:

**New tacking-up scene (before the ring):**
Between fetching Thunder from the paddock and arriving at the exercise ring, add a scene where Sage tacks him up. The heat makes her rush. She's irritable, sweating, wanting to get through the work before it gets worse. She pulls the bridle on without running her fingers along the bit. Doesn't check the edges. The narrator should note the omission without commentary — just show her skipping it. "She bridled him with quick efficiency, cinching the noseband, adjusting the browband, her fingers moving through the motions without the careful inspection Riley had drilled into her in those first weeks."

**Recontextualize Thunder's behavior:**
Everything Thunder does from the first stride is now a response to the burr. "Heavy in her hands, leaning on the bit" = trying to ease pressure on the side where the burr is cutting. "Between a jog and a stomp" = moving erratically because his mouth hurts. "Tossed his head and yanked the bit" = trying to get rid of the thing that's hurting him. Riley's calls of "more leg" and "send him forward" should still be there — Riley can't see the bit from across the ring and is reading the behavior as laziness. Neither of them knows the bit is wrong because neither of them checked.

**The rear — Sage grabs the reins:**
When Thunder rears, revise the mechanics: Sage's instinct is to grab the reins and hold on. Not just pulling in frustration — *clinging* to the reins as her only anchor when gravity takes her backward. Her full weight hangs on his mouth for two or three terrible seconds before she slides off. The rein-grab is survival instinct, not cruelty, but the effect is the same: the defective bit, already irritating his mouth, is now driven into the cut with the force of her entire falling body.

**The discovery — examining the bit:**
When Sage checks Thunder's mouth (the existing scene), add the moment of discovery. As she unbuckles the cheekpieces to examine the damage, she sees it — or rather, feels it. A rough edge on the left side of the bit, a burr of metal sharp enough to catch on her fingertip. Something that would have been instantly obvious if she'd done the inspection Riley taught her.

This is the moment the lesson lands. Not "I lost my temper" but "I didn't check his equipment. He was in pain from the moment I put the bit in, and I read every signal wrong because I'd already failed him before I ever got in the saddle."

**Rebecca's response — adjusted:**
Rebecca's analysis should now include the equipment failure. She should examine the bit herself — systematically, the way she examines everything — and identify the burr. Her response should be even more devastating because it's not just about emotional control: "This was preventable. Riley taught you to check your tack before every ride. When did you stop doing that?"

The lesson becomes: "Controlling your emotions in the ring is important. But the failure started in the tack room. The failure started every time you decided the inspection didn't matter. Every time you hurried through it because you were eager to get to the riding. The riding is the easy part, Sage. The care — the meticulous, unglamorous, every-single-time attention to the details that keep your horse safe — that's the foundation. Without it, nothing else you do matters."

**Riley's response — adjusted:**
Riley should feel the guilt too — they were in the ring, calling instructions, and they didn't catch it either. But Riley's guilt is different: they taught the lesson and it wasn't enough. Maybe a moment where Riley examines the bit and goes quiet. "I should have checked it myself before the lesson." Then, to Sage: "But you knew to check. I taught you. And you stopped doing it."

### Chapter 14 (Returning to the Saddle) — Aftermath:

Add a beat where Sage returns to rigorous tack inspection — checking every piece of equipment with painful thoroughness. Make it a visible part of her routine, something she does with almost obsessive care now. This becomes part of her rebuilding — not just emotional control, but foundational discipline.

### Chapters 15-17 — Continued:

Brief references to Sage's now-meticulous tack inspection routine. One mention is enough per chapter — a sentence showing her checking the bit, running her fingers along it, making sure. It's become ritual. Atonement through diligence.

## Dialogue Additions for Rebecca (with Pass 1 characterization)

Rebecca's response should reflect her Layer 1 traits: systematic analysis, following the causal chain, precision. She should examine the bit the way she'd examine a horse — methodically, completely.

Example lines (adapt to fit revised Ch 13):
- "When did you last check this bit? Really check it — fingers along every edge, the way Riley showed you?"
- "This burr has been here for some time. Days, perhaps. Every ride he's done with this in his mouth, he's been feeling it. And every ride, you didn't notice."
- "The emotional control matters. Of course it matters. But the failure didn't start in the ring, Sage. It started in the tack room. It started every time you decided the preparation was less important than the performance."

## The Chain of Failure (Summary)

For Claude Code's reference, the complete causal chain:

1. Riley teaches tack inspection → Sage learns and practices it (Ch 5-6)
2. Sage becomes competent and confident → starts cutting corners (Ch 10-11)
3. Heat day, rushing → skips bit inspection entirely (Ch 13)
4. Burr on bit causes Thunder pain from first stride → Sage reads pain as laziness
5. Thunder escalates communication → Sage escalates force
6. Thunder rears → Sage grabs reins to stay on, hanging full weight on damaged bit
7. Thunder's mouth cut by combination of defective bit + Sage's weight
8. Discovery: the burr that would have been caught by the inspection she skipped

**The lesson isn't just "control your emotions." It's "the care is the work. All of it. Every time."**

## Interaction with Other Passes

- **Pass 1 (Rebecca):** Rebecca's examination of the bit should use her Layer 1 traits — systematic, precise, following the causal chain to its origin. Her harshness is even more justified because this failure is methodical, not just emotional.
- **Pass 2 (Endings):** Ch 13's ending should still follow Pass 2 principles. Don't add a new reflective monologue about tack inspection.
- **Pass 3 (Riley's Fall):** The tack inspection pattern establishes Sage's character flaw — cutting corners on foundation work out of eagerness. The Riley-fall arc echoes this same flaw at a larger scale.

## Execution Order

This pass should be done BEFORE Pass 3, since it establishes the pattern that Pass 3 escalates. The seeding in Ch 5-6 should be done first, then Ch 9-11, then Ch 13, then Ch 14-17.

---

# REVISION PASS 5: Riley's Pronouns — They/Them → He/Him

## The Change

Riley's pronouns change from they/them to he/him throughout the entire manuscript. This is primarily a mechanical find-and-replace operation, but several passages need more careful revision where the pronoun choice is discussed, explained, or narratively significant.

## Rationale

Riley presents as male — binds his chest, wears men's clothing, and asks to be addressed with masculine terms. In 1813, a person living this way would have been understood and addressed as male by the people around them who respected that choice. He/him is both more period-authentic and creates cleaner, less ambiguous prose than singular they/them, which produces micro-jolts in the historical voice every time it appears.

Riley's identity remains what it has always been — a person born in a female body who lives as male. The pronoun change doesn't alter his character; it gives him the pronoun that his 1813 world would have used for someone living as he does.

## Mechanical Replacement

### Global find-and-replace across all chapters:

**Pronoun substitutions (case-sensitive):**
- "they" → "he" (when referring to Riley as subject)
- "them" → "him" (when referring to Riley as object)
- "their" → "his" (when referring to Riley as possessive)
- "theirs" → "his" (possessive pronoun)
- "themself" → "himself" (reflexive)
- "themselves" → "himself" (reflexive, if used for singular Riley)

**CRITICAL: Context-check every replacement.** "They" and "their" are also used for actual plurals (multiple people, groups of horses, etc.) throughout the manuscript. Do NOT blindly replace every instance. Each replacement must be verified to be referring to Riley specifically.

**Method:** Search for "Riley" in each chapter. Read surrounding paragraphs. Identify every pronoun that refers to Riley and replace individually. This is safer than regex.

### Verb agreement changes:
When "they" (singular) becomes "he," verb forms must change:
- "they were" → "he was"
- "they are" → "he is"  
- "they have" → "he has"
- "they walk" → "he walks"
- "they don't" → "he doesn't"
- "they've" → "he's" (context permitting)
- "they'd" → "he'd"

## Passages Requiring Careful Revision (Not Just Find-Replace)

### Chapter 1: Rebecca's Carriage Speech

**Current text:**
"Riley was born in a female body, but she is not a woman in the way most understand the term. She binds her chest and wears men's clothing and asks to be addressed with masculine terms."

**Revised:**
"Riley was born in a female body, but he is not a woman in the way most understand the term. He binds his chest and wears men's clothing and lives as a man. I employ him because he is the finest horseman I have ever met, and because he understands better than anyone what it means to be forced into a shape that does not fit one's soul."

**Note:** The shift from "asks to be addressed with masculine terms" to "lives as a man" is important. With he/him pronouns, Riley isn't *requesting special accommodation* — he's simply living as male, and the household respects that as fact. Rebecca's explanation to Sage is now: this person was born female but is male, here's why, moving on. The narration from this point forward uses he/him without further comment because that's simply who Riley is.

### Chapter 1: Riley's Introduction

**Current text:**
"They turned to Sage, and their eyes—a startling blue in a sun-weathered face—held neither pity nor excessive curiosity."

**Revised:**
"He turned to Sage, and his eyes—a startling blue in a sun-weathered face—held neither pity nor excessive curiosity."

**Also:** Riley's initial description — "a person in rough working clothes, moving with the economical grace of someone comfortable in their body" — revise to "comfortable in his body." The phrasing "a person" can stay since it reflects Sage's initial uncertainty before Rebecca's explanation, but "their" must become "his."

### Book 1 Summary: Riley's Description

**Current text:**
"Born in female body, binds chest, wears men's clothing, uses masculine terms"

**Revised:**
"Born in female body, binds chest, wears men's clothing, lives as male, he/him pronouns"

### Chapter 4 / Chapter 5 / Early Chapters: Sage's Perception

In early chapters, Sage may initially perceive Riley with some uncertainty before Rebecca's explanation settles things. After Rebecca's carriage speech in Ch 1, Sage (and therefore the narration) should use he/him consistently without internal commentary or hesitation. There should be NO scene where Sage "adjusts" to using male pronouns — Rebecca told her, she accepted it, done. The household treats this as fact, not as a topic requiring ongoing negotiation.

### Chapter 29: Riley's Backstory

**Current text references "three rejected marriage proposals" and Riley saying "None of them saw me."**

This works even better with he/him. Riley is a man who was proposed to by men who saw a woman. "None of them saw me" now means: they saw a woman they could marry, not the man standing in front of them. The rejected proposals are Riley refusing to disappear into a female identity for someone else's comfort. No revision needed to the substance — just pronoun cleanup.

### Chapter 31: Riley and Sage's Intimate Scene

Riley staying the night for comfort. With he/him, this reads as a man and a woman sleeping together (chastely). Check that the description of the scene doesn't contain anything that would be confusing with male pronouns — e.g., if there are references to Riley's body that relied on they/them ambiguity, those may need slight adjustment. The scene should work naturally with he/him.

### Bible and Summary Documents

Update all character descriptions of Riley:
- Change all pronoun references
- Change "non-binary head groom" → "head groom" (or "head groom, born female, lives as male")
- Update speech pattern notes
- Update relationship descriptions

## What This Changes Thematically

Very little, and that's the point. Riley is the same person. The household's radical acceptance of Riley is the same. The only thing that changes is that the narration now uses the pronoun Riley's 1813 world would have used for a person living as he does — which is the pronoun he himself would have expected and wanted.

If anything, he/him makes the household's acceptance MORE visible, not less. In a world where everyone can see Riley was born female, the consistent use of he/him by everyone at Hartwell — without hesitation, without correction, without comment — is itself a radical act of respect. It's the pronoun equivalent of the novel's core philosophy: we see you as you are, not as the world says you should be.

## Execution Order

This pass can be done at any point — it's independent of Passes 1-4. However, it should be done AFTER any passes that rewrite substantial prose (Passes 3 and 4) to avoid doing pronoun work on text that will later be replaced. 

**Recommended:** Do this pass last, after Passes 1-4 are complete, as a final cleanup sweep across the finished manuscript.

## Checklist for Completion

After all replacements, verify:
- [ ] Every chapter searched for Riley references
- [ ] All singular they/them/their referring to Riley → he/him/his
- [ ] All verb agreements updated (they were → he was, etc.)
- [ ] Ch 1 introduction passage revised
- [ ] Ch 29 backstory passage checked (should work as-is)
- [ ] Ch 31 intimate scene checked
- [ ] No remaining they/them referring to Riley (search "Riley.*they" and "they.*Riley" patterns)
- [ ] Bible updated
- [ ] All five summary documents updated
- [ ] No accidental changes to actual plural "they" (groups, horses, etc.)

---

# REVISION PASS 6: [RESERVED]

*This section will be filled in during planning for the next cross-chapter revision.*
