# Various Ru

Thanks to https://forum.language-learners.org/viewtopic.php?t=5799 for resources on Russian (some are listed below).

----

## FreeLing with Russian input

8. Data for Russian WordNet in file data/de/senses30.src is 
extracted from Universal WordNet ( https://www.mpi-inf.mpg.de/departments/databases-and-information-systems/research/yago-naga/uwn/ )
created by Gerard de Melo at Max Planck Institut.
It is distributed under its original CC-BY-NC-SA 3.0
license. [...]

//from https://github.com/pragmatic-strain/FreeLing/blob/master/COPYING

[TS-114] Option 'Full Parsing' not available for language 'ru'. //from http://nlp.lsi.upc.edu/freeling/demo/demo.php FreeLing 4.1

[TS-114] Option 'Semantic Graph' not available for language 'ru'. //from http://nlp.lsi.upc.edu/freeling/demo/demo.php FreeLing 4.1

[TS-114] Option 'NE [Named Entity? --p.strain] Classification' not available for language 'ru'. //from http://nlp.lsi.upc.edu/freeling/demo/demo.php FreeLing 4.1 with [x] Named Entity classification

[TS-114] Option 'Sense Annotation' not available for language 'ru'. //from http://nlp.lsi.upc.edu/freeling/demo/demo.php FreeLing 4.1 with [x] WN sense annotation: All senses 

[TS-114] Option 'Sense Annotation' not available for language 'ru'. //from http://nlp.lsi.upc.edu/freeling/demo/demo.php FreeLing 4.1 with [x] WN sense annotation: UKB disambiguation

[Empty] Analysis Results for utterance "Стол стоит" //from http://nlp.lsi.upc.edu/freeling/demo/demo.php FreeLing 4.1 with [x] No sense annotation and [x] Morph. Analysis

[Empty] Analysis Results for utterance "Стол стоит" //from http://nlp.lsi.upc.edu/freeling/demo/demo.php FreeLing 4.1 with [x] No sense annotation and [x] PoS tagging

----

https://www.sketchengine.co.uk/ = Sketch Engine contains 400 ready-to-use corpora in 90+ languages, each having a size of up to 20 billion word; lots of tools - alignment, bilingual term extraction, thesaurus, concordance, etc. A word sketch is a one-page summary of the word’s grammatical and collocational behaviour. It shows the word’s collocates categorised by grammatical relations such as words that serve as an object of the verb, words that serve as a subject of the verb, words that modify the word etc.

https://www.sketchengine.co.uk/skell/ - SkELL (Sketch Engine for Language Learning) is a simple tool for students and teachers of English to easily check whether or how a particular phrase or a word is used by real speakers of English. Also for Russian

----

https://github.com/NaturalNode/natural "Natural" is a general natural language facility for nodejs. Tokenizing, stemming, classification, phonetics, tf-idf, WordNet, string similarity, and some inflections are currently supported. Mostly for English, but Russian and Spanish stemming supported

----

https://open.xerox.com/Services/fst-nlp-tools, which includes
https://open.xerox.com/Services/fst-nlp-tools/Consume/Morphological%20Analysis-176
This tool produces a full morphological analysis of the submitted text for Czech, English, French, German, Spanish, Hungarian, Italian, Polish and Russian.
Part of speech tagging is also available; this tool assigns a part of speech (POS) tags to each word of the input text.
https://open.xerox.com/Services/fst-nlp-tools/Pages/API%20Docs has instructions on how to call the API, but there is a Web interface at the fst-nlp-tools link. 

----

https://nlpub.ru/MaltParser for Russian morphological analysis. "MaltParser — инструмент для работы с деревьями зависимостей. Позволяет построить модель по размеченному корпусу и строить деревья для новых данных основываясь на ней. Реализует несколько алгоритмов построения деревьев. По утверждениям авторов "достиг передовых показателей на некоторых языках". Для последней версии существуют готовые модели для английского, французского, шведского и испанского языков. Также существуют модели для русского языка, натренированные на корпусе SynTagRus и доступны для версий 1.5 и 1.7.2.

Модель для версии 1.7.2 (поддерживается также более поздними версиями, включая 1.9.0), подготовленная Мариленой Ди Бари, является результатом переобучения модели, разработанной Сергеем Шаровым для MaltParser версии 1.5. Инструмент распространяется под свободной лицензией."

----

For Russian morphological analysis, lemmatization, etc. see https://sourceforge.net/projects/phpmorphy/ . 

phpMorphy is morphological analyzer library written in pure PHP. Currently supports Russian, English and German languages.

License: LGPLv2

Website: http://phpmorphy.sourceforge.net/dokuwiki/

Intended Audience: Developers

Downloads: 77 This Week (Jan 20, 2020)

Last Updated: 2013

"Phpmorphy works excellent." 2013

"Great tool! Very helpful for me. Thanks!" 2012

phpMorphy – библиотека морфологического анализа, реализованная на платформе PHP.

## Возможности

phpMorphy позволяет решать следующие задачи:

 *    Лемматизация (получение нормальной формы слова)
 *    Получение всех форм слова
 *    Получение грамматической информации для слова (часть речи, падеж, спряжение и т.д.)
 *    Изменение формы слова в соответствии с заданными грамматическими характеристиками
 *    Изменение формы слова по заданному образцу

Поддерживаемые языки: Русский, Английский, Немецкий (AOT). Украинский, Эстонский (на основе ispell). Есть возможность добавить поддержку других языков при помощи myspell словаря.

Поддерживаются различные кодировки:

 *    все однобайтовые (windows-1251, iso-8859-* и т.п.)
 *    Unicode кодировки - utf-8, utf-16le/be, utf-32, ucs2, ucs4.

## Информация

 *    Документация
  *        Использование phpMorphy http://phpmorphy.sourceforge.net/dokuwiki/manual
  *        Описание грамматической информации http://phpmorphy.sourceforge.net/dokuwiki/manual-graminfo
  *        Система сборки
  *        Внутреннее устройство
  *        Формат файлов
 *     Скачать http://phpmorphy.sourceforge.net/dokuwiki/download
 *     Демонстрация работы http://phpmorphy.sourceforge.net/dokuwiki/demo
 *     Форум http://sourceforge.net/apps/phpbb/phpmorphy/
  *        тема на форуме phpclub http://phpclub.ru/talk/showthread.php?s=&threadid=96949&rand=207
 *     BugTracker https://sourceforge.net/apps/mantisbt/phpmorphy/

----

http://cst.dk/online/lemmatiser/uk/ - CST's lemmatizer uses affix rules (affix: prefix, infix, suffix, circumfix) and has been trained for a number of languages. Trained affix rules are available for the following languages: Bulgarian, Czech, Danish, Dutch, English, Estonian, Farsi, French, German, Greek, Hungarian, Icelandic, Italian, Latin, Macedonian, Polish, Portuguese, Romanian, Russian, Serbian, Slovak, Slovene, Spanish, and Ukrainian. 

----

TreeTagger (recommended): supports fr, en, es, de, ru, da

----

https://github.com/koorchik/node-mystem3 wrapper for Russian morphological analyzer

----

pymorphy2 is a morphological analyzer and generator for Russian and Ukrainian languages.

# AOT.ru

http://aot.ru/ - a website fetched to local backup at https://github.com/pragmatic-strain/aot-ru-backup/

# ruwn #

https://github.com/pragmatic-strain/RuWordNet - Various tools for generating and managing RuWordNet thesauri database

https://github.com/pragmatic-strain/RuWordNetView - Web interface for RuWordNet thesauri database

https://github.com/Zebradil/DictionaryWebEditor - ???

# RuThes + ruwn #

https://www.labinform.ru/pub/ruthes/

https://www.labinform.ru/pub/ruwordnet/index.htm - about, literature

https://www.labinform.ru/pub/ruwordnet/Noun/te/00/000/index.htm Cписок текстовых входов - СУЩЕСТВИТЕЛЬНЫЕ

https://www.labinform.ru/pub/ruwordnet/Adj/te/00/000/index.htm Cписок текстовых входов - ПРИЛАГАТЕЛЬНЫЕ

https://www.labinform.ru/pub/ruwordnet/Verb/te/00/000/index.htm Cписок текстовых входов - ГЛАГОЛЫ

# English WN #

https://wordnet.princeton.edu/

# Global WN #

http://globalwordnet.org/

http://compling.hss.ntu.edu.sg/omw/ - Open Multilingual Wordnet - a full site backup: https://github.com/pragmatic-strain/omw

http://compling.hss.ntu.edu.sg/omw/summx.html - Extended Open Multilingual Wordnet - Wordnet data http://compling.hss.ntu.edu.sg/omw/wn-wikt.tgz = http://compling.hss.ntu.edu.sg/omw/wn-wikt.zip = http://compling.hss.ntu.edu.sg/omw/wn-wikt.tar.bz2  - a full site backup: https://github.com/pragmatic-strain/omw

# OLAC Resources Ru #

 *   Primary texts
 *   Lexical resources
 *   Language descriptions
 *   Other resources about the language
 *   Other resources in the language

http://www.language-archives.org/language/rus

# Russian #

https://www.ethnologue.com/language/rus

ISO 639-3 : rus http://iso639-3.sil.org/code/rus

Population

138,000,000 in Russian Federation (Arefyev 2012), all users. L1 users: 119,000,000 (Arefyev 2012). Total users in all countries: 258,227,760 (as L1: 153,746,530; as L2: 104,426,230).

Language Status

1 (National). Statutory national language (1993, Constitution, Article 68(1)). Provincially recognized language in Dagestan Autonomous Republic (1994, Constitution of Dagestan Autonomous Republic, Article 10).

Classification

Indo-European, Balto-Slavic, Slavic, East

Dialects

North Russian, South Russian.

Typology

SVO; prepositions; genitives after noun heads; adjectives, numerals before noun heads; question word initial; 1 prefix on a word; recursive addition of suffixes allowed; gender (masculine/feminine/neuter); no articles; case-marking (6 cases); verb affixes mark person, number; passives; tense and aspect; comparatives; 32 consonants, 5 vowels, 4 diphthongs; non-tonal; free stress.

Language Development

Fully developed. Bible: 1680–2011.

Language Resources

OLAC resources in and about Russian http://www.language-archives.org/language/rus

Writing

Braille script [Brai]. Cyrillic script [Cyrl], primary usage.

Other Comments

Christian
