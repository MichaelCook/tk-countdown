tk-countdown
============

Display a continually-updating countdown to a specified time.

Usage: tk-countdown [options] WHEN...

WHEN can be specified multiple times in any form accepted by date(1)

Examples: '5am tomorrow'
          '5 hours' (i.e., from now)

Options:
    --action (-a) command   What to do when the time expires.
                            The command is eval'ed as a Tcl expression.
                            Examples:
                                --action 'exit 1'
                            Default: --action bell
