# Contributing to BloomCode

Thanks for helping. The most useful contributions are reports: a test that rejects a correct answer, a prompt that is unclear, a page that breaks on your phone.

## Report a problem

Open an issue on the repo you are working in, usually your starter's upstream (for example [dsa-python](https://github.com/bloomcode/dsa-python)). The issue form asks for the exercise id, what went wrong and your language version. A short piece of code that shows the problem makes it quick to fix.

## Where changes are made

- **Starters** (`dsa-python`, `cp-go`, ...) are generated. Don't open pull requests against them: they would be overwritten on the next sync.
- **Solutions repos** (`dsa-python-solutions`, ...) hold every exercise, its reference solution and its test. Fixes land here, then flow to the starter and the site.
- **bloomcode.github.io** holds the page templates and the concept guide; exercise text on the pages comes from the solutions repos.

Pull requests to a solutions repo are welcome for small, clear fixes. Each one must:

- keep the exercise block format (`==== EX ch.num | Title | Level`, then PROMPT, EXAMPLE and BIGO lines);
- pass the repo's tests and `python tools/check_track.py`;
- for the DSA track, change Python, Java and Go together, since the three share ids, titles, levels and examples.

For anything larger, open an issue first so we can agree on it.

## Originality

Everything here is original work. Don't copy exercises, text or code from books, courses or contest sites, and don't name them as sources.

## Conduct

Be kind and assume good faith. See the [code of conduct](CODE_OF_CONDUCT.md).
