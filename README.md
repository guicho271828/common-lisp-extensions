# common-lisp-extensions

List of extensions beyond CL available in lisp implementations, and the status of its spread.

"Extensions" refers to the additional features implemented in the functions and macros in the `:common-lisp` package,
not the libraries based on the implementation-specific functions. For example, CAPI in Lispworks does not count as the
language extensions of CL.

Syntactic constructs implemented with macros on top of CL do not count as the "Extensions" either. Therefore, most public libraries
that provide macros are not considered "extensions" in this repository's term.

Similarly, simple reader macros (such as hash-table literals) are not considered "Extensions". However, features that require significant changes in the reader algorithm, such as package prefixed sexp and local package nickname, are considered extensions.

Compiler features are considered as "extensions". For example, `sb-ext:*inline-expansion-limit*` is an example of compiler extensions.

One extention could be spread across various implementations. The aim of this repository is to track the support status from each implementation. Progress is tracked in the Github Project feature available in the Projects tab.
