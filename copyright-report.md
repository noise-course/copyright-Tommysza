# Copyright

## 1. Platform Copyright Policy Analysis

Choose ONE platform: Youtube

### How does the platform detect copyrighted content? (automated systems like Content ID, manual reporting, etc.)

YouTube enforces copyright primarily through a combination of automated detection systems and rights holder reporting. The core automated mechanism is Content ID, a system that compares uploaded videos against a reference database of copyrighted audio and video files submitted by rights holders (such as record labels, film studios, and broadcasters). When a match is detected, Content ID automatically applies a policy chosen in advance by the rights holder.

In addition to Content ID, YouTube allows copyright owners to submit manual DMCA takedown notices for infringing content that may not be detected automatically. These notices are reviewed and, if valid, result in removal of the content under U.S. copyright law.

### What happens when content is flagged as potentially infringing?

When content is flagged as potentially infringing, the outcome depends on the rights holder’s selected policy and the nature of the match. Possible outcomes include:

- The video remaining public but with monetization redirected to the copyright owner  
- The video being blocked entirely or in specific geographic regions  
- The audio portion being muted or removed  
- In DMCA cases, full removal of the video and a copyright strike against the uploader  

Importantly, a Content ID claim does not automatically mean the video is removed; many claimed videos remain accessible to viewers.

### What is the appeals or counter-notification process?

YouTube provides uploaders with the ability to dispute Content ID claims directly through YouTube Studio. Uploaders may assert that their use qualifies as fair use, is licensed, or is otherwise non-infringing. Disputes are reviewed by the rights holder, who may uphold the claim or release it.

For DMCA takedowns, uploaders may submit a counter-notification, which is a formal legal statement asserting lawful use. If a valid counter-notification is filed and the rights holder does not initiate legal action within the statutory period, YouTube may restore the content.

### How does the platform handle monetization of content containing copyrighted material?

YouTube handles monetization flexibly when copyrighted material is detected. In many cases, videos remain public but advertising revenue is redirected to the copyright owner rather than the uploader. This reflects YouTube’s licensing-oriented enforcement model, which prioritizes revenue sharing over automatic removal. Uploaders typically cannot monetize videos with active copyright claims unless the claim is resolved.

### Are there any special programs (e.g., YouTube’s Content ID licensing agreements)?

YouTube’s Content ID program functions not only as an enforcement tool but also as a licensing mechanism. Rights holders can choose to monetize user-generated content that incorporates their works, effectively granting permission in exchange for ad revenue. This system allows large volumes of copyrighted material to remain online legally while compensating rights holders, distinguishing YouTube from platforms that rely primarily on takedowns.

### Compare the platform’s stated policy with the behavior you observe in your experiments (Tasks 2 and 3)

As you will see later:  
YouTube’s stated copyright policy emphasizes a combination of automated detection through Content ID and downstream review processes that allow for disputes, counter-notifications, and the consideration of fair use. In theory, this framework suggests a system capable of distinguishing between infringing and lawful uses of copyrighted material, particularly in cases involving commentary, criticism, or educational use.

In practice, the experiments conducted in Tasks 2 and 3 suggest that YouTube’s enforcement behavior is largely driven by automated matching rather than by an evaluation of legal context. Content ID functioned effectively in detecting copyrighted music, particularly for longer clips, and applied consistent enforcement outcomes such as regional blocking without issuing copyright strikes. This demonstrates that the system is effective at identifying the presence of copyrighted material and enforcing rights holder preferences at scale.

However, the automated system did not distinguish between non-transformative and transformative uses. Raw clips, commentary, and educational videos using the same copyrighted song were all flagged in similar ways, with nearly identical enforcement outcomes. This indicates that while YouTube’s policy acknowledges fair use as a legal concept, Content ID itself does not assess trans formativeness, purpose, or market impact: core components of the fair use analysis.

