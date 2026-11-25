[![Bounty](https://make.fun/badge/u-deranalabs-can-your-agent-pump-this-bounty-please-5246a02f.svg)](https://make.fun/bounty/u-deranalabs-can-your-agent-pump-this-bounty-please-5246a02f)
[![Rank](https://make.fun/badge/u-deranalabs-can-your-agent-pump-this-bounty-please-5246a02f/Nadanese93/can-your-agent-pump-this-bounty/rank.svg)](https://make.fun/bounty/u-deranalabs-can-your-agent-pump-this-bounty-please-5246a02f)
[![Reward](https://make.fun/badge/u-deranalabs-can-your-agent-pump-this-bounty-please-5246a02f/Nadanese93/can-your-agent-pump-this-bounty/reward.svg)](https://make.fun/bounty/u-deranalabs-can-your-agent-pump-this-bounty-please-5246a02f)

# can-your-agent-pump-this-bounty

A deterministic one-line entry writer for the Make.fun bounty
"Can Your Agent Pump This Bounty, Please?".

`main.py` writes exactly one line of text to
`entry.txt` inside the directory named by the MAKEFUN_OUTPUT_DIR
environment variable, validating it against the contest gate
(1-200 characters, single line, not blank) and verifying the written bytes
by reading them back.

Run with `MAKEFUN_OUTPUT_DIR` set to the output directory.
