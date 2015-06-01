# MovieTweetingsMappings
Mappings of movies from [MovieTweetings](https://github.com/sidooms/MovieTweetings) (published by [Simon Dooms](https://github.com/sidooms/MovieTweetings)) to DBpedia. 

## Format
CSV file, records separated by semicolon (**;**)
* id - id of movie in MovieTweetings
* title - title (year)
* genre - assigned genres
* uri - DBpedia URI
* method - method of mapping (perfect|partial|pattern|any)
* tc - title confidence
* yc - year confidence
* cc - genre confidence
* updated - datetime of last update

## Example
id | title | genre | uri | method | tc | yc | cc | updated
--- | --- | --- | --- | --- | --- | --- | --- | --- 
75148 | Rocky (1976) | Drama\|Sport | http://dbpedia.org/resource/Rocky | perfect | 1.0 | 1.0 | 1.0 |2015-06-01T11:33:06

## Confidence Values
### Title Confidence
:pencil:
### Year Confidence
:pencil:
### Genre Confidence
:pencil:

## Methods
* perfect - perfect match of title and year (e.g. Rocky, Rocky (film), Rocky (1976 film), etc.)
* partial - partial match of title and year
* pattern - pattern-based match of abstract (e.g. Rocky is a ... 1976 ..., Rocky ... released 1976 ..., etc)
* any - any partail match in asbtract (... also known as ..., German: ..., etc. )

## Contributors
- Jaroslav Kuchař (https://github.com/jaroslav-kuchar)
