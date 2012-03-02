## D Scripts - A collection of dTrace scripts
Most are (and will continue to be) storage and adaptations of [Brendan Gregg's](http://www.brendangregg.com/) work from the [DTraceToolkit](http://hub.opensolaris.org/bin/view/Community+Group+dtrace/dtracetoolkit).

#### fsFlush
File system flush activity (Solaris Internals).

#### latencyByHandler_generic
Probe latency by handler (for all handlers). Uses standard Restify.js (*-start & *-end) probe name conventions for quickly returning a "top" of latency within an API.