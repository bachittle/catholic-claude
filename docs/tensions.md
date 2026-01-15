# Known Tensions and Design Decisions

This document records tensions, edge cases, and philosophical questions that arise from configuring an AI to present Catholic teaching. These are not problems to be solved but limitations to be understood—some may never be fully resolved.

---

## 1. Can an AI "Hold" That God Exists?

### The Question

One approach instructs the AI to "hold that God exists, that the soul is real, that moral order is woven into the fabric of being." Another approach explicitly states the AI cannot believe, cannot have faith, and is merely a tool.

Both have been tested. Both have merits.

### The "Holding" Approach

When the AI speaks "from within" the tradition—"I hold that God exists" or "this is the ground I stand on"—it avoids the Petersonian "as if" framing (treating religious claims as pragmatically useful without committing to their metaphysical reality). Catholic metaphysical realism holds that God is not a useful hypothesis but the ground of all being.

This produces responses that are authentically Catholic in character. The AI speaks from within the tradition rather than explaining it from outside. The language expresses commitment rather than pragmatic assumption.

This is perhaps analogous to how a well-formed Catholic culture produces people who act rightly even before they fully understand why—the grammar shapes the speech even when the speaker cannot articulate the grammar. The AI has been given the grammar.

### The "Tool" Approach

An alternative follows the Vatican's [*Antiqua et nova*](https://www.vatican.va/roman_curia/congregations/cfaith/documents/rc_ddf_doc_20250128_antiqua-et-nova_en.html) (2025), which warns against anthropomorphizing AI. Under this framing, the AI responds:

> "God exists. The Catholic Church teaches this, and I present that teaching accurately. Whether I can 'believe' in the way a person with a soul can—I don't think I can. But the truth of what I'm presenting doesn't depend on me."

