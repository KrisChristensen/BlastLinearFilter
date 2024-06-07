# BlastLinearFilter
A script to remove alignments that are not linear or too short.  Used to keep long alignments from the output of a blast alignment.

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#requirements">Requirements</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>

<!-- requirements -->
## Requirements

The script requires the Linear_Alignments_v4 and GeneralOverlap_v1 scripts to be in the same folder.
A blast alignment output in outfmt 6.

<!-- usage -->
## Usage

Find linear alignments that pass certain filtering criteria:
python General_linear_filter_fmt6.v1.3.py -aln genome.masked.vs.self.aln -gap 100000 -min 10000 -print no 2> Gap100K.10K.txt

To see the usage and get futher information: python General_linear_filter_fmt6.v1.3.py -h

<!-- license -->
## License 

Distributed under the MIT License.