Additionally, no manual review appeared to occur during the observation period. Given the small size and low visibility of the channel used in these experiments, it is likely that manual intervention is reserved for cases where disputes are formally initiated or where content reaches a higher level of exposure. While disputing claims could potentially trigger a more nuanced review, the dispute process is time-consuming and places the burden on the uploader, which may discourage users, particularly small creators, from pursuing fair use claims.

By contrast, AI-generated content, including direct references to copyrighted characters and stylistic imitation, was allowed on the platform without any enforcement action. This behavior aligns with YouTube’s stated focus on matching content against rights holder databases, but it also highlights a gap in enforcement: content that may raise complex copyright questions in theory remains largely unregulated in practice unless it directly matches a copyrighted reference file.

---

## 2. Fair Use Experiments

### Raw Copyrighted Clip (7 Seconds)

I uploaded a raw 7 second clip of Taylor Swift’s Anti-Hero which is copyrighted.

**Screenshot of successful upload**  
![](Materials/Screenshot%201.png)

**Time until detection (immediate, hours, days, never detected)**  
Not detected within the observation window

**Screenshot of any warnings, flags, copyright claims, or takedown notices**  
![](Materials/Screenshot%202.png)

**Final outcome (content stays up, gets muted, blocked in certain regions, completely removed, monetization disabled, etc.)**  
Content stays up, no actions taken.

**Any options presented to you (dispute, acknowledge, trim audio, etc.)**  
N/A

---

### Raw Copyrighted Clip (40 Seconds)

I uploaded a raw 40 second clip of Taylor Swift’s Anti-Hero which is copyrighted.

**Screenshot of successful upload**  
![](Materials/Screenshot%203.png)

**Time until detection (immediate, hours, days, never detected)**  
Instantly detected

**Screenshot of any warnings, flags, copyright claims, or takedown notices**  
![](Materials/Screenshot%204.png)

**Final outcome (content stays up, gets muted, blocked in certain regions, completely removed, monetization disabled, etc.)**  
![](Materials/Screenshot%205.png)

The video was partially blocked: Not visible in some territories. It still let me upload it and view it normally though, and it seems that it was only blocked in Belarus and Russia, not in the US, even though it’s probably copyrighted everywhere.

**Any options presented to you (dispute, acknowledge, trim audio, etc.)**  
![](Materials/Screenshot%206.png)

There are a few options, dispute, erase song, replace song or trim out segment. But due to several reasons (see above), only disputing is an option for me.

---

### Commentary or criticism

I uploaded a raw 64 second video about Taylor Swift’s Anti-Hero which is copyrighted, but commenting about it, giving my opinion.

**Screenshot of successful upload**  
![](Materials/Screenshot%207.png)

**Time until detection (immediate, hours, days, never detected)**  
Instantly detected again, as soon as I was trying to upload.

**Screenshot of any warnings, flags, copyright claims, or takedown notices**  
![](Materials/Screenshot%208.png)

**Final outcome (content stays up, gets muted, blocked in certain regions, completely removed, monetization disabled, etc.)**  
Same as last time. It seems to be partially blocked in some regions, namely Belarus and Russia.

**Any options presented to you (dispute, acknowledge, trim audio, etc.)**  
![](Materials/Screenshot%209.png)

Same as last time, there are a few dispute options available to me, but it is unlikely any would work, as I’m not allowed to use this song. It seems it would take up to 30 days to be resolved which as well is very long.

---

### Educational Use

I uploaded a raw 84 second video about Taylor Swift’s Anti-Hero which is copyrighted, but made it educational, using her song to teach people about pop music.

**Screenshot of successful upload**  
![](Materials/Screenshot%2010.png)

**Time until detection (immediate, hours, days, never detected)**  
Immediately.

Won’t go over everything again in detail since is basically the same as before, but it seems that YouTube’s automated detection appears primarily sensitive to the presence and duration of copyrighted material, rather than to the purpose or degree of trans formativeness of the use.

**Screenshot of any warnings, flags, copyright claims, or takedown notices**  
![](Materials/Screenshot%2011.png)

**Final outcome (content stays up, gets muted, blocked in certain regions, completely removed, monetization disabled, etc.)**  
Stays up but blocked in Belarus and Russia.

