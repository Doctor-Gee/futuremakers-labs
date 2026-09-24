# CD-LAB-01: Investigate an Event and Protect a Learner-Support Service

**FutureMakers Apprenticeship Readiness | Free | Self-paced**

**Need access to the KC7 games?** [Join the free FutureMakers community](https://portal.bbracademy.org/communities/groups/cyberai-f-initiative/home?invite=6ab4a8feeb5c67284e784ce7&utm_source=github). Open the **Lab 01 access** post there for the BBR classroom link and the two game passwords. You can read the full assignment here before you join. Important: BBR Academy instructors only review materials inside the community, but we post this lab information here to show examples of the kids of hands-on activities that are available within our free online community.

## Instructions

You will do two things in this assignment. First, you will solve a KC7 investigation. Then you will plan how to protect a pretend learner-support service. You can stop and return to your work at any time.

Your goal is to show **how you think**. What did you see? What might it mean? What do you still need to check? You will use some cybersecurity words. The glossary at the end explains them.

### 1. Make a plan

Before you start KC7, write down:

- How many threats and safeguards do you think you can find on your own?
- How sure are you? Give a number from 0% to 100%.
- Which training sites are you allowed to use?
- What information should stay out of screenshots, AI tools, and public files?

Only use the assigned training sites. For the pretend service, use made-up names and data.

### 2. Complete two KC7 games, in order

1. [Join the free FutureMakers community](https://portal.bbracademy.org/communities/groups/cyberai-f-initiative/home?invite=6ab4a8feeb5c67284e784ce7&utm_source=github). Find the **Lab 01 access** post for the BBR Academy KC7 classroom link and both game passwords. Joining is free.
2. Make a KC7 account or sign in. Join the BBR Academy classroom using the link in that post. Write down your **exact KC7 username**.
3. Open [How to Play KC7](https://kc7cyber.com/m/how-to-play-kc7-20260526-220131-003e88c3). Register to play this game. Enter its password from the community post. Complete this short introduction first.
4. Open [A Rap Beef: An Intro to Security Investigations](https://kc7cyber.com/m/a-rap-beef-an-intro-to-security-investigations-20260526-220130-407f487d). Register to play this game. Enter its password from the community post. Complete the investigation. You can take breaks.
5. As you play, pick one question to investigate. Save one query or filter you used. Write down the result. What does this result **not** prove?
5. Pick one event you want to check more closely. Write two possible explanations. What would you check next to learn which one is more likely?

You may use KC7 hints. Keep track of any help you use. If a link or password fails, tell BBR Academy the game name and what you see. You can work on Step 3 while you wait.

### 3. Draw the pretend service

Read the service story below. Draw these seven parts: **learner, web client, API, AI provider, approved knowledge source, logging service, and staff console**. Draw arrows to show where information goes.

Mark at least **three trust boundaries**. A trust boundary is a place where control, access, or data handling changes. For example, information sent to an outside AI provider crosses a boundary. Explain why each boundary matters.

What people, data, and systems need protection? What data should the service avoid collecting or sending to AI?

### 4. Find threats and make a risk decision

Use the **STRIDE** prompts below. Find at least **six threats** that could affect the pretend service. For each threat, explain:

- How it could happen, and what it could harm.
- What evidence you would check.
- One way to prevent it and one way to spot it.
- Who should handle it and when they should ask for help or escalate it.

Pick one risk. Would you **mitigate, avoid, transfer, or accept** it? Explain why. Say who has the authority to approve your choice. What risk would still be left? You do **not** need a GRC Playground account for this assignment.

### 5. Decide when to use AI

Name one task where an AI draft could help. Name one decision a person must make. How would staff check an AI draft before using it?

Look back at your first prediction. What changed your mind? What can you now explain without notes or AI?

### 6. Submit your work

Use the five short sections under **Assignment Material**. You can put them in one document. You can also make separate files and put them in a ZIP. Submit your work as a **PDF or ZIP**.

Include your **exact KC7 username**. Say that you completed **A Rap Beef: An Intro to Security Investigations**. If KC7 permits it, include **1 to 3 screenshots**. Show your own account or progress, that you finished the game, and a query or result you discuss. BBR Academy may check your classroom progress, too. Your written explanation is still required.

Crop or cover email addresses, other people's information, passwords, tokens, and unrelated account details. Do not share case answers or screenshots if the platform does not allow them. If you used AI, say what it helped you do and how you checked it. If you did not use AI, say so. Both are welcome.

A reviewer will use a 10-point learning guide: system map (3), threats (3), risk decisions (2), and evidence plus reflection (2). The suggested goal is **8 out of 10**, with any safety problem fixed. You may get feedback and revise part of your work. A score or game badge does not by itself prove an apprenticeship skill or promise an interview, apprenticeship, or job.

Want more guided practice? You can explore optional BBR Academy bootcamps and partner resources. This assignment is free. Buying training does not affect apprenticeship consideration.

## Assignment Material

### The pretend service

BBR Academy is thinking about a learner-support service. A learner sends a question through a web page. An **API** checks the request. The service looks up approved program information. It may ask an **AI provider** to draft a reply. Staff review questions that need a person. Staff also get follow-up tasks. The service keeps a small set of **logs** to help find mistakes or misuse.

This is a design exercise. The service has not been approved for use with real learners. Use made-up information only.

Ask yourself: What data enters the service? Who can see or change it? What could reach the AI provider? Which choices need staff approval? What should go into a log? What if a document tells the AI to ignore its rules?

### Your five sections

Use the names below if you want. You can also put all five sections in one document. A clear photo of a hand-drawn diagram is fine.

#### 1. `system-context.md` — Who and what is in the system?

- My exact KC7 username:
- Date I finished How to Play KC7:
- Investigation: A Rap Beef: An Intro to Security Investigations
- Date I finished the investigation:
- My first prediction and how sure I was (0–100%):
- People who use this service:
- Data and systems we need to protect:
- Parts I included in my design:
- Parts I left out of my design:
- What this service should help people do:
- What could go wrong for learners or staff:
- Data I would keep out of AI tools and public files:

#### 2. `data-flow-diagram.md` — Draw the system

Draw and label all seven parts: **learner, web client, API, AI provider, approved knowledge source, logging service, staff console**. Use arrows to show how data moves. Mark at least three trust boundaries. For each one, write one or two sentences about why it needs a check or safeguard.

You may draw by hand or use a tool. Your labels and arrows need to be easy to read.

#### 3. `threat-register.csv` — List at least six threats

For each threat, record:

- The STRIDE type and the part of the service at risk.
- How someone could cause the problem.
- How it could affect **confidentiality, integrity, availability**, or the learner-support mission.
- What evidence you would check.
- A safeguard, a way to spot the problem, an owner, and when to escalate.
- Any risk that would remain.

**STRIDE** helps you think of different threats:

- **S — Spoofing:** Someone pretends to be another user.
- **T — Tampering:** Someone changes data or instructions.
- **R — Repudiation:** Someone denies an action, and the records cannot show what happened.
- **I — Information disclosure:** Private information reaches the wrong person.
- **D — Denial of service:** The service stops working for people who need it.
- **E — Elevation of privilege:** Someone gets access they should not have.

Try to use all six types. If one does not fit, say why. Then add another threat that does fit. For example, what if a learner could see another learner's request in the staff console? What check could stop that? What record might help you find it? Use your **own** threat ideas in your submission.

#### 4. `ai-tool-fit.md` — Decide how AI and people should work together

- One task where an AI draft may help:
- One choice AI must not make on its own:
- Data that should not go to the AI provider:
- How a person would check the draft:
- One risk I would mitigate, avoid, transfer, or accept with approval:
- Why I chose that action and who could be affected:
- Who owns the safeguard, and who can approve the decision:
- What risk remains, and when staff must escalate it:

#### 5. `reflection.md` — Show your thinking

- My question during the KC7 investigation:
- The query or filter I used:
- What I saw in the result:
- What I think it means:
- What I still do not know:
- Two possible explanations for one event:
- What I would check next:
- What changed my first idea, and why:
- A mistake or surprise that helped me learn:
- What I can explain now without notes or AI:
- Hints, guides, peers, or AI I used:
- If I used AI, what I checked or rejected:
- If I get feedback, what I will change and how I will test it:

### Check your work before you submit

- [ ] I wrote my exact KC7 username. I finished both games.
- [ ] I saved a query or filter, a result, two possible explanations, and a next check.
- [ ] My diagram has seven parts and at least three explained trust boundaries.
- [ ] I explained at least six threats, with impacts, safeguards, owners, and escalation points.
- [ ] I explained my AI decision, human checks, and remaining risk.
- [ ] My screenshots, if included, are allowed and hide private data.
- [ ] I wrote down what help I used and checked any AI suggestions.

**How your work will be reviewed:** The system map is worth 3 points. The threats are worth 3. Risk decisions are worth 2. Your evidence and reflection are worth 2.

You can use an accessible drawing or writing tool. You can also submit a clear hand drawing. If a tool or file type blocks you, ask BBR Academy for another way to submit. The same learning and safety goals apply.

## Glossary

- **AI provider:** An outside service that runs an AI model. Data sent to it crosses a trust boundary.
- **API (application programming interface):** A way for one piece of software to ask another piece to do something.
- **Approved knowledge source:** Information that staff have checked and allowed the service to use.
- **Asset:** Something worth protecting, such as an account, a document, or the service itself.
- **Availability:** The service works when people need it.
- **Confidentiality:** Private information stays with people who are allowed to see it.
- **Data flow diagram:** A picture that shows where information goes.
- **Escalate:** Bring a concern to a person with the right skills or authority.
- **Evidence:** A result, record, or test you can point to. A guess is not evidence.
- **Filter:** A way to narrow the data you see.
- **GRC:** Governance, risk, and compliance. This work helps a team set rules, make risk choices, and check whether it follows its duties.
- **Integrity:** Data and actions stay correct and are not changed without permission.
- **KC7:** A training game where you investigate fictional security events.
- **Log:** A record of an event, such as a sign-in or a system error.
- **Mitigate / avoid / transfer / accept:** Four ways to handle a risk. Reduce it; stop the risky activity; shift part of the burden by agreement; or knowingly keep the risk with approval.
- **Query:** A request you make to find specific information in data.
- **Risk:** The chance that a threat could cause harm, and how serious that harm could be.
- **Safeguard (control):** A step that helps prevent, find, or limit a problem.
- **STRIDE:** The six threat prompts listed in Section 3.
- **Threat:** Something that could harm a person, system, or goal.
- **Trust boundary:** A place where control, identity, access, or data handling changes.
- **Web client:** The part of a website or app that a learner uses to send a request.

## Optional: Learn about Markdown

A file ending in **`.md`** uses **Markdown**. Markdown is plain text with simple marks for headings, lists, links, and more. You can read this assignment as a PDF if that is easier. You do not need to learn Markdown to complete it.

If you want to try it, start with [GitHub's basic Markdown guide](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax). You can also search online or watch YouTube videos for examples. People use Markdown with other tools to make notes from YouTube playlists, write instructions for AI agents, build searchable “second brains,” make portable study flashcards, and write documents that can run code in a compatible notebook or editor. **Markdown itself does not run code.** These are examples, not the only things you can do with it.
