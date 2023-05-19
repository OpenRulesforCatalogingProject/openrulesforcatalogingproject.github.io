---
layout: single
type: docs
title: 6 - Series (Repeatable) [DRAFT]
permalink: /ORC/series/
sidebar:
  nav: "docs"
---

Provide feedback <a href="https://docs.google.com/forms/d/e/1FAIpQLSd-VwSN3pr7TmccQcY3db5deCfdVN2sVGtrASC9RQdQOeEnzA/viewform" target="_blank">here</a>

Series are usually created by the publisher. A publisher assigns a
separate series title to a group of resources (such as books, DVDs,
periodicals, etc.) that have a common subject or theme. They may or may
not be numbered.

## Contents:
{: .no_toc .text-delta }

- TOC
{:toc}

## 060100. Series title

**Definition:** The series title is the title of a comprehensive
publication of which the resource is a part; includes the ISSN if known.

-   Source: BIBFRAME \"[Series](https://id.loc.gov/ontologies/bibframe.html#c_Series)\"; [LCRI 1.0](http://www.loc.gov/cds/PDFdownloads/csb/CSB_113.pdf) (p. 16).

**Rule:** Record the series title in a series statement.

Transcribe the titles of all the series of which the resource is a part.
If there is an inaccuracy in the series title, transcribe it as it
appears and add a note for the corrected version. If the series title is
grammatically linked to the title of the item being cataloged, include
it in the title proper, and transcribe it in a series statement.
Consider providing a controlled series added entry if required for
access.

