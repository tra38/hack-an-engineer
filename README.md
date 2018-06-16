# Hacking Engineers and Engineering Media

![Puppet cutting it's string - Male](https://www.nemil.com/musings/images/puppet-1.0.png) ![Puppet cutting it's string - Female](https://www.nemil.com/musings/images/puppet-2.png)

<small>*These images are available to use freely ([CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)). Free stickers can be requested [here](http://eepurl.com/cxs5Zr) — original SVGs are [here](https://www.nemil.com/musings/images/boy-eng-puppet.svg) and [here](https://www.nemil.com/musings/images/girl-eng-puppet.svg).*</small>

### "Background" Background (prelude note from Tariq Ali)

While I like the vanilla ["Hacking Engineers and Engineering Media"](https://github.com/nemild/hack-an-engineer) markdown file, I find that hyperlinks, examples, and quotes can accidentally "hack" an engineer. This fork is an experiment to see whether stripping out these hyperlinks, examples, and quotes lead to a different "reading experience" that can ultimately provide a "safer" document free of the very hacks we're describing here.

### Background
There are many ways to “hack” software engineers by influencing media sources and fellow community members.

This document collects examples of intentional and unintentional hacks of software engineering information sources like Hacker News, Reddit, and tech blogs. The hope is to unbias these sources and provide antibodies to engineers so that they can make better personal and team decisions.

While this is targeted at engineers, many of the examples and lessons here apply to anyone who uses media to make decisions or understand what's going on around them.

Contributions are welcome. Follow me on Twitter to see more examples of media manipulation.

### General Notes
- Key questions to ask with any media:
  - Why are they writing about this topic and how do they and/or their sources personally benefit? Always need to understand the personal motivation of writer and their sources
  - What is the technical background of the writer? A surprising number of people with little subject matter expertise have strong opinions on highly technical topics
  - Why is the media distributor (social network, news organization) putting this piece of content in front of me? How do they benefit from having me see this content?
  - Do I "need to know" this topic that this content is covering? Would investigating this topic be a productive use of my time, or could I use this time investigating other topics?
- **Reader Interest is King**: When something is heavily covered, it is often due to large reader interest — not due to the importance of the event for you
	- Editors and especially social media algorithms focus on engagement as it maximizes interest and revenue; also, a key reason for confirmation bias, filter bubbles, and technical hype
	- Journalists are under immense pressure by media owners and investors to provide content that is highly read/watched/shared and therefore most profitable
	- Journalists focus on "newsworthy" content, which many believe is the content their audience __needs__ to make good decisions. Instead, newsworthy media is what their audience __wants__ to consume (and is also most read and most profitable for their publication)
	- Rather than thinking of news as mirror of what’s going on in the world, think of it as mirror of what people want to read/hear; this "invisible hand of the reader" dictates what content is created and how well it will be distributed
	- This is a key reason for so much hype on topics like blockchains, AI, or the latest frontend framework (journalists/editors share similarities with entrepreneurs/VCs in that they're - in aggregate - providing coverage of and investing in the stories the market wants;  Scientists trying to determine what research to pursue, face the same pressure to make something journal editors and journal readers want, not necessarily what will push science forward
- **Selective facts are everywhere**: Selective facts are “true” facts that only tells us part of the story. Partisan news and social media algorithms give us the facts that confirm our beliefs and purposefully exclude important facts that give us the full picture
- **Issues with Online Democracy**: Social networks algorithms and voting mechanisms generally treat each of us equally, which diminishes how much voice is given to experts; often an issue on deeply technical topics
- **Empathy Gap**: Media and social media forums often have little empathy for the “other” side, as a given audience prefers to see themselves in the best light — and it is more engaging to see the most easily caricatured/dismissed voices on the other side (see many cryptocurrency communities). Newsfeed algorithms and friendship-based social graphs encode this bias based on the user choices they see.
  - Leads you to a deeply flawed view, which you need to consciously correct for by favoring moderate voices on the "other" side.
  - Also suggests that algorithms need to chase more than outrage and engagement (this is a key reason for filter bubbles)
- **Access and the Turning Journalism into PR**: Journalists in tech are often incentivized or subtly threatened to write positively about favored tech companies
- **The Power of Narrative**: Humans generally value stories with certain narrative notes (e.g., good vs evil, David vs Goliath, a new technology/startup will make the world a better place); Hollywood writers and journalists face similar incentives to cater to this demand
  - For deciding what war to cover in America, value to "an emotionally engaging frame of clearly identifiable good guys and bad guys" that can be pitched to an audience
  - In technology, desire of journalists to cover companies that pitch them a "make the world a better place" message
- **Attention Economy**: All media sources are in constant competition against each other for the 'attention' of their audience, in the hopes that they can later exploit that attention. Attention is a very scarce commodity (only 24 hours in a day), so the competition for your eyeballs can reach a fever pitch.
- **Building antibodies**: Scientists and engineers deeply benefit from getting things “right” in their job; to do the best job, critical for us to identify ways our data sources are influenced — and how to partially unbias them

### Content Playbook
These are common content strategies that technical organizations can use to influence engineers:

- Play into an engineer’s fear of being left behind technologically
  - Argue something is the future and what’s used now is old and anachronistic; especially powerful on junior developers
- Write derivative content on hyped topics, as you know there’s a huge market that already wants to read this
  - Hype is a function of reader interest, but often says little about engineering appropriateness
- Support others who write seemingly tangential content that supports the need for your product
- Write something controversial that you don’t fully believe
  - Controversial posts engage partisans and evoke vitriol (“engagement”) on the other side in social media, which is the fuel to get something widely discussed

### Common Players in the Engineering Ecosystem and Their Incentives

#### Venture Capitalists (VCs)

- **Key goals**: Source and win deals, market their portfolio companies
- Create content to show themselves as thought leaders and paint their portfolio companies in the best light
- Have a difficult time critiquing entrepreneurs, as they need to seem founder friendly as they compete for deals
- Function as a powerful ally for their portfolio companies, but also means you should critically weigh their messaging

#### Dev Tool Companies

- **Key goals**: Get uptake for their tools
- Sponsor content that justifies their tools; can be direct justification - or indirect (e.g., containerization companies and the push for microservices)
- May push their tools as the future, while suggesting that existing tools are anachronistic


#### Training Programs

- **Key goals**: sell classes/content
- Push new technology as new technology has less existing content - and often enables higher pricing for training programs
- Ally for motivated dev tool vendors, as both financially benefit from having engineers uptake newer dev tools


### Sources and Hacks
## Social Media


#### Common Issues Across Social Media Platforms

*Example Hacks*

- **Selective facts (intentional)**: Share partial facts with your followers (i.e., factual coverage that only shows part of the picture - and conveniently ignores facts that don't support a pre-existing view)
- **Fake News**: False content that comport to reader’s views
- **Glurge**:  False content that aims to "inspire" readers; as they don't advocate for a political position, they tend to avoid as much scrunity as "fake news"
- **Comment Filtering**: When an organization controls the Facebook page or website, comments can be filtered to highlight a favored view
- **Astroturfing**: Troll armies upvote and positively comment on their posts

*Other Issues*

- **Selective facts (unintentional)**: Algorithms favor factual coverage that only shows part of the picture, as this maximizes engagement; key issue with relying on likeminded friends and algorithms that focuses primarily on engagement to dictate content
- **Extreme “other”**: Lack of empathy for other side, as more relevant to see the most extreme actions of the other side and ignore the poor actions of the most extreme people on your side
- **Clickbait**: Decision of clickworthiness made on title alone, leading to incentives for clickworthy titles and easily explained content

#### *Reddit and Hacker News*

**How it works**

- Anyone can join and vote in community, with everyone’s vote counted equally
- For new posts, the number of upvotes soon after posting determine placement in the front page ranking
- Comments are similarly upvoted, with early comments generally advantaged over later comments
- Goal is to favor content that is likely to be heavily upvoted *for the community of upvoters*
- (Popular input source in startup communities and for junior engineers)

**Example hacks**

- **Upvoting Ring**: Asking your friends and supporters to upvote (common in dev tool companies, training programs, incubators); this can work despite social network countermeasures
- **Allied Commenters**: Get your allies to be the first commenters (which your friends will then upvote and bubble to the top), subtly shaping the views of everyone who reads the content
- **Confirmatory Content**: Creating content that justifies pre-existing views or financial incentives of subreddit holders; see what popular views are before, and ape them

**Other issues**

- **Tribalism**: Tribal behavior by key influencers can determine how certain topics are received
- **No more experts**: No distinction for experts versus others; one layman has the same voting power as the world’s most thoughtful expert; readers may also not take the time to understand background/expertise of writer
- **Militant Minority**: Upvoting and posting community is likely small compared to readers, providing lots of power to a small group of motivated users; motivated users are often people who personally benefit from post
- **Different Needs**: Ideal tools for one group/use case don’t map to another group/use case, even though both share the same social network

#### *Facebook and Twitter Feeds*

**How it works**

- Algorithms take newly posted content from often likeminded friends/followers and decide what to feature so that user engagement is maximized (click, like, share/retweet)
- Unlike Reddit model, algorithm is focused on maximizing engagement for each individual user, not for a broader, more diverse community

**Other issues**

- **Confirmation Bias**: Extreme degree of confirmation bias
	- We click on content that justifies our individual views without interacting with the full body of research on a topic; newsfeed algorithms see these choices and give us more of the same
	- Gives us an irrational confidence that we know what is “reality”, because all evidence we see justifies a certain view - and the only opposing side that breaks through is the most extreme, outrageous voices that can be easily dismissed

**Potential Antibodies**

- **Wants vs Needs**: Social feed algorithms focus on user "wants", but in engineering, huge value to determining your "needs"
- Realize huge degree of confirmation bias on Twitter/Facebook — and echo chambers in every social network. Shares a lot of similarities with publication bias in the sciences. Reader interest influences what content is produced ("the invisible hand of the reader") and distributed on social networks.
- Avoid trolls
- Realize it is newsworthy/relevant to see the excesses of the opposite side, but not very newsworthy/relevant to see excesses of your side (leads to empathy gap); applies in engineering communities, but also across religions and countries

## Conferences and Meetups
**How it works**

- Conferences make money primarily through ticket sales, sponsorships, and booths; they aim to fill the conference seats
- Companies and media organizations organize groups of speakers and market the conference
- Sponsors and corporate organizers want to show their technology in the best light
- Motivations to speak at a conference (according to MongoDB’s marketing team)
	- increasing the speaker’s network
	- raising the speaker’s profile (personal branding)
	- recruiting for the speaker’s company
	- marketing for the speaker’s company (and for conference sponsors)

**Example hacks**

- **Sponsor speaker**: For companies, support a speaker unaffiliated with your company who you think will be likely to represent your view
- **Organize your own conference**: Run your own conference to ensure your own viewpoint is widely shared — and then shared widely online afterward by participants

**Other issues**

- **Invisible hand of the sponsor/organizer**: Hard to speak badly about any sponsor/conference organizer, as it may impact if you’ll get free follow-up marketing or a future speaker invitation
- **Surfing on hype**: Conferences need to fill seats, and so often feature tested ideas that will encourage this (e.g., NoSQL)

**Potential Antibodies**

- Conferences should be just one additional data point that augment learnings from being around talented engineers — and shouldn’t be used as a primary view of what’s going on
- Weigh the background and personal motivations of every speaker
- Weigh the motivations and editorial power of who’s running the conference

## Content Marketing
**How it works**

- Create “valuable” content that doesn’t look like an ad; is apt to get engagement and influence engineer behavior
- Popular reasons for content marketing: increase domain SEO, collect sales leads, sell product/service, recruit engineers, improve brand
- Content can be created in house, or relatively small amounts of funding can encourage others to create the content needed
- Content marketing applies far beyond online posts, including categories like whitepapers to handouts in college/grad school classes

**Example Hacks**

- Create content that encourages audience to mistakenly believe that your product should be bought

**Other Issues**

- Lots of content marketing passes for journalism
- University/grad school reading can be content marketing
- Need to write content on widely read topics to maximize readership; leads to an echo chamber of hype around new technologies since these have been validated to be of interest
- Content is expensive to produce (and the costs of creating more effective content is only increasing), so only those with the resources and exposure are the ones most likely to present the content to you.)

**Potential Antibodies**

- Have to be able to identify when something is content marketing in everything from online posts to school curriculums
- Ask what is motivation of writer and how this influences their view; also need to understand their technical background
- Use content marketing to learn, but use it with proper skepticism

## Tech blogs and top media publications

**How it works**

- Trained (and untrained) journalists research various topics and work with editors to publish on blogs and print news
- Media organizations most often make money from ads; in some cases, they make money from subscription fees
- At its best, goal of journalism is to give the "facts [we] need to make good decisions"
	- Baser goal is to optimize eyeballs and number of paying subscribers by providing content that audiences want to read
	- News site can have some similarities to a convenience store that determines product placement based on maximizing sales (maximizing viewership is a key reason for the journalistic saying "If it bleeds, it leads")

**Example Hacks**

- **Rewarding Supporters/Attacking Opponents**: Media organizations/journalists can try to reward supporters such as negotiating with politicians for favorable coverage or painting their enemies in an unfavorable light; can do this to gain exclusive future access from a source or reduce competition
    - In tabloid industry, buying story to bury it is called "catch and kill; allows you to exercise leverage and/or gain a future source
- **Selective Leaking**: Leak something to a journalist that reflects unfavorably on your competitor (or a coworker), allowing it to receive more credibility than if sourced back directly
  - A flavor of this is common in business/international negotiations: leak information to journalists on actions your company/country is unlikely to do to increase your leverage in ongoing negotiations
- **Pay to place**: Pay journalist/writer directly to place a piece
- **Pay others to place**: Pay for PR firm to place
- **Pre-written Articles**: Write a press release that is easy for a journalist to publish without modification

**Other Issues**

- **Engagement is king**: Reader interest and social media algorithms prize engaging content, rather than information that leads to good engineering decisions
	- Coverage is a function of reader interest; fundamental problem with using media to make decisions
		- What’s covered is not the same as what’s important for the decisions we make each day, though the latter is a key purpose of journalism
		- Journalists will say they're covering important, "newsworthy" stories. Social media product designers will say they're surfacing "relevant" content. Both techniques surface the content readers want to read - and what is profitable for the media organization. (most journalists don't have the luxury to distinguish between "newsworthy" and the facts their readers need for good decisions)
		- Focus on newsworthiness and relevance leads to substantial “sampling bias”
	- Opportunity to create fake content that meets reader interest
- **Technical Competence**: Many journalists don’t have a technical or business background, but write on these topics authoritatively
- **Getting past PR**: PR steers journalists in favored directions and sometimes implicitly threatens things journalists value like access to a CEO
- **Talent**: Salary in journalism is a fraction of tech industry, meaning that many experienced, smart journalists increasingly leave or work in house
- **Access**: Some journalists may trade favorable coverage for access/tips; businesses/politicians favor journalists that "toe the line"
  - Companies/investors can control access to their companies, dictating the rules that journalists must follow to get exclusives and scoops; can cut off access to influence future coverage
  - Hard to get access in first place with many "A-listers", unless they have something to sell; these "A-listers" often also actively shop for journalists who will be an ally
- Journalists try to:
	- maintain good source relationships (e.g., investors) and access for future information
	- manage substantial story deadlines with limited time
	- show strong engagement metrics to ensure job security
	- can be fired or influenced to prevent unfavorable coverage even in seemingly innocuous beats like business or technical reporting
	- use “three’s a trend” as a common heuristic, despite the fact that this would be laughable to most statisticians
	- Often overweight single data points to make too broad generalizations
	- are susceptible to narrative - and confirmation bias - that then influences the follow-up coverage they do
	- have a bias to cover subjects (entrepreneurs, companies, technologies) that will “make the world a better place” — as this is an affirming message their readers value; motivates parties that want to be covered to stress these elements, no matter how unrealistic this sounds or how unclear their impact is
	- (sometimes) keep a future career path open to the technology sector
	- (though this may seem critical of journalists, it is primarily critical of the readership and financial incentives faced by many journalists; it also suggests that statistics needs to be more widely taught in journalism)
- **Media frenzy**: A singular event is reported, and a frenzy of media coverage ensues on stories that fit this narrative
  - The precipitating event:
    - validates that readers/viewers care about this issue and that for news editors there are impressions and profits to be made to see the thought process for one editor about what to cover)
    - encourages insiders/critics to leak more information — and search for receptive journalists looking for this
    - makes journalists invest more in this topic, uncovering new issues (this also has a risk of confirmation bias, where stories are reported that fit the narrative); those that don’t are poorly reported, deemed un-newsworthy, or simply ignored by the audience)
  - Targeted groups (startup founders, employees of a company, a politician) get deeply defensive, since a media frenzy is not always fair. These targeted groups fixate on the stories that are inaccurate or unfair. This then (inappropriately) leads them to dismiss most criticism, even those that a thoughtful observer would consider a fair critique.

**Potential antibodies**

- When something is heavily covered, it is substantially due to large reader interest — not due to the importance of the event for you; risk of confirmation bias and sampling bias if you don’t adjust signal
- Realize vivid stories are powerful for user engagement, while lots of drier data and stories that inform good decisions are less monetizable
- Dig into technical background of writer
- When you see something covered, ask yourself who is motivated to have it covered this way
	- Especially valuable in laudatory personal profiles
	- In leaks, who could have leaked it and what was their motive? What important information might be unleaked?
- When a PR-like piece is shared, ask what the covered party’s motivation is to get the word out now (recruiting, sales, corporate branding)
- Distinguish between guest written or sponsored pieces, and something written by the staff

## Fellow engineers

**How it works**

- Fellow engineers/scientists may be vocal in social media, conferences, and on mailing lists


**Example Hacks**

- Give them a monetizable business model, so that they’ll represent your views
- Give them equity in the success of your business — increasing the likelihood they’ll speak positively of you and, at minimum, reducing the likelihood they can publicly say negative things about you
- **Give a college talk or become an ongoing college lecturer**: For entrepreneurs this lets you scout talent, increase your company's brand on campus, and improve your own personal brand; for VCs, this lets you scout deals earlier and have greater consideration to be the chosen funder when the company raises outside funding

**Other Issues**

- Establish your expertise in one topic so that you have people's attention. Once you have their attention, express your views on another topic that you have no expertise in
- Fund researchers who pursue avenues that will be potentially accretive to your interests; not explicit bias, but means that opposite hypothesis may be weakly pursued

**Potential antibodies**

- Question funding and incentives of anyone speaking favorably about a chosen technology
- Just because someone has a well regarded reputation (e.g., through open source contributions, through previous well regarded projects) doesn’t mean they can’t be representing parochial incentives that are at odds with what is right for you
- Like with all written media, you have to question the incentives of someone speaking
