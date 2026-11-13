# Chainguard Project Theseus feedback
 
This repository is where to report problems with [Chainguard Project
Theseus](https://github.com/chainguard-project-theseus/) and its Guarded Components.
 
## Filing an issue
 
Try a component in a test environment. If something breaks, or behaves
differently from the component it replaces, open an issue here. Please
file one issue per problem.
 
Include:
 
- **The component and its version.** For challoc, the package version,
  plus the feature line from `challoc_features()` or
  `malloc_stats_print` if you can get it.
- **Where it ran.** The image or distribution, the architecture and the
  host kernel version.
- **What you did.** A minimal reproduction helps most.
- **What happened,** and how it differs from the expected behavior.

Issues here are public, so don't include credentials, keys, customer
data or anything else you wouldn't post publicly.
 
## Components
 
- [challoc](https://github.com/chainguard-project-theseus/challoc): a
  memory allocator written in Rust, built to replace glibc malloc,
  jemalloc, tcmalloc and mimalloc. Status: experimental.

## Pull requests
 
We aren't accepting pull requests.
 
## Trademarks
 
Use of the Chainguard and challoc names is governed by Chainguard's
trademark policy.
