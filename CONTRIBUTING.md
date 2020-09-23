Overview
===
Formalize each and every tag in Stacks project.  Each section should be in a separate file.  The stacks project is mostly self-contained, but if some preliminary is required (e.g., basic facts about groups), put the file under the `Foundation` directory.

Naming convention
===
Follow the [naming convention](https://github.com/arend-lang/arend-contrib/blob/master/CONTRIBUTING.md) of arend-contrib.

Comments
===

Each tag in Stacks project should be discussed.  Use comments to mark corresponding parts in the source.  If some items are not applicable (e.g., automatic in the type-theoretic setting), explain why no code is needed in comments.

If the formalization is notably different from the set-theoretic setting, explain how hPOV simplifies or complicates things with comments starting with "hPOV:".  We currently do not distinguish the more precise cause (constructivity, infinite hierarchy of universes, or the homotopy interpretation of path types).

If there is some space for improvement on the Arend side, mark them with comments starting with "Arend:" and report issues on [their GitHub repository](https://github.com/JetBrains/Arend).
