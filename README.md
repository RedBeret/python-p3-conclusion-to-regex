# Conclusion to Regular Expressions

## Learning Goals

- Validate that strings match specific patterns using regular expressions.
- Search for strings that match specific patterns using regular expressions.

***

## Key Vocab

- **Regular Expression**: a sequence of characters used to search for a pattern
inside of a string.
- **Pattern**: a description of sequences of characters that share certain
traits with one another. Sequences do not need to be the same length or share
any common characters to pattern match. Also called a **filter**.

***

## Conclusion

Regular expressions can be tricky, but there are many tools that will help you
craft patterns to check that strings match important patterns (like email
addresses and phone numbers) and search for these types of strings in massive
walls of text. We learned that:

- There is a near-universal regular expression language that stems from PERL.
- There are online tools to check your regular expression patterns as you go,
  such as [regex101][regex101].
- RegExes in Python are managed using the `re` module in the Python standard
  library.
- `search()`, `match()`, and `fullmatch()` return a single `re.Match` object if
  your RegEx pattern has a match in the search string.
- `findall()` returns a list of matching strings in the search string.
- `split()` and `sub()` can be used to modify strings where there are matches
  for a RegEx pattern.

We didn't cover everything about regular expressions in this module- there are
many nuances that you will learn throughout your software career. Make sure to
revisit regular expressions _regularly_ to keep building your skills.

***

## Resources

- [Python 3 Documentation](https://docs.python.org/3/)
- [re - Regular expression operations - Python](https://docs.python.org/3/library/re.html)
- [regex101][regex101]]
- [Python Regular Expressions - Google for Education](https://developers.google.com/edu/python/regular-expressions)

[regex101]: https://regex101.com