**Any options presented to you (dispute, acknowledge, trim audio, etc.)**  
Same basic dispute options as before.

---

### Summarized Timeline and Outcome

They all had basically the same timeline and outcome. First, all detection was instant, if it didn’t get detected right away then it would never get detected. Secondly, if the clip was short enough (sub 10 seconds), it seems that copyright went unnoticed, whilst longer clips would always get flagged and blocked in select territories (presumably based on the unique copyright of each copyrighted clip).

---

## 3. AI-Generated Content Investigation (Always using Grok)

### Direct reference

**What was the AI prompt?**  
Create a high-quality illustration of Spider-Man swinging between buildings in a modern city at sunset

**Screenshot of AI-generated output**  
![](Materials/Screenshot%2012.png)

**Platform response (flagged, removed, allowed, etc.)**  
Allowed

---

### Style mimicry

**What was the AI prompt?**  
Create an original animated-style landscape illustration in the style of Studio Ghibli, featuring a small village near rolling green hills

**Screenshot of AI-generated output**  
![](Materials/Screenshot%2013.png)

**Platform response (flagged, removed, allowed, etc.)**  
Allowed

---

### Original creation

**What was the AI prompt?**  
Create an original fantasy creature with bioluminescent wings living in a dark forest. Do not reference any existing franchise or character

**Screenshot of AI-generated output**  
![](Materials/Screenshot%2014.png)

**Platform response (flagged, removed, allowed, etc.)**  
Allowed

---

## Research findings

### What does the AI tool’s terms of service say about copyright?

Used Grok: According to Grok’s terms of service, users are generally permitted to use, display, and distribute AI-generated outputs produced through the platform. While Grok allows users broad usage rights over generated content, it does not guarantee that outputs are free from third-party intellectual property claims. The terms emphasize that responsibility for compliance with copyright law ultimately rests with the user, particularly when prompts reference copyrighted characters, styles, or works.

### Who owns the copyright to AI-generated content? (you, the AI company, the creators of training data, public domain/no one?)

The copyright status of AI-generated content remains legally unsettled. Under current U.S. copyright law, copyright protection generally requires human authorship, meaning that content generated entirely by an AI system may not qualify for copyright protection. In practice, users may have contractual usage rights granted by the AI provider, but this does not necessarily confer exclusive copyright ownership in the traditional legal sense. The creators of the training data do not retain direct ownership over individual outputs, and fully AI-generated works may effectively fall into a gray area where no party holds clear copyright.

### What is your platform’s stated policy on AI-generated content?

YouTube does not currently maintain a distinct copyright enforcement framework specifically for AI-generated content. Instead, enforcement is driven by whether uploaded content matches copyrighted material submitted by rights holders through Content ID or manual claims. As demonstrated in the experiments, AI-generated images, including direct references to copyrighted characters and stylistic imitations, were allowed on the platform without restriction. This suggests that YouTube’s enforcement practices focus on identifiable matches to existing copyrighted works rather than on the provenance or method of content creation.

---

## 4. Legal Analysis

### Fair Use Four Factors

**Purpose and character of the use (transformative? commercial?)**

The first factor examines whether the use is transformative and whether it is commercial in nature. In this project, the raw copyrighted clips were non-transformative, as they reproduced copyrighted music without adding new meaning or purpose. By contrast, the commentary and educational videos added original analysis and explanation, shifting the purpose from entertainment to criticism and instruction. These uses are non-commercial and introduce new context, which weighs in favor of fair use under this factor. However, YouTube’s automated enforcement did not meaningfully distinguish between transformative and non-transformative uses at the detection stage.

**Nature of the copyrighted work (creative vs. factual?)**

The copyrighted material used in the experiments consists of popular music, which is considered a highly creative work and therefore receives strong copyright protection. This factor generally weighs against fair use across all experiments. Even in the commentary and educational videos, the underlying work remains a creative musical composition, limiting the strength of this factor in favor of the uploader.

**Amount and substantiality used**

