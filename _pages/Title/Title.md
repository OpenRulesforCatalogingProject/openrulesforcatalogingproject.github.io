---
layout: single
type: docs
title: 1 - Title [Draft]
permalink: /ORC/title/
sidebar:
  nav: "docs"
---
A Title is the name by which a resource is known, typically assigned by
the creator or publisher. Titles may have variations due to
translations, abbreviations, placement on the item, or multiple parts.

## Contents:
{: .no_toc .text-delta }

- TOC
{:toc}

## 010100. Title proper (not repeatable)

Definition: The Title proper is the name of the resource being cataloged. An
alternative title---a second or additional title connected to the main
title using words like "or" or equivalent script in another
language---is part of the Title proper.

-   Source: Universal principle expressed in current cataloging codes; [ALA 1908 rules](https://babel.hathitrust.org/cgi/pt?id=mdp.39015033881775&view=1up&seq=17){:target="_blank"} (p. xiii, 43); 
BIBFRAME \"[Title](https://id.loc.gov/ontologies/bibframe.html#p_title){:target="_blank"}\"; 
[ISBD 2021](https://repository.ifla.org/server/api/core/bitstreams/202c522c-82e9-41ae-ab7c-d7227070142c/content){:target="_blank"}, 1.1.3.4.

**Rule:** Transcribe the Title proper.
Retain the word order, spelling, and punctuation, following [ISBD
2021](https://repository.ifla.org/server/api/core/bitstreams/202c522c-82e9-41ae-ab7c-d7227070142c/content){:target="_blank"}, 1.A-J
as appropriate. Retain any numbers or part names associated with
multipart monographs. Provide a transliteration of the Title proper if it
differs from the script of the language of the cataloging agency, such
as Cyrillic into a Romanized form. If the Title proper is ambiguous, include
additional information in square brackets. Symbols that cannot be
reproduced with Unicode characters can be written out where appropriate
or necessary, following conventions found in [LCRI 1.0E](https://www.loc.gov/catdir/cpso/lcri01_0e.pdf){:target="_blank"}.

If a resource does not bear a title or if it is a compilation with no
collective title, supply a Title proper found on an outside source, such as the
publisher's website; if no title can be found then the cataloger may
create one, following [ISBD 2021](https://repository.ifla.org/server/api/core/bitstreams/202c522c-82e9-41ae-ab7c-d7227070142c/content){:target="_blank"}, 1.A-J
and/or local practice. Add a note specifying the source if the Title proper is
not found on the resource.

If a title is preceded by an introductory statement or phrase, do not
include it in the Title proper. If a title includes a grammatically
linked statement of responsibility, include it in the Title proper.

-   Source: [LC 1949 rules](https://babel.hathitrust.org/cgi/pt?id=mdp.39015030341799&view=1up&seq=25){:target="_blank"} (p. 13, 27-28).

**MARC field:**
[245](https://www.loc.gov/marc/bibliographic/bd245.html){:target="_blank"} \$a \$n \$p

**EXAMPLES:**
<br>
>*Title transcribed from title page*
>
>245 10 \$a Anne of Green Gables / \$c by L.M. Montgomery ; illustrated by M.A. and W.A.J. Claus.

>*Alternative title*
>
>245 10 \$a Frankenstein, or, The modern Prometheus / \$c by Mrs. Shelley.

>*Ambiguous title*
>
>245 14 \$a The Joe Schmo \$b \[stories\]

>*Cataloger-supplied title*
>
>245 10 \$a \[Four poems\] / \$c Donald Finkel.  
>588 0\# \$a Title supplied by cataloger.

>*Transliteration of a title*
>
>245 10 Последние свидетели : \$b книга недетских рассказов / \$c Светлана Алексиевич.  
>245 10 Poslednie svideteli : \$b kniga nedetskikh rasskazov / \$c Svetlana Aleksievich. 

>*Title containing a symbol*
>
>245 10 \$a I \[love\] a piano  
>500 \#\# \$a On the title page, "love" appears as a heart.

>*Compilation with no collective title*
>
>245 00 \$a \[FBI documents regarding the St. Valentine\'s Day massacre\].  
>500 \#\# \$a Title from GPO Browse Electronic Titles listing.

>*Title containing number and part names*
>
>245 10 \$a Skull Cat. \$n Book 1, \$p Skull Cat and the curious castle / \$c Norman Shurtliff.

>*Title with introductory statement or phrase*
>
>245 14 \$a The little mermaid : \$b Ariel above the sea / \$c by Stephanie Calmenson ; illustrated by Franc Mateu.  
>246 3\# \$a Walt Disney presents The little mermaid

>*Title with grammatically linked statement of responsibility*
>
>245 10 \$a Edward Lear\'s The Scroobious Pip.  
>246 3\# \$a Scroobious Pip
>
>245 14 \$a The narrative of the life of Frederick Douglass.

<br>

[Return to Contents](#contents)

## 010200. Parallel title proper (repeatable)

**Definition:** The Parallel title proper is one or more titles in another language and/or script
from the same source of information as the Title proper.

-   Source: BIBFRAME \"[ParallelTitle](https://id.loc.gov/ontologies/bibframe.html#c_ParallelTitle){:target="_blank"}.\"

**Rule:** If the resource being cataloged has titles in two or more
languages, select as the Title proper the one representing the language
of the majority of the work. If no majority can be determined, select as
the Title proper the one in the language of the cataloging agency or the
one most appropriate to the user community. Transcribe all Parallel
titles proper deemed necessary. Optionally, add variant title fields for
Parallel titles proper if deemed important for discovery.

-   Source: [OLAC](https://cornerstone.lib.mnsu.edu/cgi/viewcontent.cgi?article=1027&context=olac-publications){:target="_blank"} (p. 101); 
[ICP](https://www.ifla.org/files/assets/cataloguing/icp/icp_2016-en.pdf){:target="_blank"}, 2.5 Sufficiency and Necessity (p. 5); [Cataloging Code of Ethics](https://alair.ala.org/server/api/core/bitstreams/9923a196-d345-4244-a07c-19450965f167/content){:target="_blank"} (part 2, item 8).

**MARC field:**
[245](https://www.loc.gov/marc/bibliographic/bd245.html){:target="_blank"} \$b
[246](https://www.loc.gov/marc/bibliographic/bd246.html){:target="_blank"} \$a

>**Examples:**
>
>*Parallel title proper*
>
>245 10 \$a Ah che la morte ognora = \$b Ah I have sighed to rest me
>
>*Parallel titles proper with variant title fields*
>
>245 10 \$a I︠A︡ vizhu sobaku = \$b Veo un perro = Ich sehe einen Hund =
Ani roʼeh kelev  
>246 31 \$a Veo un perro  
>246 31 \$a Ich sehe einen Hund  
>246 31 \$a Ani ro'eh kelev
>
>*Parallel title proper with subtitles*
>
> 245 00 \$a Nanotechnologies : \$b nanoscale calcium carbonate in powder form : characteristics and measurement = Nanotechnologies : 
carbonate de calcium á la nano-échelle sous forme de poudre : caractéristiques et mesurage / \$c \[prepared by Technical Committee ISO/TC 229, Nanotechnologies\].

<br>

[Return to Contents](#contents) 

## 010300. Subtitle (repeatable)

**Definition:** A word, character, or group of words and/or characters
that contains the remainder of the title after the Title proper.

-   Source: BIBFRAME "[Subtitle](https://id.loc.gov/ontologies/bibframe.html#p_subtitle){:target="_blank"}.\"

**Rule:** Transcribe the Subtitle in the same manner as the Title
proper. Optionally, if the Subtitle is very lengthy and can be abridged
without loss of essential information, omit less important words or
phrases using an ellipsis.

-   Source: [LC 1949 rules](https://babel.hathitrust.org/cgi/pt?id=mdp.39015030341799&view=1up&seq=25){:target="_blank"} (p. 13) ; 
[DCRMR 1.21.36](https://bsc.rbms.info/DCRMR/title/Title-proper/#12136-abridgments-of-the-title-proper){:target="_blank"}.

**MARC field:**
[245](https://www.loc.gov/marc/bibliographic/bd245.html){:target="_blank"} \$b

>**Examples:**
>
>*Subtitle*
>
>245 04 \$a The baby's bouquet : \$b a fresh bunch of old rhymes and tunes
>
>*Lengthy subtitle, complete*
>
>245 02 \$a A collection of voyages and travels, consisting of authentic
writers in our own tongue, which have not before been collected in
English, or have only been abridged in other collections : \$b and
continued with others of note, that have published histories, voyages,
travels, journals or discoveries in other nations and languages.
Relating to any part of the continent of Asia, Africa, America, Europe,
or the islands thereof, from the earliest account to the present time.
Digested according to the parts of the world, to which they particularly
relate: with historical introductions to each account, where thought
necessary, containing either the lives of their authors, or what else
could be discovered and was supposed capable of entertaining and
informing the curious reader. And with great variety of cuts, prospects,
ruins, maps, and charts. Compiled from the curious and valuable library
of the late Earl of Oxford. Interspersed and illustrated with notes.
Containing, either a general account of the discovery of those
countries, or an abstract of their histories, government, trade,
religion, &c. Collected from original papers, letters, charters, letters
patents, acts of Parliament, &c. Not to be met with, and proper to
explain many obscure passages in other collections of this kind / \$c
The whole compiled from undoubted authority, and the acts of Parliament
faithfully abridged, by a Gentleman of the Inner Temple.
>
>*Lengthy subtitle, abridged*
>
>245 02 \$a A collection of voyages and travels, consisting of authentic
writers in our own tongue, which have not before been collected in
English, or have only been abridged in other collections : \$b and
continued with others of note, that have published histories, voyages,
travels, journals or discoveries in other nations and languages.
Relating to any part of the continent of Asia, Africa, America, Europe,
or the islands thereof, from the earliest account to the present time
\.\.\. / \$c The whole compiled from undoubted authority, and the acts of
Parliament faithfully abridged, by a Gentleman of the Inner Temple.

<br>

[Return to Contents](#contents)

## 010400. Variant Title (repeatable)

**Definition:** A title associated with the resource that is different
from the Title proper, Parallel title proper, or Subtitle.

-   Source: BIBFRAME, "[VariantTitle](https://id.loc.gov/ontologies/bibframe.html#c_VariantTitle){:target="_blank"}," modified.

**Rule:** Record variations from the Title proper appearing elsewhere in
the resource including, but not limited to, cover title, caption title,
running title, or any other title by which the work might be known or
identified. Acronyms, initialisms or numbers can be written out where
appropriate or necessary. Other Variant titles may be added if deemed
necessary for clarity or access.

-   Source: [LC 1949 rules](https://babel.hathitrust.org/cgi/pt?id=mdp.39015030341799&view=1up&seq=40){:target="_blank"} (p. 28).

**MARC field:**
[246](https://www.loc.gov/marc/bibliographic/bd246.html){:target="_blank"} \$a

>**Examples:**
>
>*Titles from title page and spine*
>
>245 10 \$a Backpacking for fun & fitness  
>246 18 \$a Backpacking for fun and fitness
>
>or
>
>246 1\# \$i Spine title: \$a Backpacking for fun and fitness
>
>*Titles from title page and cover*
>
>245 00 \$a 10 Năm xây dựng và hoạt động của viện nghiên cứu KHKT bảo hộ lao động, 1981-1991.  
>246 14 \$a Mười năm xây dựng và hoạt động của Viện nghiên cứu KHKT bảo hộ lao động, 1981-1991
>
>or
>
>246 1\# \$i Cover title: \$a Mười năm xây dựng và hoạt động của Viện nghiên cứu KHKT bảo hộ lao động, 1981-1991
>
>*Title proper with numbers*
>
>245 10 \$a Summer of \'42.  
>246 3\# \$a Summer of 1942  
>246 3\# \$a Summer of forty-two  
>246 3\# \$a Summer of nineteen forty-two
>
>*Other title*
>
>245 10 \$a Aliens in the skies : \$b the scientific rebuttal to the Condon Committee report.  
>246 13 \$a Fuller report on unidentified flying objects  
>246 33 \$a Fuller report on UFOs
>
>245 10 \$a ICECS 2003 : \$b proceedings of the 2003 10th IEEE International Conference on Electronics, Circuits, and Systems  
>246 30 \$a 10th IEEE International Conference on Electronics, Circuits, and Systems  
>246 30 \$a Tenth IEEE International Conference on Electronics, Circuits, and Systems
>
>*Title with initialism*
>
>245 10 \$a ISBD : \$b International Standard Bibliographic Description  
>246 30 \$a International Standard Bibliographic Description
>
>*Portion of title (with initial article)*
>
>245 10 \$a Tele-revolution : \$b telephone competition at the speed of light : a history of the creation of a competitive local telephone
industry 1984-2000 / \$c by Richard G. Tomlinson.  
>246 30 \$a History of the creation of a competitive local telephone industry 1984-2000

<br>

[Return to Contents](#contents)

## 010500. Statement of responsibility relating to title proper (repeatable)

**Definition:** A statement about the persons or corporate bodies
responsible for significant intellectual or artistic contributions to
the work.

-   Source: BIBFRAME, "[responsibilityStatement](https://id.loc.gov/ontologies/bibframe.html#p_responsibilityStatement){:target="_blank"}," modified; 
[LCRI 1.1F1](https://web.archive.org/web/20200723075649/https://www.loc.gov/cds/PDFdownloads/csb/CSB_013.pdf#page=4){:target="_blank"}.

**Rule:** Transcribe the Statement of responsibility as it appears on
the resource. If a single name appears, transcribe it. If more than one name
appears, the cataloger may decide how many (or how few) names to record
according to local practice. Transcribe titles, honorifics, familial
terms or essential identifying words. If a Statement of responsibility
is grammatically linked to the title, record it as part of the Title
proper and do not repeat it. If the relationship between the Title  proper and
Statement of responsibility is not clear, the cataloger can supply a
bracketed phrase for clarity. Follow [ISBD 2021](https://repository.ifla.org/server/api/core/bitstreams/202c522c-82e9-41ae-ab7c-d7227070142c/content){:target="_blank"}, 1.A-J
regarding punctuation.

If a Statement of responsibility is not found on the item and is judged
necessary, add one following [ISBD 2021](https://repository.ifla.org/server/api/core/bitstreams/202c522c-82e9-41ae-ab7c-d7227070142c/content){:target="_blank"}, 1.A-J
and/or local practice. Include a note with an explanation of the source.

-   Source: [LCRI 1.1F1](https://web.archive.org/web/20200723075649/https://www.loc.gov/cds/PDFdownloads/csb/CSB_013.pdf#page=4){:target="_blank"}; 
[ISBD 2021](https://repository.ifla.org/server/api/core/bitstreams/202c522c-82e9-41ae-ab7c-d7227070142c/content){:target="_blank"}, 1.4.5.2; 
[LC-PCC-PS 2.4.1.4](https://original.rdatoolkit.org/document.php?id=lcpschp2&pagenum=4){:target="_blank"}.

**MARC field:**
[245](https://www.loc.gov/marc/bibliographic/bd245.html){:target="_blank"} \$c

>**Examples:**
>
>*Single personal name*
>
> 245 14 \$a The Plantagenets : \$b the warrior kings and queens who made England / \$c Dan Jones.
>
>*Multiple personal names with different roles*
>
> 245 14 \$a The story of buildings : \$b from the Pyramids to the Sydney Opera House and beyond / \$c written by Patrick Dillon ; illustrated by Stephen Biesty.
>
>*Corporate body*
>
>245 00 \$a Phantom encounters / \$c by the editors of Time-Life books.
>
>*Statement of responsibility supplied from external source*
>
>245 10 \$a Master builder respawned / \$c \[Jeff Cork\]. 
>588 0\# \$a Statement of responsibility taken from publisher\'s website, www.triumphbooks.com.
>
>*Multiple names with the same role, abridged*
>
>245 10 \$a 25 Jahre Eisenbahn / \$c Volker Dietel \[and others\].
>
>*Multiple names, complete*
>
> 245 10 \$a 25 Jahre Eisenbahn / \$c Volker Dietel, Johann Strauss, Gerhard Wolf, Manfred Knappe, Werner Markus.
>
>*Name with a title, honorific, or familial term*
>
>245 14 \$a The revolutionary line of action / \$c by Imam Khumeini.
>245 10 \$a Life is an adventure / \$c by Mrs. James Smith.
>245 10 \$a Childe Harold’s pilgrimage / \$c by Lord Byron.
>
>*Name with identifying words*
>
>245 10 \$a Git-r-done / \$c Larry the Cable Guy.
>
>*Statement of responsibility grammatically linked to title*
>
>245 14 \$a The narrative of the life of Frederick Douglass.
>
>*Cataloger-supplied relationship statement*
>
> 245 14 \$a The way of silence : \$b the prose and poetry of Basho / \$c \[edited by\] Richard Lewis ; photos by Helen Buttfield.
>
> *Transcribed with family terms or honorifics*
>
>245 10 \$a Evenings at home, or, the juvenile budget opened / \$c by Dr. Aikin and Mrs. Barbauld.
>
>245 10 \$a Cuba : \$b between reform and revolution / \$c Louis A. Pérez, Jr.

<br>

[Return to Contents](#contents)
