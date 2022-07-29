# Digital_Inequality_Project (Still ongoing)


1.	**Research Question:** 

*Bottom-up or media-dominated public space: what influence do traditional mass media have on French Twitter during the 2022 Presidential Election?*


2.	**Methods – Data collection and analysis**

- **How?**   -  I used Minet  to collect tweets, and a simple download for the other datasets: Factiva for the number of publications concerning French Presidential candidates, ARCOM/CSA for their time spent on TV & Radio, INA to get a list of media-related twitter accounts. 
- **Why?** – I used those datasets to compare candidates’ reaches during the 2022 election, and their temporal evolutions, both on traditional and social media and tried to find explanations of my quantitative results.
- **When?** – For the data directly concerning the candidates, the time frame is between 01-01-2022 and 03-14-2022. The INA dataset was last uploaded on 06-30-2020.  
- **How?** – I used qualitative and quantitative analysis with Python, to study correlations between temporal relative evolutions of each data type, and to try to determine causalities and/or explanations.
- **Limits:** Time ranges and details of the data sets, the fact I used tweets mentioning candidates’ tweet names and not their full usual names, possibly introducing a bias, and the number of RT to analyse Twitter reach or the fact I only retrieved tweets with more than 10 retweets are some of the limits of my study. 

3.	**Findings**

- **a.** Quantitatively speaking, I find strong temporal correlations between traditional media and Twitter, visually and through the computation of the Pearson correlation coefficients (r), not dependant of the political side.
    - i.	Some candidates’ Twitter are more correlated with TV/Radio: Jadot (r=0.99) or Zemmour (r=0.86). 
    - ii.	Some others with traditional written press: Le Pen (r=0.87) or Roussel (r=0.63)
- **b.**	Yet, it’s not only because mass media are present on twitter and print their own agenda on it.
    - i.	Yes, the share of tweets’ authors belonging to mass media is high both in number of tweets (resp. weighted by the number of RT): from 18% for Poutou to 65% for Arthaud (resp. between 16% Poutou and 87% Dupont-Aignan) but cannot explain the entire variations – only 27% (resp. 33%) for Le Pen.  
    - ii.	Also, verified accounts cannot fully explain those variations: 26% (resp. 62%) for Zemmour. 
    - iii.	Though, involved politicians or political parties often mentions each other during mass media highlights, i.e. those media are at the election’s centre and a way to exist online: 22% (resp. 48%) for Le Pen. 
- **c.**	Thus, it seems mass media influence the messages’ content rather than directly being influent on Twitter.
    - i.	When looking at the most important hashtags, one concerning a TV show but with a typo – “#OOED” – therefore surely not written directly by traditional media, is the 10th most important for Poutou. 
    - ii.	A quick look at YouTube results, for instance for Jean-Luc Mélenchon, seen as one of the best candidates on social media by the press , show mostly either TV Shows or Meetings. 
    - iii.	Over the 10 most RTed tweets for Le Pen, 3 are directly from media (LCP or Public Senat), the 7 others from political figures, but 6/10 concern traditional media interventions (e.g. through quoted videos). 


4.	**Contribution to the State of Knowledge**

- **a.**	My analysis is situated at the centre of a debate between some researchers describing Twitter and social media as a new form of public sphere independent from the “dominant” one (Clark, 2020), e.g. defining a new “networked public sphere” (Benkler, 2006), and others, more focused on elections’ processes, arguing politicians mainly use Twitter to interact with offline elites or to relay mass media contents (Deschuyteneer, 2019), with only very limited bottom-up interactions, opposed to initial internet principles (Small, 2010), and where Elites remain Elites (Dagoula, 2019), thus possibly reproducing, on a broader scope, existing offline inequalities online, especially when focused on digital participation (Shaw et al. 2018).
- **b.**	My analysis provides new insights on the ongoing French Presidential election, by nature not investigated in the literature, and contributes to the study of traditional media actual impact on social media by analysing the number of publications concerning the candidates and their time spent on TV & Radio over time, compared to Twitter data, not seen as such in the literature on that subject. 

5.	**Conclusion**

- **a.**	My study shows traditional mass media have a great influence over Twitter during the 2022 French presidential election, both on content–e.g., spread by political figures – and form – being very present on it.
- **b.**	Yet, to improve this study and for instance to better examine the influence of each election protagonists – politicians and mass media – on the others, collecting more tweets and trying to retrieve more detailed data, especially on time – days or hours instead of weeks – as well as qualitatively analysing results more in depth could be a good solution. Moreover, studying the typology of the candidates’ supporters – e.g., are they more watching TV than others – could provide some additional meaningful insights. 
- **c.**	My findings tend to show persistent offline inequalities in the digital world, and the decisive power and responsibility of traditional mass media in an election process, despite the dream of a new and more democratic public sphere enabled by digital tools.
References 

------------------------------
# References
BEN MANSOUR, B. (2017). « Le rôle des médias sociaux en politique : une revue de littérature ». Regards politiques 1(1) : 3-17.

Benkler, Y. (2006). The Wealth of Networks, Yale University Press.

Clark M. (2020). DRAG THEM- A brief etymology of so-called “cancel culture.” Communication and the Public. 2020;5(3-4)-88-92.

Dagoula, Chrysi. (2019). Mapping Political Discussions on Twitter: Where the Elites Remain Elites. Media and Communication. 7. 225. 10.17645/mac.v7i1.1764.

Deschuyteneer, Anne-Sophie. (2019). Quel impact a l'usage de Twitter par un candidat politique sur son succès électoral ? Le cas de Jean-Luc Mélenchon et François Fillon lors des élections présidentielles françaises de 2017. Faculté des sciences économiques, sociales, politiques et de communication, Université catholique de Louvain. Prom. : Moyson, Stéphane. http://hdl.handle.net/2078.1/thesis:20607

Shaw, Aaron and Eszter Hargittai. (2018). “The Pipeline of Online Participation Inequalities: The Case of Wikipedia Editing,” Journal of Communication 68, no. March: 143–68.

Small, T. A. (2010). La politique canadienne en 140 caracteres : la vie des partis dans l’univers twitter. Revue parlementaire canadienne, 33(3), 41–48.

# Other References

Institut Montaigne. (2019). Media Polarization « à la française » comparing the French and American ecosystems, May 2019 Report.  

Philipps, G. (2022). Sur Twitter, responsables et journalistes politiques déconnectés des sujets de préoccupation des Français, France Culture. 

Stricot, M. (2022). Réseaux sociaux : les rouages de la manipulation de l’opinion. CNRS Le Journal. 

---------------------


# Data Sources: 

- Tweets: 

Twitter, using the [Minet](https://github.com/medialab/minet) tool developed by the Medialab. 

- Factiva
- Arcom : [Source](https://www.csa.fr/csaelections/tempspresidentielle2022)  *"DONNÉES BRUTES DES TEMPS DE PAROLE ET D'ANTENNE"*
- Polls: [nsppolls](https://github.com/nsppolls/nsppolls) on GitHub. 
