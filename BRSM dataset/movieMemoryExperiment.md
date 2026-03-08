## BRSM Project 2026

### Background

**Event Segmentation Theory (EST)** proposes that people parse any continuous flow of events into smaller, discrete units of meaningful events to make sense of it. The main principle of EST is driven by **prediction errors** that arise in perceptual systems. Our working memory utilizes **event models** to guide perceptual processing; these models are stable and provide consistency across time.

Whenever activity becomes less predictable, prediction error increases, requiring an update in the event models to reach a new stable state. This segmentation depends on:

* **Bottom-up processing:** Involves sensory cues that change with the environment or movement.


* **Top-down processing:** Changes based on prior established event schemata, new goals, and plans.



Event boundaries are perceived during transient changes in the perceptual system that lead to prediction errors. Abrupt disruptions from external cues can disrupt memory encoding because the event model fails to update correctly. Research by **Boltz (1992)** showed that commercial breaks at natural event boundaries improved later recall, while those at non-boundaries impaired it.

The **Event Horizon Model** expands on EST, describing how event representations are structured and affect memory. Its fourth principle, **Boundary Advantage**, states that event boundaries serve as anchors in long-term memory (LTM). Boundaries facilitate encoding into LTM because the processing at these points is critical for updating event models. Studies have shown that participants with less agreement on event boundaries performed poorer on memory tests. Additionally, **Schwan & Garsoffky (2004)** found that deleting time segments from a boundary results in poorer recall than deleting segments between events.

---

### Experimental Manipulations

**Cutting, Brunick, & Candan (2012)** studied Hollywood films from 1940–2010 and found that event boundaries were primarily perceived based on bottom-up perceptual cues (shot dynamics, motion, luminance, etc.) rather than story goals. Film editing uses **abrupt cuts** that force the cognitive system to update the event model.

**Swallow, Zacks & Abram (2009)** identified that items present at the time of boundary perception were better encoded. This suggests that abrupt cuts trigger prediction failure and affect how memory is encoded.

---

### Experiment Brief

The experiment involved two independent groups and used 40 YouTube Shorts. An independent group of annotators first identified coarse-grained event boundaries. Based on these, two versions of each video were created:

* **Natural Cut (NB):** Videos ended at their original, uninterrupted timelines.


* **Abrupt Cut (AB):** Videos were interrupted 1–5 seconds before a consensus boundary and resumed at a new event context.



Lengths were adjusted so that the average duration matched across both conditions.

#### Phases

1. **Encoding Phase:** Participants watched the videos attentively. Five videos were repeated as a **vigilance check**; participants had to press the spacebar to skip them.


2. **Recognition Task:** Participants saw two frames (one target, one lure) and had to select the previously seen one. Similarity was manipulated across three difficulty levels (easy, moderate, difficult).


3. **Confidence Rating:** Participants rated their confidence on a 5-point scale (1 = not at all confident, 5 = very confident).



**Target Types:**

* **Before Boundary (BB):** Frames occurring just before a boundary.


* **Event Middle (EM):** Frames occurring between two boundaries.



---

### Research Questions of Interest

1. **Recognition Accuracy and Response Times:** Natural Cut participants are expected to show higher accuracy and faster response times than Abrupt Cut participants.


2. **Boundary-Related Memory Effects:** Accuracy for pre-boundary (BB) frames is predicted to be higher in the Natural Cut group.


3. **Event-Middle Frames:** Performance for EM frames is expected to be similar between groups, as they are less sensitive to boundary manipulations.



---

### Statistical Metrics

* **Vigilance:** Calculated as the time between `instruction_2.stopped` and `Videos.stopped`. Participants exceeding **27.05 minutes** are considered inattentive.


* **Recognition Memory Index (REC):** Measures the ability to discriminate Targets from Novel items (bias-corrected).


* **Formula:** $REC = P(\text{"old"} \mid \text{Target}) - P(\text{"old"} \mid \text{Foil})$ 




* **Lure Discrimination Index (LDI):** Measures mnemonic discrimination (high-fidelity memory).


* **Formula:** $LDI = P(\text{"similar"} \mid \text{Lure}) - P(\text{"similar"} \mid \text{Foil})$ 





---

### Variable Dictionary

* **Resp.corr:** Whether target identification was correct.


* **Resp.rt:** Response time for the key press.


* **_NB:** Natural movie group participant.


* **_AB:** Abrupt movie group participant.


* **Conf_radio.response:** Confidence rating.



> 
> **Note:** Data for the first 13 participants is unavailable due to a data error.

---