-   Source: Universal principle expressed in current cataloging codes; [ALA 1908 rules](https://babel.hathitrust.org/cgi/pt?id=mdp.39015033881775&view=1up&seq=76) (p. 54), modified; [LCRI 1.6B](http://www.loc.gov/cds/PDFdownloads/csb/CSB_113.pdf) (p. 61).

**MARC field:**
[490](https://www.loc.gov/marc/bibliographic/bd490.html) \$a

>**Examples:**  
>  
>490 0\# \$aDepartment of State publication ; \$v7846  
>490 0\# \$aTime-Life library of art  
>490 0\# \$aEthnic groups in American life series  
>    
>490 1\# \$aThe Reference shelf  
>830 \#0 \$a Reference shelf  
>  
>Example of grammatically linked series title:  
>  
>245 10 \$aAndroid phones for dummies.  
>490 1\# \$aFor dummies  
>830 \#0 \$a--For dummies.
    
If a resource does not bear a series title but is known to be part of a
series, record the series and add a note justifying the addition. A
series title may be found on an outside source, such as the publisher\'s
website or catalog. Additionally a cataloger may create a series title
to bring together resources commonly treated as a series.

-   Source: Universal principle expressed in current cataloging codes; [ALA 1908 rules](https://babel.hathitrust.org/cgi/pt?id=mdp.39015033881775&view=1up&seq=76) (p. 54), modified; [LCRI 1.6B](http://www.loc.gov/cds/PDFdownloads/csb/CSB_113.pdf) (p. 61).

**MARC field:**
[490](https://www.loc.gov/marc/bibliographic/bd490.html) \$a

>Examples:  
>  
>245 10 \$aSeasonal associate  
>490 1\# \$aSemiotext(e) native agents series  
>588 \#\# \$aSeries statement from publisher's website.  
>830 \#0 \$aSemiotext(e) native agents series  
>  
>245 10 \$aFiction or nonfiction?  
>490 1\# \$aLibrary skills  
>588 \#\# \$aSeries statement from publisher's website.  
>800 1\# \$aMiller, Shannon \$q(Shannon McClintock). \$tLibrary skills.  
>  
>245 10 \$aBarney, a very musical day when Barney goes to the opera  
>490 0\# \$aBarney goes to series  
>500 \#\# \$aSeries created by cataloger.  

## 060200. Parallel title of a series or multipart monographic resource

**Definition:** A parallel title of a series is a title in another
language or script than the series title that is presented as an
equivalent of the title proper on the item.

-   Source: IFLA Element Sets \"[has parallel title of series or multipart monographic resource](https://www.iflastandards.info/isbd/elements#P1027),\" modified.

**Rule:** If the series title appears in more than one language, choose
the same language as the title proper for the series title. If the
resource being cataloged has series titles in two or more languages,
record all parallel series titles deemed necessary. Optionally, add a
note describing the languages of the recorded parallel series titles in
the order that they appear.

-   Source: [LC 1949 rules](https://babel.hathitrust.org/cgi/pt?id=mdp.39015030341799&view=1up&seq=43) (p. 31), modified; [LCRI 1.6C](https://www.loc.gov/cds/PDFdownloads/csb/CSB_079.pdf) (p. 12), modified.

**MARC field:**
[490](https://www.loc.gov/marc/bibliographic/bd490.html) \$a

>Examples:  
>  
>490 1\# \$aAnnual census of manufactures = \$aRecensement des manufactures, \$x0315-5587  
>490 1\# \$aGrundlagen der Kommunikation und Kognition = \$aFoundations of communication and cognition  
>490 1\# \$aResearch in text theory, \$x0179-4167 ; \$vv. 14 = \$aUntersuchungen zur Texttheorie  

## 060300. Other title information of a series or multipart monographic
resource

**Definition:** A word or phrase, or a group of characters, appearing in
conjunction with or subordinate to the title of the series. Includes
what is commonly known as the subtitle.

-   Source: IFLA Element Sets \"[has other title information of series or multipart monographic resource](http://iflastandards.info/ns/isbd/elements/P1028),\" modified.

**Rule:** Transcribe other title information of a series if necessary
for identification or for clarification of the scope of the resource.

-   Source: [LC 1949 rules](https://babel.hathitrust.org/cgi/pt?id=mdp.39015030341799&view=1up&seq=65) (p. 53), modified.

**MARC field:**
[490](https://www.loc.gov/marc/bibliographic/bd490.html) \$a

>Examples:  
>  
>490 1\# \$aDetroit area study, 1971 : social problems and social change in Detroit ; \$vno. 19  
>490 1\# \$aLooking into the past : people, places and customs  
>490 1\# \$aDino tales : life guides for families

## 060400. Statement of responsibility relating to a series

**Definition:** Statement relating to any persons, families, or
corporate bodies responsible for the creation of, or contributing to,
the content of a series.

-   Source: BIBFRAME \"[responsibilityStatement](https://id.loc.gov/ontologies/bibframe.html#p_responsibilityStatement).\"

**Rule:** Optional if essential for identification. If all of the
volumes of the series are by the same personal or corporate author or
authors, transcribe the statement of responsibility as it appears on the
chief source of information or on another prominent place on the item.

-   Source: [LC 1949 rules](https://babel.hathitrust.org/cgi/pt?id=mdp.39015030341799&view=1up&seq=44) (p. 32), modified.

**MARC field:**
[490](https://www.loc.gov/marc/bibliographic/bd490.html) \$a

>Examples:  
>  
>490 0\# \$aWild world series / Alan Sloan  
>490 0\# \$aDepartment of State publication  
>490 1\# \$aBulletin / U.S. Department of Labor, Bureau of Labor Statistics  
>490 1\# \$aThe Malloreon / David Eddings ; \$vbk. 2  
>490 1\# \$aMemoir / Colorado Archaeological Society

## 060500. International standard number of a series or multipart
monographic resource

**Definition:** An international standard number relating to a series or
multipart monograph, such as an International Standard Serial Number
(ISSN).

-   Source: IFLA Element Sets \"[has international standard number of series or multipart monographic resource](https://www.iflastandards.info/isbd/elements#P1030),\" modified.

**Rule:** Record the international standard number of the series or
multipart monograph if it is known. The international standard number
can come from any source.

-   Source: Universal principle expressed in current cataloging codes.

**MARC field:**
[490](https://www.loc.gov/marc/bibliographic/bd490.html) \$x

>Example:  
>  
>490 0\# \$aLife series, \$x0023-6721

## 060600. Numbering within a series or multipart monographic resource

**Definition:** Numbering or other enumeration and dates associated with
issues or items held of the series or multipart monograph.

-   Source: BIBFRAME \"[enumerationAndChronology](https://id.loc.gov/ontologies/bibframe.html#p_enumerationAndChronology),\" modified.

**Rule:** If there is volume, part, or number information on the item,
transcribe this after the series title and ISSN (if present). Transcribe
the volume designation or the date of issue or both, if both appear in
the series. The date may be dependent on the frequency of publication
and the usage of the publisher.

-   Source: [LC 1949 rules](https://babel.hathitrust.org/cgi/pt?id=mdp.39015030341799&view=1up&seq=65) (p. 53), modified.

**MARC field:**
[490](https://www.loc.gov/marc/bibliographic/bd490.html) \$v

>Examples:  
>  
>490 1\# \$aWest Virginia University bulletin ; \$vser. 74, no. 11-3  
>490 0\# \$aMusic educators newsletter ; \$vno.1492  
>490 1\# \$aResearch in Medieval studies ; \$vXVI  
>490 1\# \$aLund studies in geography, \$x 1400-1144 ; \$v 101

## 060700. Notes on series and multipart monographic resources

**Definition:** A note on the series or multipart monograph.

-   Source: IFLA Element Sets \"[has note on series and multipart monographic resources](https://www.iflastandards.info/isbd/elements#P1041),\" modified.

**Rule:** Add notes when necessary to explain the series or multipart
monographic resource, and to supply essential bibliographical details
not given in the series and multipart monographic resources area. Notes
may come from any source.

-   Source: [ALA 108 rules](https://babel.hathitrust.org/cgi/pt?id=mdp.39015033881775&view=1up&seq=77) (p. 55), modified.

**MARC field:**
[500](https://www.loc.gov/marc/bibliographic/bd500.html)  \$a

>Example:  
>  
>490 1\# \$aThe Convergence saga ; \$vbook one  
>500 \#\# \$aSeries title from jacket.

---