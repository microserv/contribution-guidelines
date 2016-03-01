# Contribution guidelines
- [How to write commit messages](#commit-messages)
  * [Content](#content)
  * [Formatting](#formatting)
- [Coding rules](#rules)
  * [Python](#python)
- [Licenses](#licenses)

## <a name="commit-messages"></a> How to write commit messages
A good commit message should concisely answer three questions about a patch:

#### Content
* Why is it necessary? It may fix a bug, it may add a feature, it may improve performance, reliabilty, stability, or just be a change for the sake of correctness.
* How does it address the issue? For short obvious patches this part can be omitted, but it should be a high level description of what the approach was.
* What effects does the patch have? (In addition to the obvious ones, this may include benchmarks, side effects, etc.)
* In general; explain what and why instead of how (as how is usually explained through the code).

#### Formatting
1. Separate subject from body with a blank line
2. Capitalize the subject line
3. Use the imperative mood in the subject line

## <a name="rules"></a> Coding rules
Will be added whenever we have decided on some general rules and style guides.

### Python
[PEP8](https://www.python.org/dev/peps/pep-0008/) (Using flake8)  
[Sorted imports](https://pypi.python.org/pypi/isort) (using isort)

## Licenses
We'll need to figure this one out. [MIT](https://tldrlegal.com/license/mit-license) should work for most of our code, but we'll have to be careful when including third party libraries.

