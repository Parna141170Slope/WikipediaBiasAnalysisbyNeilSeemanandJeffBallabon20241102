1. Data Collection: Retrieved all revisions of the specified Wikipedia page ("South Africa's genocide case against Israel") using the Wikipedia API.		
2. Data Preparation: Converted the revision data into a structured DataFrame, including timestamps, usernames, comments, and content length.		
3. Bias Analysis: Applied keyword-based analysis to identify bias indicators in edit comments using categories, such as:		
   a. Strong Bias Keywords: genocide, apartheid, ethnic cleansing, war crime, massacre, occupation, colonialism, oppression, terrorist, regime, propaganda, racist, extremist, radical, militant, conspiracy		
   b. Contextual Bias Phrases: illegal, violation, rights, settler, propaganda, bias, prejudice, alleged, claimed, supposedly, purported, controversial, disputed, questionable, one-sided, biased, partisan		
   c. Neutrality Markers: npov, neutral point, objective, balanced, verification needed, citation needed, source needed, fact, reliable source, academic source		
   d. Emotional Language: brutal, horrific, devastating, tragic, outrageous, shocking, condemn, denounce, crisis, disaster, catastrophe, atrocity		
4. Edit Categorization: Classified edits into types such as content, revert, maintenance, and citation based on comment keywords.		
5. User Analysis: Aggregated data by username to calculate total edits, bias indicators, and edit types.		
6. Policy Recommendations: Developed suggestions for Wikipedia improvements based on analysis findings, focusing on edit verification, user interaction, content neutrality, and technical implementation.		
7. Summary Statistics: Compiled key metrics such as total revisions, unique contributors, and bias ratios for high-level insights.	
