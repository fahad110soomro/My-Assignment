# My-Assignment
In this Repository I'm uploading my Software Engineering Assignment of making Summaries

<h1>SimplyHover
Improving Comprehension of else Statements</h1><br>

<h2>Authors:  Ahmad Jabara, Bar Ben Michael, Or Shacham, Omer Tavor
Conference Name: ICPC 2020 Tool Demonstration
Date: Wed 15 Jul 2020 00:24 - 00:36 at ICPC - Session 9: For Developers Chair(s): Anderson Oliveira</h2><br>
<h3>Introduction:</h3>
In large blocks of code, for the developer its got essential to make any maintenance in the large code. In particularly those that are governed by If-else statements, these large blocks of code increase the distance between the if and its else counterpart or the other dependent else statements . So this is very difficult to find the parts of If else statements means sometime there is the multiple page codes are coded by developer so there is a lot of difficulty facing by the developers to maintain the if else code means if the if is on the one page the else part may occurs on the different one so it became hard to find the if’s part. So this SimplyHover Tool is developed that helps to make maintenance easy specially for If-else statements. Its just easy to use tool and helped a lot developers its basically a plug-in make for the Eclipse IDE 
<br>
<h3>Important:</h3>
SimplyHover’s importance is to when developers hover over else statements. Its great feature to compare of if statements to its else part in large code. It appears in the main toolbar for preferences. 
<br>
<h3>Methodology:</h3>
We take an unsplitCurrent method of java from JEdit in which we have 3 else-statements occurred in large blocks of code for comprehending else blocks we used simply hover plug-in tool in Eclipse IDE that brings the if condition next to its else counterpart. simply hover presents to the developer to know hover over else the if conditions in their negated form and even lets him own simplification for that.
<br>
<h3>Motivation:</h3>
Best tool to get the else part of the if statement easily from the large code even it is occurred in the thousands of lines no matter which else part of which if statement. Now the developer can easily got that which else part is from which if statement by this amazing tool simply by hover feature.
<br>
<h3>Result:</h3>
This is the best tool for the developers to easily maintain the large code in which there is a lot of if else statements cause it helps to find the if statement’s else part easily simply by hover feature..


<h1>Automatically Granted Permissions 
in 
   Android Apps</h1>

<br>
<h2>Authors:  Paolo Calciati, Konstantin Kuznetsov, Alessandra Goria, Andreas Zeller.
Conference Name: MSR 2020 Technical Papers
Date: Tue 30 Jun 2020 11:12 - 11:24 at MSR:Zoom2 – Security	 Chair(s): Dimitris Mitropoulos</h2>
<br>
<h3>Introduction:</h3>
Android apps are updated continuously by developers to keep up with competitors in the market. Such constant updates do not bother end users, by default the Android platform automatically pushes the most recent compatible release on the device, unless there are major changes in the list of requested permissions that users have to explicitly grant. The lack of user’s explicitly approve of update for each application may lead to some risks for the end user, as the new behavior may be the privacy invasive and then the Permission Group’s Introduction in Android make this problem worse cause If a user gives the single permission within a group the application can silently request further permissions in this group with every and each update without asking user. The threat that permission groups may pose for the privacy of Android users.
<br>
<h3>Methodology:</h3>
The empirical study on 2,865,553 app releases and showed that the in a representative app store more than 17% of apps request new dangerous permission that the operating system grants without any user’s approval. Our analysis shows that apps actually use over 56% of such automatically granted permissions, although most of that there isn’t any description given that for what purpose it is being used.
<br>
<h3>Motivation:</h3>
The motivation in this research work is that the automatically granted permissions in the android app is very harmful for the user cause it collects the personal data of the user.
<br>
<h3>Result:</h3>
Our manual inspection reveals clear abuses of apps that leak sensitive data such as user’s accurate location, list of contacts, history of phone calls, and emails which are protected by permissions that user never explicitly acknowledges. 

	

<h1>Ownership at Large
      Open Problems and Challenges in Ownership Management
			         Facebook Inc.</h1>
<br>
<h2>
Authors:
John Ahlgren, Maria Eugenia Berezin, Kinga Bojarczuk, Elena Dulskyte, Inna Dvortsova, Johann George, Natalija Gucevska, Mark Harman, Shan He, Ralf Lämmel, Erik Meijer, Silvia Sapora, and Justin Spahr-Summers 

