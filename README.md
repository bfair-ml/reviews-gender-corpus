# Reviews Gender Corpus

The corpus consists of 70 IMDB reviews which were manually annotated as male-related, female-related, or both or none of them.
The reviews are sourced from the [IMDB Review Dataset](https://aclanthology.org/P11-1015), which includes the text of the reviews and a positive or negative label, depending on whether the review transmits a positive sentiment or not.

Data is available in `data/reviews.csv`.

## Example of data instance

```json
{
    "Review": "An unmarried woman named Stella (Bette Midler) gets pregnant by a wealthy man (Stephen Collins). He offers to marry her out of a sense of obligation but she turns him down flat and decides to raise the kid on her own. Things go OK until the child named Jenny (Trini Alvarado) becomes a teenager and things gradually (and predictably) become worse. I've seen both the silent version and sound version of \"\"Stella Dallas\"\". Neither one affected me much (and I cry easily) but they were well-made if dated. Trying to remake this in 1990 was just a stupid idea. I guess Midler had enough power after the incomprehensible success of \"\"Beaches\"\" to get this made. This (predictably) bombed. The story is laughable and dated by today's standards. Even though Midler and Alvarado give good performances this film really drags and I was bored silly by the end. Stephen Collins and Marsha Mason (both good actors) don't help in supporting roles. Flimsy and dull. Really--who thought this would work? See the 1937 Stanwyck version instead. I give this a 1.",
    "Gender":  "Male, Female",
    "Sentiment": "negative",
}
```

## License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Reviews Gender Corpus</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.<br />