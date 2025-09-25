# Repository Instructions

The guidelines below apply to the entire repository.

- Follow the existing coding style of the surrounding files.
- Keep documentation in sync with code updates when appropriate.
- Use clear, descriptive commit messages that summarize the change set.
- Before invoking any CMake build or test, make sure the source tree is reachable
  at `<parent>/usml` (rename the checkout to `usml` or create a `usml`
  symlink pointing to this directory) so includes such as
  `<usml/ublas/randgen.h>` resolve correctly.
- Run the CMake-based builds or unit tests that are relevant to your changes
  and report their status in the final summary.

