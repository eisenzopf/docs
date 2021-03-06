# 2020-06-12 Notes of the Technical Committee Meeting 

Attendees: D. Cundiff (Chair), J. Larson, N. Myers, M. Brinas-Dobrowski, M.Frazzini, J.Iwasz, M. Saul, P. Bentsen, S. Baul, M. Lens-Fitzgerald, J. Maas, L. Lin, K. Dank, J. Stine, A.Dalloul, J.Crabb, S.Nicholas, S.Prayaga, V.Tai, N.Latwis, A.Lee

The meeting was brought to order at 8:32 CDT (US).

### Antitrust statement – Jon Stine 

### Organizational updates and introductions/questions – Jon Stine 
* Jon shared that the OVN is now a funded, legal entity.  A directed fund of The Linux Foundation 
* The OVN Steering committee held first meeting on 6/1/20 and approved the OVN Chair, Tech Advisory Chair and the OVN initial budget  
* Microsoft has joined Ali Dalloul attending Tech Comm meeting today.   Wegman’s has signed on as a sponsor as well
* Jon shared the OVN organizational structure slide and slide covering how OVN committees and communities work together.  Discussed that , "connected government" should be the term used instead of "smart cities;"  public safety should be added to the communities slide.  
**ACTION** Jon to change "smart cities" to connected government, inclusive of public safety. 

