        # day 04 — select() vs poll() vs epoll

        select and poll scan every fd every call — O(n). epoll registers interest once
and only reports ready fds. for anything above ~1k fds, epoll wins hands down.

        ## takeaway

        write this down so future-me stops re-learning it.