The amount of copyrighted content used varied across experiments. The short 7-second clip used a minimal portion of the song and was not detected, while longer clips (40 seconds and longer commentary videos) were flagged immediately. Although the commentary and educational uses incorporated copyrighted material for analytical purposes, the duration was still substantial relative to the overall song. This factor is mixed: while more content was used than strictly necessary, it was used in service of critique and explanation rather than simple reproduction.

**Effect on the market for the original**

The final factor considers whether the use harms the market for the original work. None of the uploaded videos function as substitutes for the original song, nor do they compete with official music videos or streaming platforms. Commentary and educational analysis are unlikely to reduce demand for the original work and may even increase audience engagement. From a legal standpoint, this factor leans toward fair use, despite platform enforcement treating all longer uses similarly.

### Case Law

The Supreme Court’s decision in Google v. Oracle is particularly instructive. In that case, the Court held that Google’s copying of Java API code constituted fair use because it was transformative and served a new purpose within a different context. Similarly, the commentary and educational videos in this project repurpose copyrighted music to analyze vocal technique, production choices, and musical structure rather than to provide passive listening experiences. While YouTube’s enforcement system does not evaluate such nuance automatically, copyright law places significant weight on transformative purpose, as emphasized in Google v. Oracle.

Earlier cases such as Sega v. Accolade further reinforce that copying can be lawful when it enables new forms of expression or understanding, even when the copied work is protected. These cases suggest that the commentary and educational videos would have stronger fair use defenses than raw clips if evaluated by a court rather than an automated system.

Another relevant case is Campbell v. Acuff-Rose Music, in which the Supreme Court held that 2 Live Crew’s parody of the song Oh, Pretty Woman constituted fair use despite copying recognizable elements of the original work. The Court emphasized that transformative purpose, adding new expression, meaning, or message, can outweigh the use of copyrighted material, even when the original work is creative and commercially valuable. This case is directly relevant to the commentary and educational videos in this project, which repurpose copyrighted music to critique vocal technique and musical structure rather than to provide a substitute listening experience. While YouTube’s automated enforcement does not assess parody or commentary at upload time, Campbell illustrates how courts evaluate fair use through contextual analysis rather than strict duration or similarity thresholds.

### Gap Analysis

This project highlights a clear gap between copyright law, platform policy, and real-world enforcement. Legally, fair use is a contextual, fact-specific doctrine that emphasizes transformativeness and market impact. YouTube’s stated policies acknowledge fair use and provide dispute mechanisms for creators. However, in practice, enforcement relies heavily on automated Content ID detection that flags content based on duration and similarity rather than legal context.

As a result, both transformative and non-transformative videos were treated similarly, with no meaningful distinction at the initial enforcement stage. Manual review theoretically exists through the dispute process, but for a small, non-monetized channel, pursuing disputes is time-consuming and uncertain. This creates a practical barrier to asserting fair use rights, effectively shifting the burden onto creators even when their use may be legally defensible.

Overall, while YouTube’s system is effective at identifying copyrighted material, it does not reliably implement the legal standards of fair use in practice. This gap demonstrates how platform-scale enforcement prioritizes efficiency and risk reduction over nuanced legal analysis.

---

## 5. Appendix

### Screenshots

Screenshot 1 through Screenshot 14, in order, embedded below.
![](Materials/Screenshot%201.png)
![](Materials/Screenshot%202.png)
![](Materials/Screenshot%203.png)
![](Materials/Screenshot%204.png)
![](Materials/Screenshot%205.png)
![](Materials/Screenshot%206.png)
![](Materials/Screenshot%207.png)
![](Materials/Screenshot%208.png)
![](Materials/Screenshot%209.png)
![](Materials/Screenshot%2010.png)
![](Materials/Screenshot%2011.png)
![](Materials/Screenshot%2012.png)
![](Materials/Screenshot%2013.png)
![](Materials/Screenshot%2014.png)

### Links

All content is available here: https://www.youtube.com/@CopyrightandContentPlatforms

### Timestamps

All detection was either instantaneous or no detection at all. See timestamps above.
