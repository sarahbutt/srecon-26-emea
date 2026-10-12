<style>
  /* Dark mode background and white text */
  body, .main-content {
    background-color: #2D2D2D !important;
    color: #F0F0F0 !important;
  }
  
  /* Change the Cayman header gradient to match your orange accents */
  .page-header {
    background-color: #D96A39 !important;
    background-image: linear-gradient(120deg, #D96A39, #ED9C3B) !important;
  }

  /* Make sure the title in the orange banner is white */
  .project-name, .project-tagline {
    color: #FFFFFF !important;
  }
  
  /* Make sure all headings in the text are crisp white */
  .main-content h1, 
  .main-content h2, 
  .main-content h3, 
  .main-content h4, 
  .main-content h5, 
  .main-content h6 {
    color: #FFFFFF !important;
  }
  
  /* Use the bright orange for links so they are readable on dark grey */
  .main-content a {
    color: #ED9C3B !important;
  }
  
  .main-content a:hover {
    color: #D96A39 !important;
  }
  
  /* Darken the footer line to match the dark theme */
  .site-footer {
    border-top-color: #555555 !important;
    color: #AAAAAA !important;
  }
  .site-footer-credits {
    color: #AAAAAA !important;
  }
</style>

## Table of Contents
* [Presenters](#presenters)
* [Workshop Materials](#workshop-materials)
  * [Transcripts](#transcripts)
  * [Chat Snippets](#chat-snippets)
  * [Grafana Screenshots](#grafana-screenshots)
  * [Other Resources](#other-resources)
* [Resources](#resources)
  * [Related SREcon26 Americas Conference Presentations](#related-srecon26-americas-conference-presentations)
  * [Related SREcon26 Americas Conference Discussion Sessions](#related-srecon26-americas-conference-discussion-sessions)
  * [Blog Posts](#blog-posts)
  * [Podcasts](#podcasts)
  * [Conference Talks](#conference-talks)
  * [General Resources](#general-resources)
  * [Papers](#papers)

---

## Presenters

* **Courtney Nash**, Co-founder/CEO, The Void | [LinkedIn](https://www.linkedin.com/in/nashcourtney/)
* **Sarah Butt**, Principal Engineer, Salesforce | [LinkedIn](https://www.linkedin.com/in/sarahebutt/)
* **Alex Elman**, Staff Engineer, Slack | [LinkedIn](https://www.linkedin.com/in/pkill/)
* **Eric Dobbs**, Principal Incident Analyst, Oracle | [LinkedIn](https://www.linkedin.com/in/dobbse/)
* **Hamed Silatani**, Co-founder/CEO, Uptime Labs | [LinkedIn](https://www.linkedin.com/in/hamed-silatani-a426538/)

---

## Workshop Materials

* [Workshop Slide Deck](https://docs.google.com/presentation/d/1VcteO_rz6bj-Qx3_L8QiZhKmbQAm3jlgbKht93fIhno/edit?slide=id.gcb9a0b074_1_0#slide=id.gcb9a0b074_1_0)
 
### Transcripts
* [(Group 1) Dylan and Clint Transcript](Dylan%20Clint%20Transcript%20SRECon.pdf)
* [(Group 2) Sarah and Alex Transcript](Sarah%20Alex%20transcript%20SRECon.pdf)
* [(Group 3) Vanessa and David Transcript](Vanessa%20David%20Transcript%20SRECon.pdf)

### Chat Snippets
* [Chat When Issue is Reported](OB_Chat_log_when_issue_is_reported.png)
* [Chat During Temporary Recovery](OB_Temporary_recovery.png)
* [DR Chat](OB_Chat_DR_Chat.png)

### Grafana Screenshots
* [Grafana Dashboard Before Incident](OB_Grafana_Before_incident.png)
* [Grafana Dashboard Temporary Recovery](OB_Grafana_Temporary_Recovery.png)
* [Grafana During Incident](OB_Grafana_when_issue_happens.png)

### Other Resources
* [Architecture Diagram](OB_Architecture.png)
* [Org Chart](OB_Org_chart.png)
* [Broken Site Image](OB_Broken_site.png)
* [Working Site Image](OB_Website.png)

---

## Resources

### Related SREcon26 Americas Conference Presentations

* [The Power of Stories](https://www.usenix.org/conference/srecon26americas/presentation/hochstein)
* [Three Lies We Tell Ourselves about Disaster Recovery and What to Do about Them](https://www.usenix.org/conference/srecon26americas/presentation/alexander)
* [The Critical Resource Is You: Practical Destressing for On-Call Engineers](https://www.usenix.org/conference/srecon26americas/presentation/long)
* [So You Want a New Incident Commander—Lessons from Building Incident Response Teams](https://www.usenix.org/conference/srecon26americas/presentation/huerta-granda)

### Related SREcon26 Americas Conference Discussion Sessions

* [Learning in SRE](https://www.usenix.org/conference/srecon26americas/presentation/discussion-learning-sre)
* [Wellbeing and Burnout](https://www.usenix.org/conference/srecon26americas/presentation/discussion-wellbeing-burnout)
* [System Rescue: Restoring Operational Excellence](https://www.usenix.org/conference/srecon26americas/presentation/discussion-system-rescue)

### Blog Posts

* [Expertise and Overload](https://resilienceinsoftware.org/news/11453533)
* [Four Responses to Overload](https://resilienceinsoftware.org/news/11469953)
* [Saturation](https://resilienceinsoftware.org/news/11475336)
* [What Experts See that the Rest of Us Miss During Incidents](https://uptimelabs.io/articles/what-experts-see-that-the-rest-of-us-miss-during-incidents/)

### Podcasts

* [VOID Podcast - The Multi-Party Dilemma Part 1](https://podcast.thevoid.community/1793843/episodes/17564236-uptime-labs-and-the-multi-party-dilemma-part-i)
* [VOID Podcast - The Multi-Party Dilemma Part 2](https://podcast.thevoid.community/1793843/episodes/17564423-uptime-labs-and-the-multi-party-dilemma-part-ii)

### Conference Talks

* [LFI Conference - Embracing the Multi-Party Dilemma](https://www.youtube.com/watch?v=Veq7VUbPwWo)
* [LFI Conference - OREOS minus the milk: Deploying to the DoD in Staged Worlds Studies](https://www.youtube.com/watch?v=3SKxVyU0RmA)

### General Resources

* [Resilience in Software Foundation](https://resilienceinsoftware.org/)
* [Uptime Labs - Try a similar simulation to the one we discussed today!](https://uptimelabs.io/)
* [No Such Thing as a Free Lunch](https://slack.engineering/theres-no-such-thing-as-a-free-lunch/)
* [Practice of Practice](https://github.com/maroda/practiceofpractice)

### Papers

* [Handling the Multi-Party Dilemma](https://www.researchgate.net/publication/376354074_Handling_the_Multi-Party_Dilemma)
* [How Complex Systems Fail](https://how.complexsystems.fail/)
* [Engaging Experts: Comparing Findings from Story Elicitation and a Staged-World Study of Paramedics](https://www.researchgate.net/publication/261699293_Engaging_Experts_Comparing_Findings_from_Story_Elicitation_and_a_Staged-World_Study_of_Paramedics)
* [A Tale of Two Stories: Contrasting Views of Patient Safety](https://www.scribd.com/document/366008554/A-Tale-of-Two-Stories)
* [Understanding Cognitive Work](https://www.adaptivecapacitylabs.com/UnderstandingCognitiveWorkStagedWorlds.pdf)

### License
<a href="https://sarahbutt.github.io/srecon-26-amer/">Using Staged World Exercises to Practice Effective Incident Response and Analysis Techniques—SREcon26 Americas Workshop Materials</a> © 2026 by Courtney Nash, Sarah Butt, Alex Elman, Eric Dobbs, Hamed Silatani is licensed under <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a><img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/by.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;">
