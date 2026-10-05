# Summary

The Bezeyni treebank is a small collection of annotated sentences in Bezeynî, a Kurdish language variety spoken in Turkey. The corpus contains 177 sentences with morphological and syntactic annotations following Universal Dependencies guidelines, providing basic coverage of nominal, verbal, and clause structures.

# Introduction

This treebank represents the first UD resource for Bezeynî dialect. The data consists of naturally occurring sentences and constructed examples illustrating core grammatical patterns of the language.
Language characteristics:
•	Bezeynî has an SOV word order
•	Rich case system with ergative alignment in past tenses
•	Extensive use of clitics and enclitic pronouns (e.g., malêyan 'their house' with =yan clitic)
•	Possessive constructions with Ezafe marker (e.g., kurê ewî 'his son')
Annotation specifics:
•	The treebank includes basic sentence types: declarative, interrogative, and imperative
•	Possessive relationships are annotated with nmod:poss (e.g., dötê tu 'your daughter')
•	Light verb constructions use compound:lvc (e.g., söz dame 'I gave word/promised')
•	Enclitic pronouns are split using multi-word tokens (e.g., jingelêyan → jingelê + yan)
Example sentence:
# text = Mêrike jingelê çûn we dêye .
# 'The man went to the women's place/mother.'
Mêrike jingelê çûn we dêye .
man-the women-of went to place
The treebank covers fundamental constructions including simple clauses, possessive phrases, relative clauses with the particle ke, and basic verb complementation patterns.



# Acknowledgments

We thank Cemile Çelebi for making this data available from her Master's thesis research on grammatical gender in Bezeynî Kurdish.

## References

* Çelebi, Cemile (2021). Zur Frage des grammatischen Genus im Bezeynî-Kurdischen. Eine empirische Untersuchung am Beispiel der Turin-Varietät. Goethe-Universität Frankfurt: Unpublished Master's thesis.


# Changelog

* 2025-11-15 v2.17
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.17
License: CC BY-SA 4.0
Includes text: yes
Parallel: no
Genre: TO-BE-SPECIFIED
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Asadpour, Hiwa
Contributing: here
Contact: asadpourhiwa@gmail.com
===============================================================================
</pre>
