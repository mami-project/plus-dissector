# A PLUS dissector for Wireshark.

This repository contains a PLUS dissector for Wireshark. A dissector
is a plugin that you can load in order to display the contents of
packets in a protocol-specific way.

## Installation

Copy `plus.lua` into any of Wireshark's plugin directories. I suggest you use your personal plugin directory. Find the list of plugin directories under Help > About Wireshark > Folders > Personal Plugins. Yes, I know, it's not very intuitive.

You will need a fairly recent version of Wireshark for this plugin to work.

## Operation

At this stage in its development, the PLUS dissector will look at packets that come in on Port 9999, even though you can use Analyze > Decode as... if another port is used. At this stage, the dissector does _not_ hand over the rest of the packet to any other dissectors.

## Acknowledgments

This dissector was written by Marcel Süess `sueesmar [at] students [dot] zhaw [dot] ch` as part of his Master's Thesis. All credit belongs to him.

This work has receiving funding from the European Union’s Horizon 2020 research and innovation programme under grant agreement No 688421 (MAMI).

## Copyright

Copyright &copy; 2017 Zürcher Hochschule der Angewandten Wissenschaften. All rights reserved. 

You can use and modify this software under the terms of the [Apache License, version 2.0 of January 2004](https://www.apache.org/licenses/LICENSE-2.0).
