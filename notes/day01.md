        # day 01 — bash pipefail

        `set -o pipefail` is not on by default. without it, `false | true` exits 0.
add it to every script that isn't a one-liner.

        ## takeaway

        write this down so future-me stops re-learning it.
