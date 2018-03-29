# MPTCP One-Way Delay Estimations

This repository contains a patch to illustrate one-way delay-estimations for MPTCP developed for the [programmable Multiapth TCP scheduler ProgMP](https://progmp.net).

This patch illustrates the collection of the one-way delay-estimations. This metric might be used, e.g., in the scheduler as alternative for the round-trip time estimation. More information and measurements are available in our [ICC 2018 paper](https://progmp.net/thinStreams.html).

Visit [am I using MPTCP](http://amiusingmptcp.de) to see one-way delay-estimates for your current MPTCP connection.

The current patch is for [MPTCP version 0.94](https://github.com/multipath-tcp/mptcp/tree/mptcp_v0.94).