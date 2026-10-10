# Bilingual dictionaries

Learner's dictionaries in SQLite: every inflected form leads to its dictionary word, with a
translation, the main forms and example sentences. They are built from open, human-curated
sources, listed below with their authors and licenses.

| File | Words | Translated into | Size |
|---|---|---|---|
| [`swedish-russian.sqlite`](swedish-russian.sqlite) | Swedish, 119,216 words (32,957 translated), 879,430 forms | Russian | 44 MB |
| [`spanish-english.sqlite`](spanish-english.sqlite) | Spanish, 109,433 words, 1,146,837 forms | English | 46 MB |
| [`english-spanish.sqlite`](english-spanish.sqlite) | English, 62,473 words, 101,596 forms | Spanish | 13 MB |
| [`finnish-russian.sqlite`](finnish-russian.sqlite) | Finnish, 44,191 words (22,447 translated), 1,268,221 forms | Russian | 38 MB |

## License

Each file is an adaptation of the sources below and is licensed under
[Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/).
You may copy, change and use them for any purpose, including commercially, as long as you
credit the sources (this README does) and share your changes under the same license.

The sources' own licenses and credits travel with the data: each file's `meta` table holds them
under the key `sources`, and every example sentence from Tatoeba names its authors (see
[Examples](#examples)).

The files come as they are, without warranty of any kind.

## Sources

### `swedish-russian.sqlite`

| Source | Authors | Used for | License |
|---|---|---|---|
| [SALDO's morphology](https://doi.org/10.23695/agcm-ny22) | Språkbanken Text, University of Gothenburg | words, every inflected form | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| [Lexin Swedish–Russian](https://sprakresurser.isof.se/lexin/ryska/) | Institute for Language and Folklore (Isof) – Language Council of Sweden; Valery Alexandrov | translations, expressions, example sentences | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| [WikDict](https://www.wikdict.com) | Karl Bartel; Wiktionary contributors via [DBnary](http://kaiko.getalp.org/about-dbnary/) (Gilles Sérasset) | translations of words Lexin lacks | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |
| [Swedish Kelly list](https://doi.org/10.23695/6act-rs25) | Elena Volodina, Sofie Johansson Kokkinakis; Språkbanken Text | CEFR levels A1–C2 of 7,865 words | [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/)* |
| [Tatoeba](https://tatoeba.org) | Tatoeba contributors | which of several words a spelling usually is (Swedish sentences with Russian translations; no sentence is included) | [CC BY 2.0 FR](https://creativecommons.org/licenses/by/2.0/fr/) |

\* The Kelly page names two licenses (CC BY-SA 3.0 and LGPL 3.0 in its description, CC BY 4.0
in its download table); the stricter CC BY-SA 3.0 is given here. Kelly's authors ask to cite
Volodina & Johansson Kokkinakis (2012), *Introducing Swedish Kelly-list, a new free e-resource
for Swedish*, LREC 2012, and Kilgarriff et al. (2014), *Corpus-based vocabulary
lists for language learners for nine languages*, Language Resources and Evaluation 48:121–163.

### `spanish-english.sqlite`

| Source | Authors | Used for | License |
|---|---|---|---|
| [English Wiktionary](https://en.wiktionary.org), extracted by [kaikki.org](https://kaikki.org/dictionary/Spanish/) | Wiktionary contributors; extraction by wiktextract (Tatu Ylönen) | Spanish words, forms, English translations, expressions | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |
| [Tatoeba](https://tatoeba.org) | Tatoeba contributors, named with each example | example sentences with translations; word frequencies | [CC BY 2.0 FR](https://creativecommons.org/licenses/by/2.0/fr/) |

### `english-spanish.sqlite`

| Source | Authors | Used for | License |
|---|---|---|---|
| [English Wiktionary](https://en.wiktionary.org), extracted by [kaikki.org](https://kaikki.org/dictionary/English/) | Wiktionary contributors; extraction by wiktextract (Tatu Ylönen) | English words, forms, phrasal verbs, translation tables | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |
| [Spanish Wiktionary](https://es.wiktionary.org), extracted by [kaikki.org](https://kaikki.org/eswiktionary/) | Wikcionario contributors; extraction by wiktextract (Tatu Ylönen) | Spanish translations | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |
| [Tatoeba](https://tatoeba.org) | Tatoeba contributors, named with each example | example sentences with translations; word frequencies | [CC BY 2.0 FR](https://creativecommons.org/licenses/by/2.0/fr/) |

### `finnish-russian.sqlite`

| Source | Authors | Used for | License |
|---|---|---|---|
| [English Wiktionary](https://en.wiktionary.org), extracted by [kaikki.org](https://kaikki.org/dictionary/Finnish/) | Wiktionary contributors; extraction by wiktextract (Tatu Ylönen) | Finnish words, declension and conjugation tables, expressions | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |
| [Russian Wiktionary](https://ru.wiktionary.org), extracted by [kaikki.org](https://kaikki.org/ruwiktionary/) | Викисловарь contributors; extraction by wiktextract (Tatu Ylönen) | Russian translations | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |
| [WikDict](https://www.wikdict.com) | Karl Bartel; Wiktionary contributors via [DBnary](http://kaiko.getalp.org/about-dbnary/) (Gilles Sérasset) | Russian translations of words Russian Wiktionary lacks | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) |
| [Nykysuomen sanalista](https://kotus.fi/sanakirjat/kielitoimiston-sanakirja/nykysuomen-sana-aineistot/nykysuomen-sanalista/) | Kotimaisten kielten keskus (Institute for the Languages of Finland) | which untranslated words are standard Finnish | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| [Psycholinguistic Descriptives](http://urn.fi/urn:nbn:fi:lb-2018081601) | Tatu Huovilainen; University of Helsinki, the Language Bank of Finland | word frequencies | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| [Tatoeba](https://tatoeba.org) | Tatoeba contributors, named with each example | example sentences with translations | [CC BY 2.0 FR](https://creativecommons.org/licenses/by/2.0/fr/) |

Kotus asks to cite the word list as: Nykysuomen sanalista. Kotimaisten kielten keskus.
https://kaino.kotus.fi/lataa/nykysuomensanalista2024.txt

Wiktionary text is dual-licensed under CC BY-SA 4.0 and GFDL; it is used here under CC BY-SA 4.0.
Tatoeba sentences are CC BY 2.0 FR or CC0; sentences with unresolved licensing are not part of
Tatoeba's exports and so not used here.

## Changes made

The sources were not copied as they are. For each dictionary they were matched, filtered and
reorganized as follows; no translations were written by hand or by machine translation.

**Swedish–Russian**

- Every SALDO word with all its inflected forms; participles, genitives and subjunctives are
  marked as weaker readings of a form.
- Lexin's entries are matched to SALDO words by spelling and word class (Lexin's ordinal
  numerals to SALDO's adjectives: *andra*, второй); Lexin's translation comes first. A word
  Lexin, Kelly or WikDict files under another class than SALDO's takes it when SALDO knows the
  word in one class only and it is no verb (*anhörig*, *samtlig*); a one-word spelling takes
  Lexin's two-word one (*ikväll*: i kväll). Lexin's notes ("в идиомах", "см. …") are not used
  as translations. WikDict's Wiktionary links are resolved to their shown text
  ("[[трубка|трубку]]" → трубку). Where Lexin lists two words under one spelling and translates
  both (*andra*: второй, and другие as annan's plural), the entry gives both meanings. Places Lexin translates are kept (*Sverige*, Швеция). Words Lexin lacks get WikDict's translations, ranked by WikDict's importance score.
- Lexin's expressions and idioms are kept as entries of their own, keyed by their first word;
  reflexive pronouns are stored as *sig* (*känner mig* finds *känna sig*).
- Lexin's example sentences with their Russian translations (up to three) are attached to their words.
- Kelly levels are attached to the matching words.
- Where a spelling belongs to several words (*bad*: a bath, or *be*'s past "asked"), the word
  the Russian translations of Tatoeba's Swedish sentences with it point to is read first, when
  clearly so; a Kelly word never gives way to one off the list. A noun's second spelling of a
  form that is another word (*bit* beside *biet* for *bi*) is marked weak.
- Forms that start compounds are listed for splitting compounds (`parts`).

**Spanish–English**

- Spanish lemmas with their inflected forms, including verb forms with attached pronouns
  (*dámelo*, *siéntate*); archaic, rare and misspelled forms are left out or marked weak.
- English translations are taken from Wiktionary's sense glosses, shortened to the gloss's
  translation part (not a clarifying note such as "As a temporary state"); slang, vulgar,
  obsolete and dated senses are skipped. A word with no other sense may take a sense marked
  nonstandard, rare or colloquial for Latin America or Spain as a whole (*regresar*), never
  slang or one country's usage, and never when the word is a form of another or a name.
- A form with a meaning of its own beside its word's gets an entry: *hay* (there is, there
  are), *los hijos* (sons, children), *les* (to them), *peor* (worse).
- Places whose English name is written otherwise are kept (*España*, Spain; *Londres*, London),
  not given names (*Sofía*), and so are names of several words translated otherwise (*Semana
  Santa*, Holy Week). Places of several words written the same in English are listed in `names`
  (*Costa Rica*, *La Paz*).
- *ir a* counts as a construction before an infinitive only in the present, imperfect and
  subjunctive.
- Where a form belongs to
  several words (*vino*: wine, or "came"), the reading Tatoeba's translations point to is preferred.
- Where Tatoeba's translations of a word's sentences clearly point to a later sense than
  Wiktionary's first, that sense is used (*carne*: meat). Function words don't count as evidence,
  common words only beyond chance, phrasal verbs as a pair (*put on*). A verb's reflexive senses
  belong to the reflexive verb (*acordar*: agree; *acordarse*: remember), which picks its sense
  from sentences with the pronoun written apart (*se puso*: put on) and takes no slang sense.
- Reflexive verbs and expressions with a reflexive pronoun (*darse cuenta*) are listed with every
  pronoun they take (`reflexives`); multiword expressions are keyed by their first word, and
  constructions followed by an infinitive (*ir a* + infinitive) are marked `+inf`.
- Feminine nouns get their own entries where Wiktionary lists them as female forms
  (*profesora*: teacher).
- Up to two short Tatoeba sentence pairs per word as examples.
- An importance score from how often Tatoeba's sentences use the word and its forms.

**English–Spanish**

- English lemmas with their inflected forms; phrasal verbs with all their forms (*gave up*,
  *given up*).
- Spanish translations from Spanish Wiktionary's meanings, kept when English Wiktionary's
  translation table for the word's main sense confirms them; otherwise the table's own Spanish
  words, the rare ones dropped by how often Tatoeba's Spanish uses them.
- Lowercase nouns that in running text are nearly always a person's name are left out
  (*tom*: Tom).
- Phrasal verbs get up to three meanings, in the order of how often the Spanish translations of
  Tatoeba's sentences show them (*give up*: rendirse; abandonar).
- Constructions followed by an infinitive (*be going to*, *have to*) are marked `+inf`.
- Up to two Tatoeba sentence pairs per word, chosen so their Spanish shows the translation, one
  per meaning first.
- An importance score from how often Tatoeba's sentences use the word and its forms.

**Finnish–Russian**

- Finnish lemmas with every form of their declension or conjugation tables; a negative verb
  form gives its main verb (*en tiedä* → *tiedä*). Possessive forms (*talossani*) are not
  listed: cut the suffix off and look up the rest. Only the possessive stem that differs from
  every listed form is kept, as a weak form (*käsi*: *käte-ni* → `käte`).
- Russian translations from Russian Wiktionary's meanings, up to three words: two from the first
  sense, then the first word of the following senses (*väärä*: кривой, согнутый; неверный).
  Labels, Latin names, stress marks and glosses that describe a form of another word are
  removed. Words Russian Wiktionary lacks take WikDict's checked translations, without the few
  obscene ones; its unchecked ones are not used. A source that files a word under a part of
  speech the word has nowhere else is used too (*moni*: a pronoun in one Wiktionary, an
  adjective in the other).
- Spoken Finnish as textbooks print it: forms English Wiktionary marks as alternative or
  colloquial lead to the standard word (*ku* → *kun*, *sit* → *sitten*), the spoken pronouns'
  forms to the standard pronouns (*sä*, *sun*, *sulla* → *sinä*), and a few spoken forms no
  source lists are added (*oo* → *olla*, *meiän* → *me*). These are weaker readings (`weak` 1–2).
- Forms of a form follow the chain (*niistä* → *ne* → *se*); a form that is also a word of its
  own about as common, or a rare case (instructive, comitative), is a weaker reading (*yli*,
  *hyvin*, *noin* are words first).
- Names only with a translation (*Suomi* → Финляндия).
- Every translated word is kept; untranslated ones only when they are on the Kotus list and
  common (at least 1,000 uses in Psycholinguistic Descriptives' corpora), one entry per word.
- Forms that start compounds (the nominative and the genitive singular) are listed in `parts`.
- Up to two Tatoeba sentence pairs per word, chosen so their Russian shows the translation; a
  word spelled like a commoner one (*voi*, butter, beside *voi*, can) takes only sentences that
  show it.
- An importance score from Psycholinguistic Descriptives' lemma frequencies.

## Format

All files share one schema (`reflexives` and `names` only in Spanish).

| Table | Columns | What it holds |
|---|---|---|
| `entries` | `id`, `lemma`, `pos`, `display`, `forms`, `translation`, `importance`, `examples`, `level` | One row per word or expression. `display` is the dictionary form as learners see it (*att tala*, *to go*). `forms` is a JSON list of `[label, form]` pairs. `translation` is comma-separated, meanings separated by `; `. `level` is a CEFR level 1 (A1) – 6 (C2), 0 when unknown. |
| `forms` | `form`, `entry_id`, `weak` | Every lowercased inflected form → its word. `weak = 1` marks a rare or secondary reading. |
| `parts` | `form`, `entry_id` | Forms a word takes as the first part of a compound (Swedish). |
| `phrases` | `head`, `rest`, `entry_id` | Multiword expressions by their first word, in any of its forms: `gave` + `up` → *give up*. A trailing `+inf` means the expression only counts before an infinitive. |
| `reflexives` | `form`, `pronoun`, `entry_id` | Spanish: a verb form and the reflexive pronoun before it → the reflexive verb (`levanto` + `me` → *levantarse*). |
| `names` | `head`, `name` | Spanish: places of several words, as written, keyed by their lowercased first word (`costa` → *Costa Rica*). |
| `meta` | `key`, `value` | `translation_languages`, `language` (ISO 639-1) and `sources` (JSON: name, authors, license, links). |

### Examples

`examples` is a JSON list of `[sentence, translation]` pairs, with a third element for Tatoeba
sentences: `tatoeba:<sentence id>:<author>:<translation id>:<author>`. Tatoeba's license asks to
name each sentence's author: the sentence is at `https://tatoeba.org/en/sentences/show/<sentence id>`.
An empty author means Tatoeba records none.

```sql
SELECT e.display, e.translation, e.examples
FROM forms f JOIN entries e ON e.id = f.entry_id
WHERE f.form = 'gave' ORDER BY f.weak, e.importance DESC;
```
