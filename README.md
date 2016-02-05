[![Build Status][travis-badge]][travis-link]
[![Wharf][wharf-badge]][wharf-link]

# Git-status

Add the following functions to retrieve Git status information from the current repository.

* `git_is_repo`
* `git_is_dirty`
* `git_is_staged`
* `git_is_touched`
* `git_is_stashed`

## Install

With [Fisherman][fisherman]

```
fisher install git-status
```

With [Fundle][fundle], add

```
fundle plugin "fishery/git-status"
```

to your shell config, reload your shell and run `fundle install`.

<!-- Badges -->

[travis-link]:  https://travis-ci.org/fishery/git-status
[travis-badge]: https://img.shields.io/travis/fishery/git-status.svg?style=flat-square

[wharf-link]:   https://fisherman-wharf.herokuapp.com/
[wharf-badge]:  https://img.shields.io/badge/slack-join%20the%20chat-00cc99.svg?style=flat-square

<!-- Install -->

[fundle]:       https://github.com/tuvistavie/fundle
[fisherman]:    https://github.com/fisherman/fisherman
