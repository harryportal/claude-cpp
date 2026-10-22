# C++ and OS Practice

Problem sets with expected output and worked solutions, as static HTML pages.

- Open `index.html` to start. Each topic page keeps its own progress in the browser (localStorage).
- The C++ and STL pages can be read in any browser. Run the programs yourself with `g++ -std=c++23 -pthread`.
- The OSTEP page uses POSIX system calls, so run those programs on Linux (or WSL).

## Updating the site

1. Replace or add the changed `.html` files at the top level of this repo.
2. Update `index.html` if a topic was added or renamed.
3. Commit and push. With GitHub Pages enabled on the `main` branch, the site redeploys automatically.

## Publishing with GitHub Pages

Settings → Pages → Build and deployment → Source: "Deploy from a branch" → Branch: `main`, folder `/ (root)`.
