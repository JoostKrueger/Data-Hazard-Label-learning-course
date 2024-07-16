# Data Hazard Labels
<img src="img/data-hazard-overview.png" alt="hazard-overview" width="600"/><br>
<br>
<br>
<br>
 The most basic element in conducting research is data in its many forms. The methods for collecting and presenting of this data can vary greatly depending on the source and methodology which in turn can lead to problems in evaluation and conclusions. Especially the use of increasingly complex digital technologies has muddied the question of responsibility for certain outputs or decisions made by algorithms.

 These effects and outcomes can have consequences ranging from slight deviations in results to actively harmful effects for people and the environment. Thus a reflected and responsible approach to using data science is more important than ever, but since data can be abstract and nuanced this can be difficult.<br>

 To give perspective on the difficulties and problems for specific works or sources using data science the [Data Hazard Project](https://datahazards.com/index.html#) was founded. Data Hazard Labels are similar to their real world counterparts and aim to help highlight aspects that could limit the outcome or lead to problems if they are not considered carefully.  
 
 These labels are not simple true or false problems and more than a single label can be applied to a dataset or a project. Each label comes with its own set of challenges and solutions and none of these labels are strict guidelines and rules, but are meant to facilitate communication and create understanding about the problems that can happen through improper use of data science.<br>

 <br />
 <br />
 <br />
 **What is a data hazard label?**<br>
 A data hazard label is a warnings sign used in cases where there are dangers through wrong use of data or technology.
 <br />
 <br />
 **Why do we need hazard labels?**<br>
 Data hazard labels are a tool to help prevent harmful scenarios by giving perspectives on data or technology uses.

## Reinforces Existing Biases
### Definition
<img src="img/reinforce-bias.png" alt="reinforce-bias" width="200"/><br>
 This label indicates that data, algorithms, or software could lead to unfair treatment of individuals or certain groups. There are various reasons why this hazard might arise.

 One source of bias can be the input data itself. If the data used contains biases and these are not corrected, the bias will be perpetuated. For example, if historical data reflects societal biases, algorithms trained on this data will likely replicate those biases.

 Additionally, the design of an algorithm can introduce bias. If an algorithm gives more importance to certain characteristics, it might favor some individuals or groups over others. This can happen even if the intention is not to discriminate.

 Societal biases can also infiltrate data and algorithms, reflecting and reinforcing existing stereotypes. These biases are often unintentional and unwanted, but if left unaddressed, they can have negative and unforeseen consequences. It is crucial to recognize and mitigate these biases to ensure fairness and equity in the use of data and technology.
 <br>
<img src="img/discrimination-bias.jpg" alt="discrimination-bias" width="200"/>


### Examples
 **Input data**  <br>
  An algorithm that uses historic employment data that comes to the conclusion that men are more suited to managerial position, as historically men were favoured or even the only allowed candidates for such positions.

 **Societal Bias**  <br>
 Natural Language processing data can reinforce sexist biases due to a bias in training data. This could mean that a model evaluates certain jobs such as secretary or caretaker as intrinsically linked to women.

 Such cases were [studied](https://dl.acm.org/doi/abs/10.1145/3582269.3615599) and both natural and large language models were found perpetuate stereotypes.
 Since these models are used more, great care should be taken when working with such cases and active measures taken to prevent the spread of such stereotyping.
 Such cases prove furthermore that <br>
<img src="img/stereotypical-female-jobs.png" alt="reinforce-bias" width="350"/>
<img src="img/stereotypical-male-jobs.png" alt="reinforce-bias" width="350"/>

### Prevention of Bias
 To minimize the risk of perpetuating a bias based there are multiple strategies that can be applied when using data, software or algorithms that have the Reinforces Existing Biases label.

 **Analyzing Input data:**  <br>
 By analyzing the input data carefully and checking the whether the data origin considered diverse and representative groups, the negative impacts of a bias can be mitigated.

**Testing for biases:** <br> 
 There are multiple tests that can check for biases, which can highlight problems. Testing the algorithms performance for marginalized groups can also give insight into how the software or algorithm might impact these groups.

**Avoiding harmful tools or policies:**  <br>
 There are tools and policies (e.g. predictive policing policies) that are known to reinforce systemic biases. By intentionally excluding these tools from use in algorithms a bias might be avoided.



### Videos
Documentary: Coded Bias (https://www.imdb.com/title/tt11394170/)<br>
<br>

<iframe width="560" height="315" src="https://www.youtube.com/embed/F8aegvTVy5g?si=I6xfMBv5YQV_htnz&amp;start=682" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

[Die Schwachstelle von KI – wir Menschen | ZDF Magazin Royale (10.09.2021)](https://www.youtube.com/watch?v=F8aegvTVy5g)
[11:22-12:22](https://youtu.be/F8aegvTVy5g?t=683)

### Quiz
Test your knowledge! (Multiple Choices can be true) <br>
Which of the following is a potential source of bias in algorithms?

- [[ ]] The length of the input data
- [[ ]] The speed of the algorithm
- [[ ]] The cost of the data analysis
- [[x]] The design of the algorithm

What is a key strategy to minimize the risk of having bias in data, software, or algorithms?

- [[ ]] Increasing the speed of data processing
- [[x]] Analyzing the input data carefully for societal factors
- [[x]] Using more comprehenisve data collection methods
- [[ ]] Reducing the number of variables in the data

Which is an example of societal bias in natural language processing data?

- [[x]] A model that links certain jobs to specific genders
- [[ ]] An algorithm that predicts weather patterns based on historical data
- [[ ]] A financial algorithm that predicts stock market trends
- [[ ]] An educational tool that suggests reading materials based on age groups



## Ranks or classifies people
### Definition
 <img src="img/classifies-people.png" alt="classifies-people" width="200"/><br>
 This label indicates that the data is used to rank or classify people into different categories. It is crucial to use such data considerately and carefully, as it can have far-reaching consequences.

 Issues associated with this label include inaccurate classification processes, which can misrepresent individuals. There can also be oversights in the categorization of certain groups, leading to unfair treatment or exclusion. Additionally, ranking systems can be exploited, potentially causing harm or bias against specific groups.

 Therefore, it is important to ensure the accuracy and fairness of the classification and ranking systems to avoid negative impacts on individuals and groups.

### Examples
 Using AI to evaluate the chance of reoffending. Since some communities have been overpoliced and unproportionally impacted by policies the AI might mark people from these communities as having a higher chance of reoffending. The classification of these individuals reinforces existing biases as well.

 Another example would be an automated hiring system that favours certain ethnic groups due to an unfair weighing system.

### Prevention of improper ranking and classification
 **Testing for different groups** <br>
 Testing the algorithm on different groups ensures that no side effects or disproportional impact of groups due to the classification system.


 **Verify validity of classification groups** <br>
 To ensure the validity of the classification groups, experts and subject specialists should be involved in the creation of the ranking system. This ensures that different views are represented and that the categories are needed for the end goal of the algorithm or technology.

 **Transparency** <br>
 By communicating weaknesses and shortcomings of the algorithm or technology openly trust can be built and shortcomings addressed.  Testing for weaknesses and exploitable points in the algorithm to prevent the abuse of classification that give an undue advantage or  disadvantage.

 **Alternative ranking** <br>
 Its important to consider different alternative rankings and confer with experts on the most fitting system. This allows for different viewpoints which reduces the risk of miscategorizing groups.  Self-selecting can also be a good way to grade people, as this allows them to consider their own nuances and contribute instead of being put into categories without being able to influence the process at all.


### Videos
Black Mirror: "Nosedive" (S3E1) https://www.imdb.com/title/tt5497778/?ref_=ttep_ep1

Artificial Intelligence: Last Week Tonight with John Oliver (HBO) (27.02.2023)
7:18-8:03 (Bewertung von Bewerbungen durch Algorithmen)
20:25-21:19 (Weiterführung von oben, die Algorithmen lernen durch vorherige sexistische und rassistische Entscheidungen)


### Quiz
What is a problem associated with ranking or classifying people using data?

- [[ ]] Worse processing speed
- [[x]] Inaccurate classification processes
- [[ ]] Higher data storage costs
- [[x]] Oversight in classification

How can the validity of classification groups be ensured?

- [[ ]] By using multiple different data collection methods
- [[x]] By involving experts and subject specialists for ranking
- [[ ]] By increasing number of groups
- [[ ]] By using less areas for data collection

What are examples of an automated system that reinforces existing biases?

- [[x]] An algorithm that predicts school grades
- [[x]] An AI used for predictive policing
- [[x]] A navigation system of a self driving car
- [[ ]] An algorithm predicting music based on liked songs

## Automates decision making
### Definition
 This hazard label is applied when an algorithm or technology replaces human decision-making. The extent and scope of this automation can vary widely, as can the associated risks.

 It is important to evaluate both the potential benefits and risks of automation, and to consider who oversees the automation process. Since this label involves a broad range of possible impacts, it requires extensive risk assessment and thorough testing before implementation.

 Understanding who controls the automation, and ensuring the process is transparent and accountable, are key factors in managing this data hazard effectively.
 <img src="img/automates-decision-making.png" alt="automates-decision making" width="200"/>

### Examples
 A banking program that decides automatically whether a transaction is fraudulent or not. This example carries relatively low risk, but can also cause problems.<br>
 A different example would be the automated evaluation of cancer screenings by a healthcare service program. The results of this can have great impacts on the well being of individuals and the risk is very high.<br>
 These examples highlight the differences of automated decisionmaking in different fields and the impact of the grade of consequences.
 <br />
 <br />

### Precautions for automated decision making
 **Considering necessity**
 Consider carefully if the decision really needs to be automated or if it should stay a decision made by a human. For this an in depth look at the damage of potential consequences is needed.
 <br />
 <br />

 **Implementing review systems**
 Create systems that allow for the inclusion of incorrect cases to improve the future output. For critical systems there should be training data that covers cases as extensively as possible before it is put to real use.
 <br />
 <br />
 
 **Transparency**
 It is important that decisions can be retraced understood by a human in a timely manner. It is important that actual users also have a chance to get at least a surface level understanding of how and why their input got placed or why it failed. This creates accountability and can allow for more intricate review of a case by a human. Transparency of the output is also very important to determine if the system is working as intended and to make potential issues addressable.


### Videos
Black Mirror: "Hang the DJ" (S4E4)

Die Schwachstelle von KI – wir Menschen | ZDF Magazin Royale (10.09.2021)
16:44-17:04 (KI-Einsatz in Waffen, israelische Harop-Drohne (automatisches Erfassen und Zerstören von Zielen))
18:01-18:32 (KI-Einsatz auch bei Eurofighters, s.o.)


### Quiz


## Danger of misuse
### Definition



### Examples
Black Mirror: "The Entire History of You" (S1E3)

Die Schwachstelle von KI – wir Menschen | ZDF Magazin Royale (10.09.2021)
5:14-5:30 (Deepfakes)
18:47-19:12 (Huawei testet Gesichtserkennung in China zur Erkennung von Uiguren)


### Prevention of misuse

### Videos


### Quiz

## May cause direct harm
### Definition
Wherever the label "May cause direct harm" is applied, special care needs to be taken when creating technology or algorithms.
This usually applies in healthcare, public transportation or more recently with ai chatbots.

Mistakes or wrong applications of technologies in these fields can have dangerous consequences resulting in physical or mental harm and distress to people. Technologies implemented in these areas need to be tested rigorously and extensively to keep the chance for failure as low as possible, even more so than in other fields.

Harm can also be caused by any of the other hazard labels, when used in 

### Examples

### Prevention of harm

### Videos
Black Mirror: "The Entire History of You" (S1E3)
		"Be Right Back" (S2E1)

Artificial Intelligence: Last Week Tonight with John Oliver (HBO) (27.02.2023)
18:52-19:21 (Selbstfahrendes Auto überfährt Fußgängerin, weil es sie nicht als solche erkannt hat, da sie nicht über einen Zebrastreifen gegangen ist)
19:22-20:07 (Dunkelhäutige Fußgänger werden auch nicht erkannt)

### Quiz


## Generic Data Hazard


### How to apply data hazard labels?
The application of data hazard labels is not meant as an apply and be done with it concept. The labels are meant to open up discussion and help with reflection on responsible ethical use and potential consequences of data science.
Ethics in data science is a complex topic so there is no need for a group to come to a definitive conclusion on which labels do or do not apply.

The labels also allow external people to participate in discussions on the ethical impact a technology or algorithm might have which can be tough to get into otherwise. Researchers working in data science might not have the neccesary training or knowledge to be able to consider all these possible cases, which is why the data hazard project was started in the first place.

So if you are working on a project using data science, take a minute to think which labels could apply to your project and encourage others to do the same to get a well rounded perspective on the possible outcomes!

 <img src="img/collaboration.jpg" alt="collaboration" width="300"/>


### Sources and additional reading