# common-lisp-extensions

List of extensions beyond CL available in lisp implementations, and the status of its spread.
The progress can be seen in [the Kanban board in the Projects page](https://github.com/guicho271828/common-lisp-extensions/projects/1).
**This is a leaderboard for tracking the progress across implementations, not a place to post your new ideas. Unimplemented features will be closed immediately.** But it doesn't mean that you cannot fork some Lisp implementation and make a proposal here.

"Extensions" refers to the additional features implemented in the functions and macros in the `:common-lisp` package,
not the libraries based on the implementation-specific functions. For example, CAPI in Lispworks does not count as the
language extensions of CL.

Syntactic constructs implemented with macros on top of CL do not count as the "Extensions" either. Therefore, most public libraries
that provide macros are not considered "extensions" in this repository's term.

Similarly, simple reader macros (such as hash-table literals) are not considered "Extensions". However, features that require significant changes in the reader algorithm, such as package prefixed sexp and local package nickname, are considered extensions.

Compiler features are considered as "extensions". For example, `sb-ext:*inline-expansion-limit*` is an example of compiler extensions.

test
