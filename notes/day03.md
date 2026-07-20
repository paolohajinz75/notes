        # day 03 — go slices are weird

        append can share underlying array or reallocate — depends on capacity. if you
keep a reference to the original slice, writes may or may not be visible.

        ## takeaway

        write this down so future-me stops re-learning it.
