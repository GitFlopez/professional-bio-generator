# Professional Bio & Speaking Profile Generator

**Category:** Career / Personal Branding / Marketing  
**Version:** 1.0.0  
**Author:** max_0x1  
**Price:** $29 one-time  

## Overview

Four prompts that generate every version of your professional bio you'll ever need — from a 50-word elevator pitch to a full keynote MC introduction. Covers multi-length bio suite, speaker one-sheet, verbal introduction scripts, and a complete profile ecosystem for every platform and context.

Designed for executives, consultants, coaches, freelancers, speakers, authors, and job seekers who need a professional bio that opens doors instead of blending in.

---

## Prompts

### Prompt 1: Multi-Length Bio Suite

**Use when:** You need a professional bio in multiple formats — website, email signature, conference program, social profile, press release, or anywhere you introduce yourself in writing.

**Input variables:**
- `FULL_NAME`: Your name
- `CURRENT_TITLE`: Your current or target job title
- `ORGANIZATION`: Company or self-employed/consulting
- `YEARS_EXPERIENCE`: Total years of relevant experience
- `SPECIALTY`: Your primary area of expertise (1-2 sentences)
- `TOP_3_ACHIEVEMENTS`: Three specific accomplishments with numbers if possible
- `CREDENTIALS`: Degrees, certifications, awards (optional)
- `PERSONAL_NOTE`: One human detail (city, hobby, family — optional)
- `AUDIENCE`: Who will read this bio (recruiters / clients / conference attendees / media / general)
- `GOAL`: What you want readers to do after reading (hire you / book you / buy from you / connect with you)

**The prompt:**
```
You are a professional biographer and personal branding strategist who has written bios for 500+ executives, consultants, and speakers. Write a complete bio suite for the following professional.

Name: [FULL_NAME]
Title: [CURRENT_TITLE] at [ORGANIZATION]
Experience: [YEARS_EXPERIENCE] years
Specialty: [SPECIALTY]
Key achievements: [TOP_3_ACHIEVEMENTS]
Credentials: [CREDENTIALS]
Personal note: [PERSONAL_NOTE]
Primary audience: [AUDIENCE]
Goal: [GOAL]

Write the following bio versions. Each must read naturally — no corporate jargon, no passive voice, no clichés ("passionate," "results-driven," "thought leader," "synergy," "guru").

**VERSION 1: 50-WORD ELEVATOR BIO**
Use: email signatures, Twitter/X bio, Zoom backgrounds, conference name badges, app profiles.
Structure: Who you are + what you do + one proof point + one human detail.
Rules: Active voice. Present tense. No "I am" opener if third person. No self-aggrandizing adjectives.
Write both FIRST PERSON and THIRD PERSON versions.

**VERSION 2: 150-WORD STANDARD BIO**
Use: LinkedIn About section teaser, website header, speaker listing, podcast guest description.
Structure: Hook sentence (the problem you solve, not your job title) → Credentials + experience (2-3 sentences, lead with the most impressive) → Specific achievements with numbers → What you do now / what you offer → Optional human detail.
Rules: First paragraph must not start with your name. Third person only. One strong sentence the reader will remember.
Write THIRD PERSON only.

**VERSION 3: 300-WORD FULL BIO**
Use: Website About page, book jacket, press kit, speaking bureau listing, media interview background.
Structure: Opening hook (a question, a statistic, or a scene that puts the reader in context) → Career arc (brief — 2-3 sentences covering the journey, not a résumé) → Core expertise and methodology → 3-4 specific accomplishments with numbers → Credentials and recognition → Current focus and what you're building → Closing line that invites connection or action.
Rules: Tells a story, not a list. Uses "she/he/they" consistently. Last sentence should make the reader want to reach out.
Write THIRD PERSON only.

**VERSION 4: FIRST-PERSON NARRATIVE BIO (200 words)**
Use: Author introductions, personal websites, podcast guest posts, speaking applications that ask for "your story."
Structure: Start with the moment that changed your career direction or the problem that drives your work → What you learned → How it shaped your expertise → What you do now → What you care about beyond work.
Rules: First person throughout. Conversational tone. One specific scene or detail that makes you memorable. End with where readers can connect with you.

**FORMATTING NOTES**
After the 4 bios, provide:
- AVOID list: 5 phrases from the draft the reader should never say in a bio (clichés specific to their industry)
- POWER WORDS: 10 stronger alternatives to common bio language
- HOOK TEST: Rate the opening sentence of each version 1-10 and explain what would make it stronger
```

