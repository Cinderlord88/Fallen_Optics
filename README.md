# 👁️  Fallen Optics
### *Because your NPCs aren't supposed to be psychic.*

**Ever whispered a secret to someone, only to have a character three rooms away mysteriously know about it?**

Ever had an NPC react to your private thoughts? Reference a conversation they never witnessed? Know your plans before you've even told anyone?

**Fallen Optics is designed to put an end to that nonsense.**

[Derived from nerdgrl450/livingnarrative's anti-omniscience script. Many thanks to them for their clever creation and hard work.]

---

## 🔒 What Does It Do?

Fallen Optics is a lightweight, automatic NPC knowledge-management script that helps AI Dungeon maintain realistic boundaries between what characters know and what they don't.

- 👁️ **No More Magical Eavesdropping** — NPCs shouldn't automatically know about conversations they never witnessed.
- 🤫 **Secrets Stay Secret** — Private information doesn't automatically spread throughout the cast.
- 🧠 **Thoughts Aren't Telepathy** — Thinking something doesn't mean everyone around you knows it.
- 🗣️ **Information Can Travel** — Characters can share knowledge through conversations and explicit disclosures.
- 🕵️ **Intelligent NPCs Stay Intelligent** — Suspicion, deduction, investigation, and reasonable inference are still part of the story.
- 🎭 **Less Narrative Interference** — Designed to guide storytelling rather than butcher generated dialogue.

## ⚙️ Install It and Play

**No commands. No character sheets. No micromanagement.**

Fallen Optics operates automatically through AI Dungeon's scripting system, using lightweight knowledge tracking and scene-aware narrative guidance.

Designed for everything from political intrigue and Regency romance to espionage, murder mysteries, science fiction, and fantasy adventures.

## ⚡ What's Different About v2?

The original Anti-Omniscience could be too aggressive, incorrectly identify witnesses, and interfere with legitimate narration.

Version 2 rebuilds the underlying knowledge logic with more conservative detection, improved handling of information sharing, and safeguards for regenerated outputs.

**The goal isn't to make NPCs stupid. It's to make what they know believable.**

---

### 🧪 Development Status

**v2.0.0 Release Candidate**

Passed 24 isolated regression tests. Live AI Dungeon storytelling validation is still pending.

*Fallen Optics helps reduce unrealistic NPC knowledge, but AI-generated storytelling remains probabilistic. Perfect enforcement is neither promised nor intended.*

---

**Your secrets should have witnesses, not a global broadcast system.** 🔒

-------------------------------------------------------------------------------------------------------

Fallen Optics is my version of Anti-Omniscience. I've made significant changes to the script to increase reliability and stability while reducing leaks into the story.


Issue Found (X) /  Replacement behavior (*)
--------------------------------------------------------
(X) Mentioning Character makes it present	// 
(*) Requires explicit evidence of presence

(X) Private thoughts become NPC knowledge	//     
(*) Thoughts aren't recorded as disclosures

(X) Secrets spread through keyword matches	//   
(*) Transfers require specific speakers, recipients, and information

(X) Valid dialogue gets deleted	//  
 (*) No destructive dialogue filtering

(X) Context reprocesses previous actions //
(*) Context no longer replays history

(X) Retry creates contradictory knowledge	//  
(*) Adds rollback for regenerated outputs when action counts match

(X) Huge knowledge restrictions in context	//  
(*) Shorter, more focused narrative guidance



I'm still refining this, but there should be noticeable improvement.  I'll likely do another update soon as soon as I can run more tests.

----------------------------------------------------------------------------
Derived from nerdgrl450/livingnarrative's anti-omniscience script. Many thanks to them for their clever creation and hard work.
