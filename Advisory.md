1. Sacked. Yes, 15 months ago I, along with 7 colleagues in the “Customer Success” division of Chef Software, were let go. Although surprised by this turn of events, I decide to make the layoff a learning experience.

    SLIDE: Image TBD

2. Advisory panel: I didn’t do this alone. At two other DevOpsDays I facilitated open spaces on “DR for your Career” and got some great ideas for how to map our technical best practices to the "uptime" for our own careers. Also, to ground truth, I’ve run these proposals past an advisory panel comprising an HR specialist, a Director of Engineering, and a CEO/founder of multiple start-ups.

    SLIDE: Photos, names, positions for Tony, Rick, Jill

3. Let’s apply DevOps principles of Disaster Recovery preparedness to tend to our own careers, starting with a core metric: Uptime. Traditionally, in operations and in our careers, we focussed on mean-time-between-failures (MTBF). But in a world of continuous delivery/DevOps, the better metric is mean-time-to recovery (MTTR). Do you need DR prep? Here's a simple decision tree: Do you have a job? If yes, then you're a risk for losing it.

    SLIDE: MTBF vs. MTTR

4. DR Prep: This decade we’ve seen a decline in median tenure in technical fields. Consider it inevitable that you’ll need to change jobs, either because you initiate that, or because you’re employer does. As with DR, one you don’t test your restore from backup after the site goes down, but before. So most of our DR prep happens while you’re still employed. Key points:

    SLIDE: trends in tenure from Bureau of Labor Statistics

5. Metrics/Monitoring: It's hard to know how you're doing or where you stand. Humans are bad at gathering feedback, hearing it and learning from it. My recommendation: the first few chapters of "Thanks for the Feedback" by Stone & Heen. Make sure you're getting reviews/feedback quarterly, not annually

    SLIDE: Image + "Metrics & Monitoring"

6. Logs & Offsite Backups: Get commitments in writing, or pull a Robert Mueller and write memos of key conversations. Document your contributions and their _impact_ such money saved or opportunities enabled. This is your offsite backup of your accomplishments.

    SLIDE: Image + "Logs and Offsite Backups"

7. Redundancy/Minimize Attack Surface: Write references for colleagues on LinkedIn. 1. They'll ponder your contributions, 2. It'll demonstrate to future employers you engage in production Give & Take.  Speaking of social media: Minimize your attack surface. Don't talk smack on Twitter unless you can take the consequences.

    SLIDE: Image + "Redundancy & Minimize Attack Surface"

8. Continuous Delivery & Embrace Open-source: You are own product. Improve it continually: Learn. Experiment. Make small failures and correct. Admit ignorance daily.  And participate in OpenSource: Even if you can't use GitHub at work. Comment on issues and improve documentation. It'll be noticed.

    SLIDE: Image + "Continuous Delivery & Embrace Open-Source"

9. Game Day: Any DR plan needs testing, in what are called "Game Day" events. For you, this means: Update your resume yearly.  Practice job hunting and interviewing. Don't waste anyone's time, but you can say: "I'm happy with my job, but I'm interested in your post. Can we take 20 minutes to talk about it?".  But what to do if you are sacked? As with DevOps, Practice CALMs:

    SLIDE: Image + "Game Day"

10. First: try to stay calm. An Oscar-worthy outburst may seem satisfying, but could jeopardize any further negotiaions. Ask questions, don't rush, take all morning. Legal advice is in order, and a bargain relative to mistakes you might make. Mull things over: don't sign anything. Say you feel under duress. You're legally ok. And Severance is a negotitiation, not a gift. 

    SLIDE: CALMS:
        Calm
        Ask questions
        Lawyer up
        Mull it over
        Severance

11. Since we're now in the incident response phase, again, rely on best practie. Designate an incident commander
		○ Maybe not your spouse or partner
		○ Don't make precipitous decisions
		○ And if you know someone who's been canned: Offer to help!
	- Forensics
		○ Keep all relevant documentation

    SLIDE: "Incident Response: Incident Commander and Forensics"

12. As for recovery, I'll emphasize just one point: Your job loss can be seen as a network failure. Use other networks. Last year I sent out email saying what I'd like to do, with example workplaces, including USDS & 18F, to various groups. In my community choir, it turned out, one of the Altos had a partner at 18F -- and from that connection I landed a job I'm really happy with.

    SLIDE: Image + "Route around network failure"


13. SPOF and Horizontal Scaling: Everything we discussed so far is about you, as single working unit. That makes you a single-point of failure, as it were. How do we introduce redundancy, or enabling scaling, into this system? By employee organizing -- and here we go into content _not_ endorsed by my advisory panel....


Jill, Tony, Rick:

As I mentioned, I'm giving an Ignite talk at DevOpsDays DC next week, where I thought I'd apply general DevOps principles to the idea of "Disaster Recovery for your Career."

Personally, I like to know that any advice I'm hearing has been validated by other knowledgeable folks and is not just one person's opinion. So I thought it would be useful for my audience to know to that I'm not just making shit up.

Nothing I'm saying in my first 12 slides is particularly controversial, so what I'm asking is:
a) correct me if I'm saying something particularly off-key or 
b) pipe up if I'm missing something obviously useful, especially if it maps to a technical practice.

If you can, please comment on this pull request before EOD Wednesday. Thanks! -Peter