Conference Name: ICPC 2020 Inudstry

Date : Wed 15 Jul 2020 02:00 - 02:15 at ICPC - Session 10: Documentation Chair(s): Gias Uddin
</h2>
<br>
<h3>Introduction:</h3>   

Managing software asset ownership in any organization is important. In this paper, when we refer to 'asset' we include entities as diverse as source-code files, tables in the data warehouse, and software configurations. When we refer to the 'owner' of an asset, we mean this term in a broad sense: a set of people who take responsibility for the asset. Standard processes, e.g., based on escalation, are typically in place to rule out unowned assets, as they would clearly be a cause for concern. A more nuanced question is the one of 'ownership health', i.e., whether each asset is attributed to the 'most suitable' owner. Who is the most suitable owner of a given asset changes over time, e.g., due to reorganization and individual function changes. Attributing assets to owners and measuring ownership health encompasses a combination of static and dynamic properties of the software assets themselves, the workflows for developing and managing the assets, and the structures of the organization that possesses the assets.
<br>
<h3>
Methodology:</h3>
 
2.1 Vocabulary of Ownership Management The term resource alludes to such an element that is a piece of a framework or is controlled by an organization of intrigue. Accept an extraordinary piece of a framework: its resource for proprietor attribution planning or just attribution, which maps advantages for proprietor competitors, which are in this way alluded to as proprietors. The dark bolts on the left express that the resource for proprietor attribution planning is mostly encoded in the benefits themselves, for example, by explanation inside documents or a megastore for tables, in which case extraction can be applied to resources or conceivably to logs that record the proprietors 'in real life'. 
The quantity of on call turns is under 10k. Number of proprietor possibility for a given resource a. It is frequently conceivable, subject to heuristics dependent on key highlights, to limit to a short rundown of proprietor applicants that are at all conceivable for the benefit an and that should be positioned in this manner. 
The day by day stir for source-code documents in one of the greater mono repos of Facebook is around 100k. Every day proprietor beat for resource type t. Such stir is important as heuristics/ML should computerize these changes. 
For a significant resource type for planned pipelines in the information distribution center with about 100k resources, the totaled day by day proprietor beat in the course of the most recent 4 months is about 10k while there were a few days with a few several influenced resources - this is a result of organized endeavors on possession the executives at Facebook, in light of Ownesty or something else. 
3.1 Heterogeneity of Owned Assets Ownership suggestion - particularly when concentrating on code resources - is identified with code origin attribution , as applicable, for instance, for identifying malevolent or copied code, subject to stylometry techniques and the all-encompassing presumption of unmistakable composing style to be seen as a unique mark. Program cutting , idea task , and search-based advancement , just as numerous different examination strategies, have all been utilized to explore auxiliary parts of a product advantage for help software engineers' perception of the benefit. Existing reliance investigations should be additionally summed up to apply better to heterogeneous resources and the issue of ascribing advantages for proprietors. 
Provenance or ancestry might be focused on conditions for information resources while data stream might be focused on program resources, yet mixes or speculations of such techniques are expected to cover the advantage types that happen together by and by Workflow and Organizational Aspects Attribution of resources for proprietors likewise needs to consider communications of proprietor competitors with the benefits.
Obviously, possession proposal requires a speculation of the investigation of connections to represent the various sorts of advantages and proprietor competitors and differing types of communication. To be more concrete, hierarchical structure may bolster better comprehension of possession in that, for instance, the wellbeing of a specific attribution of a resource for a proprietor may rely upon past, later, and up and coming changes to groups or individual jobs. 
The accompanying space explicit requirements challenge the arrangement of interpretable and reasonable models for possession suggestion; devoted exploration is required in this way: The attribution connection among resources and proprietor applicants might be naturally uncertain.

<br>
<h3>Result:</h3>
This paper describes the overall idea of possession the board and the particular parts of utilizing proprietorship proposal for ascribing advantages for proprietors and estimating the wellbeing of any such attribution for huge and complex activities and frameworks. The suggestion of reasonable proprietors and the evaluation of possession wellbeing depends on information removed from resources, work processes and authoritative structures. 
They have acquainted the Facebook Ownesty framework with delineate the pragmatic modern significance of the going with proprietorship research plan. 
We additionally set out open issues and challenges and their connections to existing examination exercises and networks.
