# federal-dependencies-demo-data
A place to put Python dependency data from several federal agency public github profiles

--------------------------
## Contents

#### Data folder
Contains JSONS of Python dependency information from various repositories found within federal agencies' public github pages. The federal agencies were found via <a href="https://government.github.com/community/#us-federal">this</a> page by github.com (not all were used) 

#### The notebooks folder
Contains a jupyter notebook describing how to load the json files into Neo4J. Neo4J is a graph database tool.

#### Other
A slide presentation introducing this dataset and potential datanaut projets in data visualization and analytics that could done with it is located <a href="https://docs.google.com/presentation/d/1bNedbvWyzndNqQYfTGJS6MQid6zwOe4KTmAl7PIRhBk/edit?usp=sharing">here<a/>.

--------------------------

## Premise

Many organizations are large enough and decentralized enough that developers can write similar code but never know of each other or, more importantly, learn from & reuse each other’s work. Additionally, HR/managements understanding of an individuals skills is often limited to outdated or brief resumes and other buzz-word heavy short documents. This is both inefficient and common in many large organizations. Code dependencies implicitly tell you about code skills, so turning dependencies into data can let you answer questions about your developers even if they exist distributed across many sub-organizations and have never met face to face. 

Caution must be taken, in terms of understanding the data from dependencies, as the data will be incomplete and likely to bias certain languages or tasks.



