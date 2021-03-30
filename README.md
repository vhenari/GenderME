# GenderME

The goal of this project is to examine the use of gendered language in political discourse in Germany by analysing speeches from plenary sittings of the German Bundestag. The concept of gendered language does, for the most part, not apply to English, a language that -- besides very few word pairs such as actor/actress -- uses gender-neutral terms to refer to people. In English, talking about a singer or a teacher is always an ambiguous matter unless pronouns are used to clarify the gender of that person. German, in this regard, is a much more precise language that uses specific male and female terms to refer to people. However, even though male and female versions of most terms exist, vernacular German traditionally uses a masculine generic, i.e. a generalised male plural form, to refer to large groups, even when those groups include people not identifying as male. This practice has become more and more contested in the last decades, especially in political spheres.

Our algorithm is designed to read .xml files from Bundestag plenary sessions (open source data available at https://www.bundestag.de/services/opendata) and create a .csv file from this data. This .csv file can then be scanned for usage of gendered terms (currently, gender-neutral terms can not be reliably found, sadly). This has allowed us to extract some interesting data from a small sample of three plenary sessions, accessible at https://public.tableau.com/profile/mirjam1307#!/vizhome/GenderME_Vis2/207TermsperSpeakerallspeakers. Currently, a lot of manual cleanup has to be done in OpenRefine. More details can be found in our pdf file 'Project Report' (upload coming soon).
