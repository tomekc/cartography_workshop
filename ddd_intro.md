footer: © SmartRecruiters Inc, 2018

## CARTOGRAPHY 101

![filtered](ddd/mercator_na_world_physical_wall_mural_lg.jpg)

---

# Domain driven design

### Why should I care?

---

### Complexity of software =

### *ESSENTIAL* + ACCIDENTAL

---

### Complexity of software =

### ESSENTIAL + *ACCIDENTAL*

---

![inline](ddd/complexity_tr_1.png)

^ Initial commit. Built fast and it's working.

---

![inline](ddd/complexity_tr_2.png)

^ Without care and consideration, we build on top and software turns into BBOM.

---

![inline](ddd/complexity_tr_3.png)

^ [TC] It works, but no one knows why. Change is risky and difficult. Developers spend time on technical complexity.

---

# MODEL

---

![](ddd/mercator_na_world_physical_wall_mural_lg.jpg)

---

![](ddd/amurica.png)

---
# Maps are easy. 
# How to create domain model?

^[KS] 
- month ago we havent good tool. We had blurry idea how to start modeling domain. 
- During DDDEU Stefan Hofer and Henning Schwentner presented Storytelling technique based on example of a software which helps manuver ships over river Elbe on their way to Hamburg. 

---
# Domain Storytelling. How does this work?

![inline] (ddd/example_story_model.png)

^[KS] 
- interviews with domain experts, 
- recording stories as a diagram, drawing it using symbols
- feedback on recorded model

---
 
![inline](ddd/storytelling_symbols.png) 

^[KS] 
- technique set of simple rules and symbols
- there is no symbol for conditions and parallelism

---

* Moderators ask questions and record story as a diagram
* Participants see what gets recorded and give their feedback
* All participants agree on model created

^[KS] Deprecated.... probably to be removed

---

# "Three good examples are better than a bad abstraction."
####Peter Hruschka in Business Analysis und Requirements Engineering

^[KS]
- Focus on single scenario. 
- Avoid distractions to consider multiple scenarios

---

![inline] (ddd/whats_your_story.jpg)

^[ALL] lets draw story as a diagram without any boundaries

---

# Here lets tell why is it worth to have domains/contexts
* Single context should not belong to two teams
* If we want to apply DDD we need to identify bounded context first
* Subdomain which do not give us competetive adventage can be replaced with third party solutions

^[All] Draft! say why we should find domains/contexts

---
# How to identify bounded contexts
### Indicators of boundary:
#### one way information flow
#### difference in language
#### different triggers

^[All] Say how to do this and try to draw boundaries

---