# HackingForJustice

R Code and Walkthough for the Hacking For Justice workshop with the Cook County State’s Attorney’s Office on September 22nd and 23rd.



## SAO Data

The State's Attoneys Office (SAO) has four datasets at the case level - which means each row of data describes one court case. You can find those datasets [under this search on the Cook County Data Catalog](https://datacatalog.cookcountyil.gov/browse?tags=state%27s%20attorney%20case-level). For your convenience, direct links to and descriptions of the datasets are provided here:

- [Sentencing](https://datacatalog.cookcountyil.gov/Courts/Sentencing/tg8v-tm6u): The sentencing data presented in this report reflects the judgment imposed by the court on people that have been found guilty. Each row represents a charge that has been sentenced.
- [Dispositions](https://datacatalog.cookcountyil.gov/Courts/Dispositions/apwk-dzx8): The disposition data presented in this data reflects the culmination of the fact-finding process that leads to the resolution of a case. Each row represents a charge that has been disposed of.
- [Initiation](https://datacatalog.cookcountyil.gov/Courts/Initiation/7mck-ehwz): The Initiation results data presented here reflects all of the arrests that came through the door of the State's Attorneys Office (SAO). An initiation is how an arrest turns into a “case” in the courts. Most cases are initiated through a process known as felony review, in which SAO attorneys make a decision whether or not to prosecute. Cases may also be indicted by a grand jury or, in narcotics cases, filed directly by law enforcement (labeled "BOND SET (Narcotics)" in this data). Included in this data set are the defendant counts by initiation and year. This data includes felony cases handled by the Criminal, Narcotics, and Special Prosecution Bureaus. It does not include information about cases processed through the Juvenile Justice and Civil Actions Bureaus.
- [Intake](https://datacatalog.cookcountyil.gov/Courts/Intake/3k7z-hchi): The intake data presented in this data reflects the cases brought in for review. Each row represents a potential defendant in a case.