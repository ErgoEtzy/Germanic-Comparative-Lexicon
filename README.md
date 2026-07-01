# Germanic Comparative Lexicon
PIE / Germanic Comparative Lexicon
======================

A collection of Proto-Indo-European, Proto-Germanic, and Old Germanic lexical notes in Markdown format, made for use in Obsidian.

The purpose of this folder is to gather historical word forms into single comparative pages, so that one reconstructed root or Proto-Germanic anchor can show related forms across older Germanic languages such as Old Norse, Gothic, Old English, Old High German, Old Saxon, Old Frisian, Old Dutch, Old Swedish, Old Danish, and Old Gutnish.

This is meant as a working philological lexicon, not as a final scholarly dictionary.


Folder structure
----------------

    Germanic Comparative Lexicon
    ├── README.md
    ├── _Index.md
    ├── *audaz.md
    ├── *dagaz.md
    ├── *þunraz.md
    ├── *wōdanaz.md
    └── ...

General principle
-----------------

Each note should ideally be organized by a reconstructed historical anchor.

For Germanic material, the main anchor is usually Proto-Germanic:

    *dagaz
    *þunraz
    *wōdanaz
    *audaz

Proto-Indo-European belongs as the deeper background layer when available, but the page itself may still be named after the Proto-Germanic form if the note is mainly about Germanic descendants.

Example:

    # *dagaz

    ## Proto-Indo-European layer
    - Root:
    - Meaning:
    - Certainty:

    ## Proto-Germanic anchor
    - *dagaz
    - Meaning:
    - Grammatical class:

    ## East Germanic
    ### Gothic
    - dags

    ## North Germanic
    ### Old Norse
    - dagr

    ## West Germanic
    ### Old English
    - dæġ

    ### Old High German
    - tag

    ### Old Saxon
    - dag

    ## Sound laws
    - Relevant sound changes
    - Grimm's Law
    - Verner's Law, if relevant
    - Umlaut, breaking, contraction, rhotacism, or other later developments

    ## Semantic field
    - Day
    - Time
    - Light
    - Ritual/calendar associations, if relevant

    ## Notes
    - Personal observations
    - Symbolic or mythological links
    - Cautions and uncertainties

File format
-----------

Each lexical note can follow this general structure:

    # Reconstructed form or main lemma

    ## Proto-Indo-European layer
    - PIE root:
    - Meaning:
    - Morphology:
    - Certainty:
    - Source:

    ## Proto-Germanic anchor
    - Form:
    - Meaning:
    - Morphology:
    - Reconstruction notes:
    - Source:

    ## East Germanic
    ### Gothic
    - Form:
    - Meaning:
    - Attestation:

    ## North Germanic
    ### Old Norse
    - Form:
    - Meaning:
    - Attestation:

    ### Old Icelandic / later Icelandic
    - Form:
    - Meaning:
    - Notes:

    ### Old Swedish
    - Form:
    - Meaning:
    - Notes:

    ### Old Danish
    - Form:
    - Meaning:
    - Notes:

    ### Old Gutnish
    - Form:
    - Meaning:
    - Notes:

    ## West Germanic
    ### Old English
    - Form:
    - Meaning:
    - Attestation:

    ### Old Saxon
    - Form:
    - Meaning:
    - Attestation:

    ### Old High German
    - Form:
    - Meaning:
    - Attestation:

    ### Old Frisian
    - Form:
    - Meaning:
    - Attestation:

    ### Old Dutch
    - Form:
    - Meaning:
    - Attestation:

    ## Sound laws
    - PIE to Proto-Germanic:
    - Proto-Germanic to Old Norse:
    - Proto-Germanic to Gothic:
    - Proto-Germanic to Old English:
    - Proto-Germanic to Old High German:
    - Other developments:

    ## Semantic development
    - Earlier meaning:
    - Later meanings:
    - Metaphorical extensions:
    - Mythological or ritual relevance:

    ## Sources
    - Wiktionary / Wiktextract / Kaikki:
    - Kroonen:
    - Orel:
    - Ringe:
    - de Vaan:
    - Cleasby-Vigfusson:
    - Zoëga:
    - Bosworth-Toller:
    - Fritzner:
    - Other:


Source layer
------------

Many automatically generated notes in this folder may originate from English Wiktionary data processed through Wiktextract / Kaikki.

Pipeline:

    English Wiktionary
    → Wikimedia dump
    → Wiktextract / Kaikki structured JSONL
    → local Python conversion script
    → Obsidian Markdown notes

These files should be treated as a useful research index or lexical quarry.

They should not be treated as final authority without verification against stronger philological sources.

License
-------

No license has been chosen yet unless a LICENSE file is added.
