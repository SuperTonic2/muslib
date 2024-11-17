---
title: Technical Information
layout: about
permalink: /tech.html
credits: true

---

{% include feature/nav-menu.html sections="Metadata Application Profile;Controlled Vocabularies" %}

# Technical Information  

## Metadata Application Profile  

To view the full metadata schema utilized in this repository, click [here](https://docs.google.com/spreadsheets/d/1PvK1NRvZtL4LyIbZMC4yMWe5YQd6tnDZsBhuEOZfVbI/edit?usp=sharing)!

### Context, Content, Users, and Functional Requirements

**Context:** The Music Librarianship at IU digital collection consists of documents and photographs documenting the history of the music library and the music librarianship program at Indiana University Bloomington. The collection covers the hiring of IU’s first music librarian, Ethel Louise Lyman, in 1939, the start of the Graduate Library School’s Music Librarianship specialization and dual degree programs in 1979, and modern activities related to music librarianship at Indiana University into the present day.  

**Content:** The collection will include digitized images and documents as well as born-digital objects retrieved from the archival collections of the Indiana University Archives, Indiana University Archives of Institutional Memory, and Indiana University Cook Music Library.  

**Users:** Potential user groups for the repository include past, current, and future IU music and music librarianship students; individuals researching the history of music libraries or music librarianship in general; and other institutions looking to create music librarianship programs.

**Functional Requirements:**  

* Allow users to search/browse by:
    * Titles of formal documents (in search field)
    * Creators, publishers, and other contributors (in search field and browse)
    * Date Created (in search field, browse, and, and timeline)
    * Subjects (in search field and browse)
* Allow users to identify the following information about items:
    * Source repository and collection information
    * Permalinks to born-digital or previously digitized items
    * Existence of related items or collections
    * Copyright status
* Include the following non-visible technical information required for CollectionBuilder functionality:
    * Object ID
    * Parent Object ID (for compound objects)
    * File Name
    * Item Information
    * Latitude & Longitude
    * Item Type
    * Language

## Controlled Vocabularies

This collection utilizes a combination of multiple different controlled vocabularies, including both local vocabularies created specifically for this repository and established vocabularies. Information about each of these vocabularies can be found below.

### Local Vocabularies

#### Local Subject Headings  

* Indiana University, Bloomington. B. Winfred Merrill Hall  
    * Scope: Refers to B. Winfred Merrill Hall located at 1201 E 3rd Street, Bloomington, Indiana on the campus of Indiana University, Bloomington.  
* Indiana University, Bloomington. Music Librarianship Program  
    * Scope: Refers to any academic program at Indiana University, Bloomington that was created to train students to enter the profession of music librarianship. Includes the Music Librarianship Specialization in the Master of Library Science program and the dual degree Master of Library Science and Master of Arts in Music programs.  
  
Metadata fields in this repository that utilize Local Subject Headings:
* Subjects  
  
#### Local Locations  

##### Syntax For Entire Buildings  

[Building Name] ([Street Address], [City], [State])  

##### Syntax for an Area (Room, Department, etc.) Within a Building  

[Area Name] ([Building Name], [Room Number (if applicable)], [Street Address], [City], [State])  

##### Location List  

* B. Winfred Merrill Hall (1201 E 3rd Street, Bloomington, Indiana)
    * Coordinates: 39.1646971, -86.5182848
* Bess Meshulam Simon Music Library and Recital Center (200 S Eagleson Avenue, Bloomington, Indiana)
    * Coordinates: 39.1649980, -86.5173410
    * Building Areas (use same coordinates as parent):
        * William and Gayle Cook Music Library (Bess Meshulam Simon Music Library and Recital Center, 200 S Eagleson Avenue, Bloomington, Indiana)  
* Herman B. Wells Library, 1320 E 10th St, Bloomington, Indiana  
    * Coordinates: 39.1709799, -86.5171803
    * Building Areas (use same coordinates as parent):
        * Graduate Library School (Herman B. Wells Library, 1320 E 10th St, Bloomington, Indiana)
        * School of Library and Information Science (Herman B. Wells Library, 1320 E 10th St, Bloomington, Indiana)  
* Indiana University Memorial Union (900 E 7th Street, Bloomington, Indiana)  
    * Coordinates: 39.1678643, -86.5247164
    * Building Areas (use same coordinates as parent):
        * Georgian Room (Indiana University Memorial Union, 900 E 7th Street, Bloomington, Indiana)
        * Graduate Library School Alumni Association Office (Indiana University Memorial Union, Room M-17, 900 E 7th Street, Bloomington, Indiana)  
* Margrave Apartments (736 E 3rd Street, Bloomington, Indiana)
    * Coordinates: 39.1639121, -86.5243768  
* William Lowe Bryan Hall (1020 E Kirkwood Ave, Bloomington, Indiana)
    * Coordinates: 39.1660722, -86.5266489  
  
Metadata fields in this repository that utilize Local Locations:
* Location  
* Latitude  
* Longitude  
  
### Established Vocabularies

#### [Library of Congress Name Authority File (LCNAF)](http://id.loc.gov/authorities/names)  

*"The Library of Congress Name Authority File (NAF) file provides authoritative data for names of persons, organizations, events, places, and titles. Its purpose is the identification of these entities and, through the use of such controlled vocabulary, to provide uniform access to bibliographic resources. Names descriptions also provide access to a controlled form of name through references from unused forms."*  

In this repository, parenthetical qualifiers that are included with a name authority are included (ex. "Adams, John (Conductor)") but dates are excluded (ex. "Adams, John Couch, 1819-1892" is just "Adams, John Couch").

Metadata fields in this repository that utilize LCNAF:
* Creator
* Publisher
* Contributor
* Recipient
* Related Resources
* Source Repository

#### [Library of Congress Subject Headings (LCSH)](http://id.loc.gov/authorities/subjects)  

*"Library of Congress Subject Headings (LCSH) has been actively maintained since 1898 to catalog materials held at the Library of Congress. By virtue of cooperative cataloging other libraries around the United States also use LCSH to provide subject access to their collections."*

This repository includes any parenthetical qualifiers listed in LCSH subject headings. It also avoids using subject subdivisions (ex. Cats--Adoption) as they are not properly supported in CollectionBuilder's browse function.

Metadata fields in this repository that utilize LCSH:
* Subjects

#### [Getty Thesaurus of Geographic Names (TGN)](http://id.loc.gov/authorities/names)  

*"TGN is a unique thesaurus that is global in scope but not comprehensive, focusing on places relevant to art, architecture, and related disciplines. Included are place names, rich relationships, place types, dates, notes, and coordinates for historical and current cities, nations, empires, archaeological sites, lost settlements, and physical features"*

Paranthetical qualifiers supplied by TGN (ex. "(inhabited place)") are excluded in this repository.

Metadata field in this repository that utilize TGN:
* Location

#### [Rights Statements.org Standardized Rights Statements](https://rightsstatements.org/)

Metadata fields in this repository that utilize Standardized Rights Statements:
* Rights
* Rights Statement

#### [Dublin Core Metadata Type Vocabulary (DCMI Type Vocabulary)](https://www.dublincore.org/specifications/dublin-core/dcmi-type-vocabulary/2003-02-12/)

*"The DCMI Type Vocabulary provides a general, cross-domain list of approved terms that may be used as values for the Resource Type element to identify the genre of a resource."*

Metadata fields in this repository that utilize DCMI Type Vocabulary:
* Type

#### [ISO 639-2 Language Codes](https://www.loc.gov/standards/iso639-2/php/code_list.php)

This repository uses Bibliographic ISO 639-2 codes (as opposed to Terminology codes).

Metadata fields in this repository that utilize ISO 639-2 Language Codes:
* Language
