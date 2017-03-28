# A 3rd Approach to Richard Feldman's alternatives

This is referring to the *MEAP* **[Elm in Action](https://www.manning.com/books/elm-in-action)** discussion in section **5.1.3**.

## What this is About

The author, **Richard Feldman**, explains two approaches, **Three Ints** and **One List of Records**,
and goes into some detail about the **pros** and **cons** of each of them.

I started thinking about a **3rd approach** which I hoped would combine the others' **pros** and leave
out the **cons**.  So the **Orange County Elixir/Elm** meetup had a hackfest in which we "mob
programmed" the 3rd alternative, **Combined**, which is presented here, along w/ the full implementations
of the first two alternatives.

Here are the branch names and what they contain:

| **Description** | **Branch Name** | **Purpose** | **Comment** |
|---|---|---|---|
| Before the filter | master | Show a baseline | Section **5.1.1** code |
| The **Three Ints** approach | three-ints | `type` each of the filters | Book chose this alternative |
| The **One List of Records** approach | one-list-of-records | One `type` for all filters | Not chosen |
| The **two approaches combined** | combined | `type` each of the filters while keeping `List` of filters | Worked well |
| The **two approaches combined** at the end of the hackfest | hackfest-result | Results of hackfest. | Better looking code than **combined** |
| Adding an additional filter | addFilter | Modify **combined** to add filter | Shows how easy `List` makes expansion |

So **git** can be easily used to compare any
implementation against any other.  I also added a branch that shows how easy it is to add another filter.

---

This is a checkpoint commit for the book Elm in Action.

See [the master branch](https://github.com/rtfeldman/elm-in-action) for what
this repository is all about!