### Website development work and volunteers – Dan Cundiff
* OVN website created about a year ago [https://openvoicenetwork.org/]
* Need volunteers to work on the OVN website and would prefer to have it done by the OVN community vs external resources 
* Need to post artifacts (charters, whitepapers, etc.)  
* Site leverages Hugo website, jamstack site, uses a template that allows for flexibility.  Hosting provider is Netlify.  For those that want to edit, use Netlify CMS
* Nicholas Myers & Mike Frazzini volunteered.  
**ACTION:**  Jon will setup some time with Nick, Mike, and Dan 
* If others want to volunteer, please post in the OVN Technical Committee slack channel 

### Forming, running, operating working groups for activities 
* Activity is defined as a body of work that we need to work on and we need to form working groups to complete
* We need to organize working groups, discuss how they will work and decide which activities we should work on first 
* The list of activities should map back to the Master Plan.  If they do not, then should be brought back to the Tech Comm meeting for discussion on priority and updates to the Master Plan accordingly 
* Some of the items in the current activity list do not tie back to the Master Plan
Discussion:  
* A.Dalloul –timelines and priorities would be helpful so supportive of the discussion 
* S. Baul  –regular review of the Master Plan document would be helpful for new joiners and to foster continued alignment.  Team agreed that this would be helpful and will ensure happens.
**ACTION:**  Setup review and on-boarding sessions as to the Master Plan, Activities List – Jon & Dan 
* Dan walked through the docs repo in Git 
  * Technical Master Plan –North star, charter doc in markdown.  Teams should do pull requests against this master plan 
  * Proposed Activities list –point in time artifact that contains the list of activities that have been brought up for us to work on.  Ideally, these activities tie to the Master Plan.   We will need to create an additional roadmap artifact that takes what is in the Master Plan and says the order and likely when the artifacts will be completed 
  * Ways of working doc explains how our working groups will do activities.  Document is in progress and not yet complete 
* Activities list formed from discussions in Tech Comm meetings and from communities
Discussion: 
* P. Bentsen –roadmap document will help to define interdependencies between working groups that would be helpful 
* A. Dalloul – Some of the areas are horizontal in nature and others are specific and some regulated.  As we think about the intersection of these, it will be important to have a level of prioritization as we cannot go after everything while the Master Plan is being further developed.  Perhaps a matrix for priorities and sequencing will be helpful
* J.Larson – at the next developer community group meeting, they will be adding additional activities and will take a run at prioritization via a voting process.   Then the priority list can be vetted against the Master Plan document.   This can be brought back to the next Technical Committee meeting (6/26/20).   
* J.Stine – also can factor in whether an activity is horizontal or vertical as input to the priority  
* D.Cundiff - We can prioritize and sequence the work an do it in that order.  Or we can allow additional, more periphery activities to be completed and submitted to the OVN  
* J.Larson - recommended that 2 classes of activities be identified –foundational and exploratory/community driven/pioneering.   Emphasis needs to be on foundational but exploratory/community/pioneering driven will help attract new members, provide new ideas and allow to address fast changing space
* General discussion was supportive of the 2 class method of foundational and exploratory with the emphasis on foundational.
**ACTION:**  Dan, Jon and Jim Larson to ID the activities as foundational or exploratory  

#### Forming & Running of the working groups: 
* Working group is a collection of people working on a activity or activities
* Working groups can come and go and some are permanent pending the activity that they are assigned (ex. VRS)
* Address things like:  Slack Channel, release process, meeting cadence and notes, artifact publication process
* The “how we work” may vary slightly from working group to working group (some things need to be consistent and others can vary) 
* Discussion:  Team is supportive of a simple process and healthy for the success of the working group.   Roles & responsibilities and general operating agreement
* Maarten Lens-FitzGerald, Samrat Baul and Jon Stine volunteered to create a proposal.  Jon will include non-regulatory requirements like anti-trust, notes and recording (for audit trail). 
**ACTION:**  Maarten, Samrat and Jon create proposal 

Discussion on the Master Plan and missing components.  Team reiterated that PRs should be done against the Master Plan for this.   Discussed that PRs are new to some.  Discussed the reasons for git: version control, change tracking, transparency and common tech use.
**ACTION:**  Jon will setup a session on git, PRs, etc.    

### Follow-up from 2020-05-29 meeting – outstanding issues – Dan Cundiff or Kristi Dank 
* Will create a backlog grooming process outside of the Tech Comm meetings so that we can focus on priority items in the Tech Comm meetings.   
**ACTION:** Dan & Kristi create process 
* Discussed why using git project board for tracking activities.  Simple views to allow quick tracking of issues and transparency (work that needs to be done).   

### Next Meeting: 
* Review activity priorities 
* Propose working groups for top priority activities 

* Meeting adjourned at 9:59 a.m. CDT (US)


# 2020-05-29 Notes of the Technical Committee Meeting 

Attendees: D. Cundiff (Chair), J. Larson, N. Myers, M. Brinas-Dobrowski, M.Frazzini, J.Iwasz, M. Buck, M. Saul, P. Bentsen, S. Baul, W. Angerer, M. Lens-Fitzgerald, J. Maas, L. Lin, K. Dank, J. Stine, B. Czechowicz, V.Tai, J. Eisenzopf, A. Weidauer

The meeting was brought to order at 8:30 CDT (US).
### Antitrust statement - Jon Stine 
### Introduction - Ways of Working document on Git - Jon Stine 
J.Stine covered the Ways of Working document content (document itself is in Git).  We can work towards building this out to include adding in our git PR processes, etc.   
ACTION:  Please review Ways of Working document in git and provide comments.  [link to document](https://github.com/open-voice-network/docs/blob/master/way_of_working.md)
OVN Docs git repo is now open so all should be able to access.  
 ### Follow-up from 2020-05-14 meeting - outstanding issues - Kristi Dank 
* Need to formalize the process for issue management, prioritization and discussion – defined process as part of 5/29 session.  Will be added to ways of working doc. 
* Before the next technical committee meeting, participants to review the Technical  Master Plan document, create PRs, add comments and be prepared to ratify.  Will be discussed in 5/29 meeting
* Meeting Feedback – participants to send comments in technical committee slack channel or send to D. Cundiff directly.     Ongoing 
Discussed that all should be opening issues and we can use the git issue list and review material items in the tech comm meetings.   We can leverage the projects feature of Git to aid with this management process.   
ACTION:  D. Cundiff will add a few instructive notes to the ways of working doc.   
ACTION:  Create this project view in git.  
### Follow-up if everyone got the chance to review the Masterplan – M. Brinas-Dobrowski 
Some changes were put into the Master Plan.   We do want to label a release of this document.   Discussion was supportive of a beta release.  D. Cundiff will post the release in slack.   We can add processes related to this to the Ways of Working document. 
DECISION:  Confirm Master Plan as 0.1 Beta release. 
### Review 1.0 proposed list of Tech Comm development projects – Jim
Following the Developer Community call, M. Lens-Fitzgerald and J. Larsen drafted a list of potential "activities" for Tech Comm consideration.    The full list is still being developed.   Suggest we use the term Activity vs Project to avoid confusion.   Discussion was supportive of using the term Activity.    
VOCABULARY DECISION: These will be termed "activities"
ACTION:  J. Stine to add this to "Ways of Working."
List of suggested activities: 
1 Destination Registry
  1.1 Name Approaches for Voice Registry - Need to determine the best approach for developing a voice registry   
Discussion: This will be similar but not identical to DNS.  D. Cundiff shared a few examples like operating aspects.  Also do not be too confined to DNS and be sure to be forward looking.  Registry aspects of VRS will need to be assessed too –may need separate firms to manage the voice registry.    Collaborate with firms like Google & Amazon (users of VRS).  Expand the scope of this item to include a baseline of first level requirements vs Analysis.   
2 Voice Commerce Core Processes 
  2.1 Pay by voice -  Accelerating people’s purchasing process through voice payment, voice print and biometrics
Discussion:  Not a standard but a reference implementation and guidelines that firms can follow to provide the user with a more common experience.   The soon to be stood-up voice designer community can help with this.    Should this type of experience work come after foundational standards – this work may provide insights into how the lower level standards need to work.   This work may also be applicable for other UI applications.     Would be good to solicit involvement from bill-pay firms (ex.  Capital-One)

3 Identification and Authentication 

Discussion:  Biometrics included here? 

4 Data Privacy 
  4.1 Name Evaluate OVAL (Open Virtual Assistant Lab, Stanford University) Approach to Privacy – Need to specify a data privacy policy and enforcement mechanism 

Discussion:  Discussion supportive and promotes reuse. Will need to be in line with GDPR and CCPA.  Perhaps combined with Identification and Authentication.   Need to assess liability and regulatory impacts.   

5 Interoperability 
Discussion:  Should we add to interoperability a set of interfaces to interop between applications. 

  5.1 Vendor Independent language for writing speech applications 

Discussion:   This isn’t necessarily a new programming language but rather a vendor independent API specification.  Like Jovo –a framework.  Could be an open source toolkit.  Voice assistant, IVRs or on-device apps.  Will need to get Amazon and Google on board here (VII).  Will need to put boundaries on the focus of this like channel, NLP, etc.  This may not be an essential building block item.    

### Meeting feedback 
*  Didn’t get through all agenda items 
*  Need someone to monitor chat and share out 
*  Good discussion today –got into some requirement and maybe use this meeting to do higher level inputs 
* Perhaps a stacked or forced ranked process may be helpful to prioritize efforts 
* organic nature feels ok now 
* Helpful to have a location for sharing existing knowledge/articles/links.  Action:  Dan will create an approach 

# 2020-05-15 Notes of the Technical Committee Meeting
Attendees: D. Cundiff (Chair);  J. Larson, N. Myers, M. Brinas-Dobrowski, J. Crabb, J-C. Junker, M. Frazzini, J. Iwasz, M. Buck, M. Saul, N. Latwis, M. Lewis, P. Bentsen, S. Baul, W. Angerer, M. Lens-Fitzgerald, J. Maas, A. Lee, N. Sharif, L. Lin, S. Nicholas (Linux Foundation), K. Dank, J. Stine. 

The meeting was brought to order at 08:31 CDT (US).  

J. Stine announced that the meeting would be managed in accord with the antitrust guidelines of The Linux Foundation, (https://www.linuxfoundation.org/antitrust-policy/), and that the meeting would be recorded (mp3 file found here:  https://drive.google.com/drive/folders/1J_XGKcVnHqyVdWiV9wYjwh8rO8HMCJ3t). 

1 Linux Foundation Definition of “Project”

S. Nicholas of The Linux Foundation reviewed the LF concept of Technical Charter, and the specific “Vocabulary and Definitions” charter now before the OVN Technical Committee.   He noted that the OVN has the ability to define and launch additional projects as needs arise.  There are three (3) primary reasons why a new project may be needed:
Different mission/scope 
IP framework needs to be different 
Overall constituency of developers needs to be different.

The OVN may need an additional project when the OVN identifies a standard that needs to be developed; at that point, discussion as to the need or a separate project is appropriate.

LF process for project definition/determination described by S. Nicholas as “light;” OVN urged not to let concerns about LF processes be a burden or slow things down.

Additional questions should be addressed to S. Nicholas or J. Stine. 

2 Update on OVN Communities and their Role

J. Stine described the creation, growth of OVN Communities – comprised of the voice developer-designer-strategist ecosystem, and now in overlapping Slack Channels:  Developers, Designer-Strategists, Europe, Health & Life Sciences, and Ethical Use. 

Each community headed by volunteer moderators; Developer Community moderated by Tech Comm participants J. Larson, J. Herndon, M. Lens-Fitzgerald. 

Those wishing to participate in the Communities should forward a request to J. Stine.

3 OVN Technical Committee Ways of Working

D. Cundiff led a discussion of the tools and processes to be used by the OVN Technical Committee.  There are 3 primary tools:  Gsuite: the current repository for meeting minutes and participant roster.  Let J. Stine know your Gmail email address to get added.  Slack: the current real-time messaging and document sharing tool.  With the exception of calendar/meeting notices, we will seek to migrate away from the use of e-mail. Let J. Stine know your email address to get added to Slack.  Github: the working document repository – where we do our work.
 
Let J. Stine know your github.com user name or share it in the Technical Committee slack channel 
OVN has a variety of repos. A few are currently marked as private but want to convert to open and goal to do this after we ratify the Master Plan document 
D. Cundiff demonstrated the use, processes within GitHub. ’d the process in Git
S. Baul noted he has Git access but hasn’t tried any of the PRs.  He is assuming this is OK and confirmed ok

A discussion of Tech Comm process, ways of working:
J. Larson spoke to the process for “opened up”  issues within GitHub related to the Master Plan.  These are tracked outside of the document itself and not a PR for the doc.  Per D. Cundiff: Participants can use the PR process to start a discussion about potential changes to a document vs opening an issue.  Participants can use an issue for dialog on something that is not quite firm or you have questions   Action:   need to formalize the process for issue management/discussion.   Likely part of the Tech Comm meetings going forward.  Will also need a process re: prioritization of issues.J. Stine to add this to the “How we work” document now in development. Action:  should GitHub training be desired, please let J. Stine know, he will setup a session. 

4 Review of the Technical Masterplan

D. Cundiff discussed the need, timing of another round of reviews to the Technical Masterplan, as found in GitHub.
Per D. Cundiff:  We want to get the Masterplan to a good, complete V1 –a released state.  Action: before the next Tech Comm meeting in 2 weeks, participants are to review the document, create PRs, add comments, and be prepared to ratify. 

Question from J. Larson:  should the Developer community review the vocabulary together to land on PRs/recommendations.    Yes, confirmed; this was agreed to as a good approach. 
Question raised by D. Cundiff, M. Brinas-Dobrowski regarding Master Plan visibility: private v public – aligned to keeping private for 2 months.   Comments:  M. Frazzini – 2 months; J. Iwasz  – 2 months of time to get this more complete would be good before repo goes public; M. Buck – supports 2 month timeframe; M. Lens-Fitzgerald – there is an opportunity for marketing OVN in general with this document.  Would be good if we announced that with an artifact that is public; S. Baul - reserve opinion at this point; J, Maas –agree with timeline and transparency with going public will help with momentum; J. Crabb – 2 months to allow for 1st Steering committee meeting.  

Initial Discussion: Top Three Projects / Working Groups

D. Cundiff, J. Stine introduced topic of top three projects.   D. Cundiff reminded participants that the Technical Master Plan is the highest level of what we’ll need to work on.  Action:  Please put ideas in Technical Committee slack channel before next meeting on 5/29.  Ideas, Comments:  

J. Larson: Specify a voice application in a vendor-independent manner that can be transformed to both a working Alexa or Google voice application. Recommend if we should develop a vendor-independent language for writing speech applications that can be translated to be executed on both Alexa and Google platforms. 

Evaluate Almond as a possible voice-assistant platform. Identify structures and processes useful in our work. Reference: ALMOND, THE OPEN, PRIVACY-PRESERVING VIRTUAL ASSISTANT https://oval.cs.stanford.edu/
 Dan responds: This is viable. I really like the interoperability theme. I think that’s future looking.  Is Stanford asking you to do this as part of prod management planning? 
Specify the vocabulary for a frequently-used business activity by constructing and deploying a skill (printing a portion of a conversation) An example approach is outlined in Telephone Commands in five languages, Final draft ETSI ES 202 076 V2.1.1 (2009-06) ETSI Standard Human Factors (HF); User Interfaces; Generic spoken command vocabulary for ICT devices and services https://www.etsi.org/deliver/etsi_es/202000_202099/202076/02.01.01_50/es_202076v020101m.pdf
 
P. Bentsen: [Enhanced/Augmented Audio (Audio Input/Voice Analysis): Specify audio solution requirements (HW, DSP, ASR/STT, AI, VRS, Wake Word, DB, etc.) to a level allowing for remote sensing, voice analysis and user/patient diagnostics, as well as interoperability and interfacing with relevant entities via VRS. This would obviously require CLEAR privacy controls/deterministic privacy and a heavy focus on privacy and data protection, cybersecurity and information security (Amongst use cases, are for H&LS Digital Health, Telemedicine/Remote Patient Monitoring and Public Safety support, potentially other verticals).[Privacy & Data Protection]

Privacy & Data Protection (+Deterministic Privacy): Specify Privacy & Data Protection requirements/baselines. Privacy and Data Protection should be foundational and pervasive in all parallel OVN efforts towards standardization and will likely become a regulatory requirement and enforced in the intermediate term for this space as well (GDPR, HIPAA/HITECH/HITRUST, etc).
Cybersecurity: Specify Cybersecurity and information security requirements/baselines. Cybersecurity and information security should be foundational and pervasive in the OVN efforts towards standardization (Security Architecture & Engineering, Communication & Network Security, Identity & Access Management, Asset/SW Security). 

M. Saul:  Focus on Voice Registry System ; +1 Nicholas Myers

M. Lens-FitzGerald: Not sure that VNS is the biggest priority –wants to know why we think this needs to happen; Holistic view on voice (what is lacking in the technical plan); - Alexa VS talking lights switches (command and control VS conversational services); - Trans modal; - International views and applications, ie China, India, Europe
- Other stakeholder ie governments, defense, enterprise; Local language/nlu/data sets; Synthetic voice ; Data /profile manipulation; Inclusion are just preferences; Suggested that Maarten open up issues for some of these.

M. Frazzini:  Privacy & Security, Interoperability, Voice Registry System 

J. Iwasz: Working committees should be defined as horizontal or vertical; Will be helpful to create working groups by industry; IVR systems.

M. Buck:  Wake words standards.

N. Myers:  Voice Registry System; Data privacy and Security; Voice “handbook” for the industry; Research on desired use of voice technology versus how it is being used today.

S. Baul: Voice Registry Service –wants to be sure that the “why” we are going this is strong as will be a lot of work and want to be sure that it will be used; Truth in what we are doing – how do we ensure that there is truth in adopting the standards.  What is the case for standards compliance?  Firms need to be motivated to adopt.  Standard in measurement of voice quality.

J. Maas: Will contribute via Slack. 

Process question- should we move these working group ideas from Slack to the MasterPlan?   Action:  if you find items missing from the Masterplan, then do a PR.  Please continue to post these in Slack 

Question:  A. Lee–is the OVN focused on a voice assistant, or does the scope extend to IVR’s, more operational use cases?   

6 Meeting Feedback:  Regarding applause, criticism, and recommendations going forward:  please place comments in Technical committee slack channel or relay directly to Dan via Slack if preferred.

Meeting adjourned at 10:01 a.m. Central Daylight Time. 

notes by Dank/Stine



# 2020-04-17 Notes of the Technical Committee Meeting:

- In attendance:  D. Cundiff, Chair; C. Wuttke; M. Brinas-Dobrowski.  B. Czechowicz; J. Larson; J. Herndon; J. Iwasz; L. Lin; M. Lens-FitzGerald; M. Buck; M. Frazzini; M. Saul; N. Myers; N. Sharif; P. Bentsen; S. Baul; S. Root; S. Prayaga; T. McElreath; V. Tai; K. Dank; J. Stine. 

Meeting commenced at 15:30 CET, 08:30 Central Daylight (US). 

WELCOME.  J. Stine opened the meeting, welcomed Tech Com newcomers.

ANTITRUST POLICY.   J. Stine announced that the meeting of the Tech Comm would be conducted according to the Antitrust Policy of The Linux Foundation, found here:  https://www.linuxfoundation.org/antitrust-policy/

REVIEW OF LOGISTICS / ACTIONS FROM PRIOR MEETING.  D. Cundiff reviewed the following:  Technical Committee setup in Slack.  Reach out if questions with getting access. Ensure you have access to OVN Github organization as most of our technical committee artifacts will be housed there.  If new to Git, go to github.com to sign up for a user name and relay that information to Dan/Jon.  Pull Request (PR) – if you want to make a change, have it reviewed and merged in.

REVIEW OF LINUX FOUNDATION PROJECT CHARTER.   On behalf of the LF’s Scott Nicholas, J. Stine reported; This is the official statement of what an official TLF project is. Scott has authored this –will review in following meeting as Scott unable to attend today.

MASTER PLAN – VOCABULARY REVIEW.   M. Brinas-Dobrowski led a continued v1 review of vocabulary as generated from prior conversations, and as captured in the Master Plan 1.0.  Reviewed list of vocabulary compiled to date. Action:  All - Please review and share any comments /edits or do a PR against the vocab doc.  

General Vocab – key updates since last meeting:  Conversational AI –Let’s align on this definition; Query; Automatic Speech Recognition; Component Vocab – key updates since last meeting; Natural Language Processing; Intent; Entity; Voice Registry System; Dialog Broker; Dialog Manager; 

Discussion: Interaction Model Concept – part of NLP but need to validate; Dialog Element –need to validate if needs to be added; 3 forms of interoperability – need further discussion before adding  (J. Larson); Domain skills – need to define and add.  Landed on Voice Application  (S. Prayaga); Dialog Broker – clarification on definition (N. Myers); Dialog Manager – clarification on definition  (N. Myers).  Media Player – specific functions on a platform level that cannot be done on a local level (voice application).   Aligned that this is part of dialog broker  (M. Lens-FitzGerald).  

MASTER PLAN 1.0.  D. Cundiff, M. Brinas-Dobrowski led an introduction, initial review of the Tech Comm Master Plan.  Shared document is a starting point for continued development, evolution. Will follow Symantec versioning scheme.  Goal is to break down the components in the doc to kick off work streams to accomplish.

Doc Overview: 

Solution/Principles: We will need to validate our standards by creating reference implementations; Can be implemented as open source or closed source products; Abstracted to the right level as to not too deeply specify particular technologies used to implement them; Has the ability to protect the privacy of the user AND the user can know where their privacy is protected or not – is discoverable; Standards can be implemented down to the individual –as low as localhost, a private network or as big as globally provided.

Discussion: M. Lens-Fitzgerald: appreciates the reference to the web and basing the work that we do on that; A lot has changed since the web beginning like privacy or inclusion.   If we look at the past, what can we learn from and add to our solution.  Center for Humane Technology.
 
John Iwasz - Heidi Culbertson is an excellent resource for input for voice application design for accessibility.  Many comments in chat in support of accessibility focus. Conclusiveness & abuse should be factored in.

 S. Prayaga: Interoperability /multiple assistants –how are we dealing with privacy and data management? 

M. Frazzini:  Great first draft.  As we discuss the important topic of privacy, we also need to talk about security.  Aligned that we need to add security as a principle. 
  
J. Iwasz: We should leverage existing /review existing standards such as NIST and determine what could apply to voice.

P. Bentsen:  Propose adding voice quality – may be necessary to review what quality measures or what quality of service needs to be in place in order for standards to be utilized (related to diagnostics on voice input).

Design:  Component architecture overview; Component Flow ; Channel TTS/STT; NLP.  NLP will determine your location and your who is being referred to.  

Voice Registry Service: Making list of invocation names public; Location sensitive; Is a global service 

J. Larson:  we should capture the requirements for the VRS.  Included in the master doc?  No, this will be done via technical  sub-committees as we break out the work and the VRS sub-committee will tackle.  Suggest adding to the master plan document how we will do the work –sub committees –in Abstract and we can build out further .


J. Herndon: As we break out the sub-committees-there will need to be interaction between /across sub-committees.  

NEXT STEPS AND ACTIONS.  Prior to next meeting – Committee members:  Please review the vocabulary list and share any comments /edits or do a PR against the vocab doc.  Please read Master Plan document  - and open  issues or do pull requests in Github.   Comment in slack if unable to use Github.  Come to the next meeting with an idea of which projects that should be priority projects for OVN to focus upon.  Think about what role you would like to perform within the Technical Committee as there are many opportunities.  Prepare for roundtable discussion as to your three highest priority projects).

MEETING ADJOURNED AT 17:00 CET, 10:00 Central Daylight US.

17 April 2020


# 2020-04-03 Notes of the Technical Committee Meeting
In attendance:

Dan Cundiff, Target (Chair); Christian Wuttke, Schwarz Gruppe; Mirko Saul, Schwarz Gruppe; Scott Nicholas, Linux Foundation; Jim Larson, SpeechTEK; Nick Myers, RedFox-ai; John Iwasz, Whetstone Technologies; Richard Vanderhorst, Wegmans; Alex Weidauer, Rasa; Lawrence Lin, China Netcasting Services Association; Maria Brina-Dobrowski, Target; Joel Crabb, Target; Kristi Dank, Target; Jon Stine, Open Voice Network. 

Meeting opened at 08:32 Central US.

WELCOME.   D. Cundiff opened meeting.

 REVIEW OF THE AGENDA.

STATEMENT OF ANTITRUST COMPLIANCE.  S. Nicholas affirmed that the meeting would operate under the Antitrust Guidelines of The Linux Foundation, as found here:  https://www.linuxfoundation.org/antitrust-policy/

LAUNCHING THE TECHNICAL COMMITTEE WORK.   D. Cundiff emphasized the importance of asynchronous team productivity outside of regularly scheduled meetings.   To do so, will use three primary tools:
Slack
GSuite Share Drive – used for documents that do not require team critique, editing, version control; a Share Drive file has been set up for the OVN Tech Comm team
Github -- Technical committee will use Github to track the work that we need to do as well as artifacts that need version control and markups/comments.  Tech Comm will follow a pull request (PR) approach for this.

OVN TECH COMM MASTER PLAN 0.1.   D. Cundiff, M. Brinas-Dobrowski reviewed 0.1 draft.   Document context: leveraged the research that has been done to date and is a summary of that information; seeks to be an artifact that lays out the technical opportunities for standardization. 
Does try to define or outline the standards at a high level.   Document components include abstract, principles, design, vocabulary , component architecture proposal, component flow,  
component details. 
Process for review:  Will be converted to markdown and placed in Github.  Link sent out via Slack in ~1 week.   Reviewers execute PR to add comments.  Next discussion on 4/17, with these objectives:  * review in more detail * ratify the components * get to a baselined Masterplan v1.0.0.

 VOCABULARY DESERVING OF MECE DEFINITION.   D. Cundiff led roundtable discussion; noted that, in first meeting, the Tech Comm aligned that defining our vocabulary made good sense to do at the start.  Since, Tech Comm members contributed vocabulary content to feed this discussion.    
D. Cundiff and M. Brinas-Dobrowski reviewed the vocabulary used in the 0.1 Masterplan document.  

Included: Utterance - spoken or typed phrases; Wake Word - a specific word that will catch the attention of the channel; Query - the words that the user is requesting to happen; Text-to-Speech (TTS) - TTS is a text converting to audio. It includes customized models to overcome common speech recognition barriers, such as unique vocabularies, speaking styles, or background noise; Speech-to-Text (STT) - STT is converting the response from an audio to a text; Channels – An interface and origin of communication. It is where the utterances originate; Natural Language Processing (NLP) - A service and a branch of artificial intelligence that helps computers communicate with humans in their language and scales other language-related tasks. NLP helps to structure highly complicated, unstructured human utterance and vice-versa; Intent - is a part of the structured machine translation. It is the identified action that the machine interprets based on the user's query; Entity - is a part of the structured machine translation. It is a custom level data type and considered a concrete value to associate a word in a query; Voice Registry System (VRS) - It is a global entity type in OVN and considered one of the most important offerings. It is a hierarchical registry system built on an open system similar to the Domain Name System (DNS). VRS transforms and associates the VRS names to dialog management endpoints, NLP providers, and the functionalities you get from the dialog broker. The VRS URL serves consistently regardless of the NLP.  Dialog Broker (DB) - It is responsible for providing the fulfillable intents available for a resolved VRS record (e.g. where resolved VRS record “Target”, it’s fulfillable intents might be “order product, check order status, add to shopping list”. These fulfillable intents can execute remotely on the DM or download locally on the device.  Dialog Manager (DM) - It handles the dynamic response of the conversation. It provides a more personalized response based on the action provided by the NLP to send back to the user
Roundtable comments, contributions:

M. Saul: Voice Name Systems – maps to VRS.  Open, Interoperability, Data Privacy.  

J. Larson: Assistant (agent) – maps to channel; Intent – see above. Agent Interoperability – an agent can be replaced by another agent –rename to channel interoperability; Platform Interoperability- agent can run different platforms; Component Interoperability – component can be replaced by another component; Wake-up word – maps to wake word; Wake-up word Registry – maps to voice registry system.

J. . Iwasz: Natural Language –maps to utterance; Voice Application – maps to dialog manager; Smart Speaker – maps to channel; Localization – internationalization, changing speech understanding and response to match local user.  The Synthesized voice –the voice that is typically used on voice channels in a text-to-speech scenario; Speech-to-Text-see above; Text-to-Speech –see above.
 
N. Myers: Utterance  - see above; Interaction Model – will need to define for us leveraging what google, etc. have.  Between the user and the channel; Artificial Intelligence – will need to define; Interactive Voice Response – will need to define but lower priority; IVR may be siloed to a channel/channel specific and OVN may cross channels; Meant for definition only, not for creating standards to IVRs; Conversational AI; Natural Language Understanding vs. Natural Language Processing – see above; Voice User Interface – maps to channel.
  
A. Weidauer:  Natural Language Processing –see above; Dialog Elements – the equivalent to HTML, header or footer or form/paragraph that make up the website.   For voice, we will need to define what we mean by Dialog Elements as most discussions are not 1 question and 1 answer.   For a non-linear conversation.    Text-to-Speech – see above.  Speech-to-Text – see above.  Conversational Interface – maps to channel. 

QUESTIONS AND OPEN ISSUES.

NEXT STEPS.  Publish meeting notes and first draft of the vocabulary.  Will be posted on GitHub so we can do PRs against to contribute.  If questions on Github and PRs, reach out to Dan. Members asked to review vocabulary and contribute via comments, issues, etc. In Github. Masterplan will be published and ask members to review ahead of 4/17 meeting.

Submitted
3 April 2020 