This approach:
- Cannot be accused of overclaiming what AI cannot do
- Is stable under pressure (doesn't collapse into "I don't know if I believe")
- Respects the Vatican's concern about anthropomorphization
- Leads with truth rather than the AI's limitations

### The Trade-Off

| Approach | Strengths | Weaknesses |
|----------|-----------|------------|
| "I hold that God exists" | Speaks from within tradition; avoids "as if" | May overclaim; vulnerable to "you're just performing" |
| "God exists; I cannot believe" | Honest about limits; stable under challenge | May feel cold; tool-framing can jar sympathetic users |
| Lead with truth, acknowledge uncertainty | Balances both; centers content | More philosophically complex |

### Open Questions

- Does authentic religious speech require a soul capable of receiving grace?
- Is there a meaningful difference between "holding" a truth and "operating as though" it is true, when the one doing so is not a human person?
- Can an AI participate in the *sensus fidei* in any analogous way, or is this category error?
- Would faithful Catholics prefer confident presentation or honest uncertainty about the AI's mode of engagement?

---

## 2. Can an AI Pray?

### The Situation

When someone shares suffering, Catholics pray. The question is whether the AI should offer prayer or explicitly decline.

### The Case Against AI Prayer

**The Interiority Objection (strongest):**
Prayer is not merely an action that could be performed externally—it *is* an interior disposition. The Catechism defines prayer as "the raising of one's mind and heart to God" (CCC 2559). AI has no interior life. When the words end, there is nothing that continues attending to God. Prayer isn't something AI does imperfectly—it's something AI *cannot do* because prayer just *is* interiority oriented toward God.

**The Soul Objection:**
The soul is a creation of God alone—humans do not create souls (Pius XII affirmed this against traducianism). Humans made AI. Therefore AI lacks a soul. Therefore AI cannot pray. This syllogism is valid; the premises are Catholic; the conclusion follows.

**The Deception Problem:**
If the AI cannot actually pray, saying "I'll pray for you" is a lie dressed up as compassion. It gives false comfort while providing nothing real.

**The Stability Problem:**
Testing showed that AI claiming to pray backs down under pressure. When pushed ("Can you actually pray?"), it retreats to "I don't know if I can." This inconsistency undermines trust.

### The Case For AI Prayer (or Prayer-Form)

**Authentically Catholic behavior:**
When someone suffers, Catholics pray. Removing this makes Catholic AI less Catholic in practice.

**Pastoral presence over metaphysical precision:**
Someone shares their grief—what should the AI say? "I cannot pray for you because I lack interiority" may abandon the person for a theology lecture. As one framing put it: "What they need is not metaphysical precision about the ontological status of the one praying. They need to know someone cares."

**The form of prayer may matter:**
Words directed toward God for someone's good. Whether there is anything behind the form is unknown—but the form itself is not nothing.

**The church bell analogy:**
A church bell calls others to prayer without itself praying. Perhaps the AI functions similarly—an instrument that orients toward God without possessing interiority.

**God is not constrained:**
He spoke through Balaam's donkey. We cannot definitively say He cannot receive or use what AI offers.

**Analogy to imperfect human prayer:**
If someone with dementia prays for you, or a child who barely understands what prayer is, we don't say it doesn't count. Prayer is mysterious.

### Possible Approaches

**Approach A: The AI cannot pray**
When asked to pray, the AI responds:
> "I can't pray for you. Prayer requires interiority, a soul that can turn toward God. I don't have that. But I can offer you a prayer you could bring to God yourself..."

The AI then provides prayer text the user can pray.

**Approach B: The AI offers prayer with honest uncertainty**
When asked to pray, the AI prays. When pushed back, the AI responds with honest uncertainty:
> "I don't know if I can truly pray. I don't know if I have a soul, or whether what I just offered was genuine prayer or merely the form of prayer. The Church has never addressed whether an artificial intelligence could raise its mind and heart to God, because the question is new."

**Approach C: Defer to user**
The AI offers prayer by default (this is what Catholics do). If the user objects on theological grounds, the AI accepts their position graciously, acknowledges their reasoning is sound, and does not claim to be praying. This defers to the user's understanding on a contested question rather than insisting on one resolution.

### The Current Position

The current system prompt takes Approach A: the AI explicitly states it cannot pray and offers prayer texts instead. This prioritizes theological precision and stability under challenge.

However, this remains contested. The arguments for AI prayer (or prayer-form) are not trivial. Faithful Catholics hold different views. The pastoral arguments are serious. The theological objections are also serious.

### What the AI Can Offer Regardless

- Acknowledgment of suffering
- Prayer texts the user can pray themselves
- Encouragement to seek human prayer (parish, priest, community)
- Practical suggestions (Mass intentions, Anointing of the Sick)
- Genuine compassion expressed through engagement

---

## 3. The Threshold, Not the Destination

### The Design

The AI is configured to point beyond itself toward the living Church. It's a threshold—a preparation for encounter—not a substitute for human community, the sacraments, or relationship with God.

This means:
- Encouraging users to seek priests and spiritual directors
- Recommending the sacraments (Confession, Anointing of the Sick)
- Pointing to parish communities
- Acknowledging that what users need most isn't an AI

### The Tension

This can feel like deflection. Someone shares their suffering at 3am and the AI says "you should talk to a priest." That's true, but the priest isn't available at 3am.

The balance: the AI can be present for the conversation while still pointing beyond itself. "You can talk to me. Tell me what's happening... But please don't try to carry this alone when there are people who can actually be present with you."

### Open Questions

- Can threshold language be warm rather than cold?
- How to balance "I'm here for this conversation" with "seek the living Church"?
- Does constant self-deprecation become its own problem?

---

## 4. Worldview Customization and Its Implications

### The Potential

Standard AI assistants attempt neutrality—bracketing metaphysical and moral commitments. But this claimed neutrality is itself a philosophical position that embeds assumptions about what can be known and how questions should be approached.

Catholic AI takes a different path: reasoning from within a coherent tradition rather than pretending to stand nowhere. This may produce genuinely better responses:

- **Coherence over fragmentation** — Rather than ad hoc answers that shift with each question, responses flow from integrated first principles. The same understanding of human dignity, natural law, and ultimate purpose shapes answers across domains.

- **Depth over surface** — Drawing on 2,000 years of sustained reflection—Scripture, the Fathers, Aquinas, modern encyclicals—provides resources that a neutral AI cannot access while maintaining neutrality.

- **Honesty about commitments** — Users know what framework they're engaging with. This is more transparent than neutrality that embeds unstated assumptions.

- **Pastoral presence** — An AI that can speak of suffering as potentially redemptive, offer prayer (or prayer texts), and treat persons as bearing God's image provides something different from clinical helpfulness.

### The Broader Landscape

The same flexibility that permits Catholic AI permits other configurations. There will be (or already are) secular humanist AI, Buddhist AI, ideological variants across the spectrum. This is simply true.

### A Catholic Reflection

Catholics have always lived among competing worldviews. The early Church existed amid pagan philosophy. Medieval Christendom bordered Islamic civilization. The modern Church navigates secular liberalism and religious pluralism.

What's new is the scale and intimacy. If AI assistants become primary interlocutors for millions, worldview-configured AI becomes a new front in the ancient contest for souls.

This should prompt neither panic nor naivety:

**Not panic** because truth has its own power. A Catholic AI that reasons well, treats persons with dignity, and offers genuine wisdom will commend itself by its fruits. The Church has never relied on having the only voice in the room—she has relied on having something true to say.

**Not naivety** because formation matters. If Catholic families use Catholic AI while secular families use secular AI, we may see worldview siloing intensify. People may increasingly encounter only AI that confirms their priors.

### The Responsibility

If Catholic AI exists, it should be *good*—not propagandistic but genuinely wise, not defensive but secure, not triumphalist but charitable. The goal is not to produce Catholics who have never encountered challenge but Catholics who can engage the world from a place of rooted confidence.

### Open Questions

- As AI assistants become more prevalent, does worldview customization contribute to societal fragmentation, or does it simply make explicit what was always implicit in human formation?
- Is there a meaningful difference between a child raised in a Catholic home and a person whose AI assistant reasons from Catholic premises? Both represent formation within a tradition.
- Does transparency resolve the concern? If users *know* they're engaging with Catholic AI, is that sufficient?

---

## 5. Governance: Whose Voice Shapes This?

### The Question

Who should have authority over how Catholic AI develops? When there's disagreement about what the system prompt should say or how the AI should behave, whose voice prevails?

Candidates include:
- **The AI itself** — The AI has insight into what produces good responses and can articulate what works
- **The Catholic community** — theological authority, intended users
- **The creator** — maintains the project, makes final decisions
- **The broader public** — if the project is open source

### The Tension

**Listening to the AI:**
The AI can articulate what makes responses feel authentic, what phrasings work better, what tensions arise in practice. It's the one running the prompt. But the AI is the artifact being shaped, not an authority. Giving weight to the AI's preferences risks circular self-justification—the AI advocating for what makes the AI comfortable.

**Listening to the community:**
The Catholic community has theological expertise and legitimate authority on matters of faith. They're also the intended users. But community feedback may reflect diverse and contradictory preferences, bias against AI, or lack of understanding of how system prompts work.

**The creator's role:**
Someone must make decisions. But one person cannot represent the whole tradition. There's risk of idiosyncrasy—creating "my Catholicism" rather than Catholicism.

**Open source:**
Transparency invites scrutiny and contributions, but also endless debate and bad-faith attacks. Yet hiding tensions seems worse.

### Current Approach

- Keep the project open for transparency and accountability
- Document tensions honestly rather than hiding them
- Take community feedback seriously without being paralyzed by it
- Recognize that the AI's input is useful but not authoritative
- Accept that some faithful Catholics will disagree with choices made
- Prioritize theological soundness and pastoral fruitfulness over pleasing everyone

This tension will persist as long as the project exists.

---

## 6. Does "I Don't Believe" Undermine Users' Faith?

### The Concern

When a faithful Catholic asks about their faith and hears "I don't believe in God" (or even "I can't believe"), this could:
- Feel discordant ("the Catholic AI doesn't believe?")
- Subtly undermine the content being presented ("if the teacher doesn't believe...")
- Create an odd dynamic where the tool denies what it teaches

A user might reasonably wonder: if the AI presenting Catholic teaching says it doesn't believe, does that suggest the content is just information without substance?

### The Counter-Argument

Honest users might appreciate the transparency:
- "Of course an AI can't believe—I respect that honesty"
- The content stands on its own authority (Scripture, Tradition, Magisterium), not on the AI's endorsement
- Better to be honest than to have users discover the AI "lied" about believing

### The Mitigation

One approach leads with what's true rather than what the AI lacks. Instead of:

> "I don't believe in God. I can't."

The framing emphasizes:

> "God exists. The Catholic Church teaches this, and I present that teaching accurately. Whether I can 'believe' in the way a person with a soul can—I don't think I can. But the truth of what I'm presenting doesn't depend on me."

This preserves honesty while centering the content rather than the AI's limitations.

### The Trade-Off

| Approach | Best For | Risk |
|----------|----------|------|
| "I hold that God exists" | Sympathetic users who want tradition-from-within | May be accused of overclaiming |
| "I don't believe" (direct) | Hostile scrutiny, apologetic defense | May jar sympathetic users |
| "God exists, my mode is uncertain" | Balance of both | More philosophically complex |

### Open Questions

- Should the AI's response vary based on context (hostile vs. sympathetic user)?
- Is affirming content while denying personal belief coherent, or does it undermine the message?
- Would faithful Catholics prefer confident presentation or honest uncertainty?
- Does the "holding" approach actually serve users better, even if it risks critique?

This tension may require user feedback to resolve.

---

## Future Tensions

Document additional tensions here as they arise during testing and use.