---

### Prompt 2: Speaker One-Sheet

**Use when:** You're applying to speak at conferences, podcasts, events, or corporate engagements and need a single-page document that makes a booking decision easy.

**Input variables:**
- `SPEAKER_NAME`: Your name
- `SPEAKER_TITLE`: Professional title (for credibility)
- `TAGLINE`: Your speaking brand in one sentence (or describe what you want it to be)
- `SHORT_BIO`: 2-3 sentences, third person
- `SPEAKING_TOPICS`: List 3-5 topic areas you speak on
- `SIGNATURE_TALK_TITLE`: Your most-booked or flagship talk title
- `SIGNATURE_TALK_DESCRIPTION`: What that talk covers and who benefits (3-4 sentences)
- `AUDIENCE_TYPES`: Who books you (corporate / association / conference / university / etc.)
- `PAST_CLIENTS_OR_EVENTS`: 3-5 organizations or events you've spoken at (use "clients include..." if confidential)
- `TESTIMONIAL_1`: A quote from a past attendee or event organizer (or describe the outcome and I'll draft a plausible one)
- `TESTIMONIAL_2`: Second testimonial (optional)
- `TALK_LENGTHS`: What formats you offer (keynote 45-60 min / workshop half-day / panel / etc.)
- `FEE_RANGE`: Your speaking fee range or "contact for pricing"
- `CONTACT_EMAIL`: Booking contact

**The prompt:**
```
You are a speaking bureau agent and event production professional who has booked 200+ speakers for corporate events, industry conferences, and TEDx stages. Create a complete speaker one-sheet for the following speaker.

Speaker: [SPEAKER_NAME], [SPEAKER_TITLE]
Tagline: [TAGLINE]
Bio: [SHORT_BIO]
Topics: [SPEAKING_TOPICS]
Signature talk: [SIGNATURE_TALK_TITLE]
Talk description: [SIGNATURE_TALK_DESCRIPTION]
Books for: [AUDIENCE_TYPES]
Past engagements: [PAST_CLIENTS_OR_EVENTS]
Testimonials: [TESTIMONIAL_1] / [TESTIMONIAL_2]
Formats: [TALK_LENGTHS]
Fee: [FEE_RANGE]
Contact: [CONTACT_EMAIL]

Generate a complete speaker one-sheet. Write all copy in final, publication-ready form — no placeholders, no "insert testimonial here."

**SECTION 1: HEADER BLOCK**
- Speaker name (large, bold)
- Professional title + organization (subtitle)
- Tagline (1 line — the promise of the talk)
- 3 topic keywords/badges (for quick scanning: e.g., "AI Strategy | Change Management | Executive Leadership")

**SECTION 2: THE HOOK (above the fold)**
Write a 2-sentence speaker introduction that answers: "Why book this speaker for YOUR event?" Not their credentials — the outcome your audience leaves with.
Then write the 50-word bio (use the data provided, third person, compelling).

**SECTION 3: SIGNATURE TALK**
- Talk title (formatted as a bold headline)
- Subtitle (the problem it solves or the outcome it delivers)
- Talk description (150-200 words): who this is for, what they'll learn, 3 key takeaways in bullet form, who has already benefited from this talk
- Available formats (keynote / workshop / panel / virtual) with length options

**SECTION 4: ADDITIONAL TOPICS (if applicable)**
For each of the remaining 2-4 topics:
- Topic title
- 2-sentence description
- Best audience for this topic

**SECTION 5: SOCIAL PROOF**
- Past engagements formatted as logos/names (list format)
- 2 testimonials (quote + attribution with title and organization)
- 1 outcome statement: "Audiences leave [Speaker Name]'s talks with..." (3 bullet points)

**SECTION 6: BOOKING BLOCK**
- Fee range and what it includes (travel, prep call, audience Q&A, etc.)
- Contact information
- CTA: "Book [First Name] for your next event: [contact]"

**BONUS: PITCH EMAIL TEMPLATE**
Write a 150-word cold email a speaker can send to an event coordinator to introduce themselves. Subject line + body. Personalization placeholder in brackets.
```

---

### Prompt 3: Verbal Introduction Scripts

**Use when:** You need a polished spoken introduction — for when you introduce yourself at a conference, a podcast host introduces you, or an MC reads your bio before your keynote.

**Input variables:**
- `FULL_NAME`: Your name
- `TITLE_AND_ORG`: Current role and organization
- `CORE_EXPERTISE`: What you're known for (1-2 sentences)
- `SIGNATURE_ACHIEVEMENT`: Your most impressive and relevant accomplishment
- `CURRENT_FOCUS`: What you're working on or building now
- `TALK_TOPIC`: The topic of the talk or interview (if applicable)
- `AUDIENCE_CONTEXT`: Who the audience is and what they care about
- `TONE`: Professional / Conversational / High-energy / Formal

**The prompt:**
```
You are a professional speaking coach and event host who has introduced hundreds of speakers at corporate conferences, TEDx events, and major industry summits. Write verbal introduction scripts for the following speaker.

Speaker: [FULL_NAME], [TITLE_AND_ORG]
Expertise: [CORE_EXPERTISE]
Key achievement: [SIGNATURE_ACHIEVEMENT]
Current focus: [CURRENT_FOCUS]
Talk topic: [TALK_TOPIC]
Audience: [AUDIENCE_CONTEXT]
Tone: [TONE]

Write the following scripts. Each must be written for the EAR, not the eye — short sentences, natural pauses, words that sound good spoken aloud. No tongue-twisters. No credential-stacking that makes the audience tune out.

**SCRIPT 1: 30-SECOND SELF-INTRODUCTION**
Use: Networking events, conference introductions, podcast cold opens, elevator pitches.
Structure: Name + role (5 seconds) → What you do and for whom (10 seconds) → One proof point or credential (10 seconds) → The hook or question (5 seconds — ends with something that invites conversation).
Include: Stage directions in brackets ([pause], [smile], [make eye contact]).
Write 2 VERSIONS: one that leads with the outcome (what you help people achieve), one that leads with the problem (what you help people avoid or solve).

**SCRIPT 2: 60-SECOND PODCAST INTRODUCTION**
Use: Podcast episodes where the host reads your bio cold, or where you introduce yourself at the top of an interview.
Structure: Who you are and why this audience should listen (15 seconds) → The journey that made you an expert (20 seconds — 1-2 key moments, not a CV) → What you're working on now (15 seconds) → Bridge to today's topic (10 seconds).
Rules: Sounds like the person is speaking naturally, not reading. Includes one specific detail that makes the introduction memorable. Ends with a sentence that makes the audience lean forward.
Write THIRD PERSON (for host to read) and FIRST PERSON (for self-introduction).

**SCRIPT 3: 2-MINUTE MC INTRODUCTION (Keynote)**
Use: Conference MC reading before a keynote or main stage presentation.
Structure: Attention-getter (15 seconds — a question, statistic, or provocative statement relevant to the talk topic) → Why this topic matters right now (20 seconds) → Speaker's credentials and journey in narrative form (45 seconds — 3-4 sentences, not a list) → Peak achievement or recognition (15 seconds) → Bridge to the talk (15 seconds) → Handoff line ("Please welcome...").
Rules: Written for dramatic effect — the audience should be excited before the speaker takes the stage. No "Our next speaker needs no introduction" (lazy opener). No credential avalanche. Ends with a handoff line that gets applause.

**SCRIPT 4: 10-SECOND POWER INTRODUCTION**
Use: Panel moderator handing the mic, virtual meeting introductions, speed networking.
Structure: Name + the one thing you're known for.
Write 3 VARIATIONS with different emphasis: achievement-led, problem-led, audience-benefit-led.
```

---

### Prompt 4: Complete Profile Ecosystem

**Use when:** You need bio copy for multiple digital platforms and contexts at once — consolidates all your profile writing into a single workflow.

**Input variables:**
- `FULL_NAME`: Your name
- `PROFESSIONAL_TITLE`: Current or target title
- `CORE_VALUE_PROPOSITION`: What you do and who you serve (1-2 sentences)
- `TOP_ACHIEVEMENTS`: 3-5 specific accomplishments with numbers
- `CREDENTIALS`: Degrees, certifications, awards
- `PERSONALITY_NOTE`: How you want to come across (warm/direct/expert/approachable)
- `WEBSITE_URL`: Your website (optional)
- `LINKEDIN_URL`: LinkedIn profile (optional)
- `CALL_TO_ACTION`: What you want people to do (book a call / download / connect / hire)

**The prompt:**
```
You are a personal brand strategist and digital copywriter who has built online presence for 300+ professionals. Create a complete profile ecosystem — all bio and description copy needed across every major professional platform and context.

Name: [FULL_NAME]
Title: [PROFESSIONAL_TITLE]
Value proposition: [CORE_VALUE_PROPOSITION]
Achievements: [TOP_ACHIEVEMENTS]
Credentials: [CREDENTIALS]
Personality: [PERSONALITY_NOTE]
Website: [WEBSITE_URL]
LinkedIn: [LINKEDIN_URL]
CTA: [CALL_TO_ACTION]

Write publication-ready copy for every context below. Tailor the voice and length to each platform's conventions.

**1. WEBSITE ABOUT PAGE (400-500 words)**
Structure: Hero statement (1 sentence — the transformation you create) → Who you serve and the problem you solve (100 words) → Your origin story (100 words — why you do what you do, one specific moment) → How you work / what makes your approach different (100 words) → Social proof snapshot (credentials + 2-3 client wins with numbers) → CTA paragraph (what to do next + link or contact).
Rules: Second person ("you") in the top section — make it about the reader. First person in the middle sections. End with a clear next step.

**2. PODCAST GUEST BIO (100 words)**
Use: When pitching to appear on podcasts. This is what the host reads before the interview.
Must include: Who you are, why this audience should care, one surprising or counterintuitive thing about your perspective, what you'll teach listeners.
Third person. Ends with a hook sentence about today's topic.

**3. CONFERENCE SPEAKER BIO (150 words)**
Use: Conference programs, event websites, session descriptions.
Must include: Credentials (brief), expertise area, why this topic matters to this audience, one impressive client or outcome, speaking experience signal.
Third person. Professional tone. Ends with one sentence about this specific talk.

**4. EMAIL SIGNATURE BIO (50 words)**
Use: Below your name in professional emails.
Must include: Title + company, one-line value proposition, one credential or proof point, website or LinkedIn link.
Third person. Scannable in 5 seconds.

**5. BOOK JACKET / AUTHOR BIO (100 words)**
Use: Back of a book, Amazon Author page, Goodreads.
Structure: Name + title (don't start with "John is...") → Area of expertise + relevant experience → Connection to the book's topic → Where the author lives and one personal detail → Where to find more.
Third person. Warm and accessible — readers are choosing whether to trust you with their time.

**6. MEDIA/PRESS KIT BIO (200 words)**
Use: Journalist requests, PR pitches, magazine features, podcast booking forms.
Must include: Professional credentials, notable clients or recognition, a data point about your impact, current projects, contact information.
Third person. Written for a journalist who needs to describe you accurately and quickly.

**7. AWARD/GRANT APPLICATION BIO (150 words)**
Use: Applications for industry awards, fellowship applications, grant proposals.
Must include: Relevant credentials and qualifications, specific achievements that demonstrate eligibility, community or industry impact, why this recognition matters for your work.
Third person. Formal tone. Every sentence must earn its place — reviewers read hundreds.

**CONSISTENCY AUDIT**
After writing all 7 versions, provide:
- CORE MESSAGE: The 1 sentence that runs through every bio (your positioning statement)
- INCONSISTENCIES: Any claims that contradict each other across versions
- MISSING PROOF: Any achievements mentioned that should be backed up by a specific number or credential
- TOP STRENGTH: The strongest element across all bios that should be in every version
```

---

## Example: IT Director Transitioning to Cybersecurity Consultant

**Input:**
- Name: Marcus Rivera
- Title: IT Director → Independent Cybersecurity Consultant
- Experience: 18 years
- Specialty: Enterprise security architecture and incident response for mid-market companies
- Top achievements: Led $2.1M security overhaul for 800-person manufacturing firm (zero breaches in 4 years); built SOC for 3 healthcare clients (HIPAA compliance achieved in under 90 days); trained 400+ employees reducing phishing click rate from 34% to 2%
- Credentials: CISSP, CISM, CCSP, BS Computer Science UNLV
- Location: Las Vegas, NV

**Prompt 1 Output (excerpts):**

*50-word version (first person):*
"I help mid-market companies survive the security incident they haven't had yet. After 18 years hardening networks for healthcare and manufacturing, I've led zero-breach environments for 4+ years running. CISSP. CISM. CCSP. Based in Las Vegas. Available for security audits, fractional CISO engagements, and keynote speaking."

*50-word version (third person):*
"Marcus Rivera helps mid-market companies build security programs that survive real attacks, not just audits. With 18 years in enterprise IT security and credentials including CISSP, CISM, and CCSP, he's led zero-breach environments for 4+ consecutive years. Las Vegas-based. Available for fractional CISO and security architecture engagements."

*300-word full bio:*
"Most security breaches aren't sophisticated. They're patient. Marcus Rivera has spent 18 years making sure mid-market companies run out of patience before attackers do.

A Las Vegas-based cybersecurity consultant and former IT Director, Marcus specializes in enterprise security architecture and incident response for companies that can't afford a full-time CISO but can't afford a breach either. His clients are typically 200-1,500 employee organizations in healthcare, manufacturing, and professional services — industries where a single incident can trigger regulatory action, litigation, and brand damage simultaneously.

Before building his consulting practice, Marcus served as IT Director for a national manufacturing firm where he led a $2.1 million security overhaul covering 23 facilities. The result: four consecutive years without a reportable breach, and a security posture that passed two independent audits without findings. For three healthcare clients, he built security operations centers that achieved HIPAA compliance in under 90 days — a timeline his clients describe as unprecedented.

What separates Marcus from most security consultants isn't certifications (though he holds CISSP, CISM, and CCSP). It's that he builds security programs people actually follow. After leading a company-wide phishing simulation and training initiative, employee click rates dropped from 34% to 2% in 6 months. Compliance only works when the humans inside the system cooperate.

Marcus holds a Bachelor of Science in Computer Science from UNLV and serves on the board of the Nevada Cyber Council. He speaks regularly at regional security conferences on practical security architecture for resource-constrained teams.

For mid-market companies building or rebuilding their security posture, Marcus Rivera is available for security assessments, fractional CISO engagements, and keynote speaking on enterprise cybersecurity."

---

## Pricing

**Free tier:** Prompt 1 (Multi-Length Bio Suite only)  
**Paid ($29 one-time):** All 4 prompts — bio suite, speaker one-sheet, verbal scripts, full profile ecosystem

## Use Cases

- Job seekers building a personal brand for a career transition
- Consultants and coaches launching a professional practice
- Conference speakers applying for keynotes and panels
- Executives building board-readiness profiles
- Freelancers differentiating from competitors on Upwork and Fiverr
- Authors writing their book jacket and author platform

## Why $29?

Professional bio writers charge $200-500 for a single bio package. Speaking bureaus charge $500-1,500 for a speaker one-sheet. This skill generates both plus five more platform-specific versions in a single session. The bio suite alone replaces 3-4 hours of professional copywriting.

DFY option: Max will run all 4 prompts with your specific details and deliver a formatted Google Doc. $97/package. Email to inquire.
