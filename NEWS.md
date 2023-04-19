# ctseq v0.0.4

## Major changes

* Now filters out any UMI with any "N" value found within the sequence.

## Backwards compatible changes

* Able to remove UMI with mostly "G" values. Can specify the minimum number of non-g values that must be in the UMI using parameter "minNonG". Default is 0 which defaults to no removal of UMI. Recommendation is minNonG=2.

# ctseq v0.0.3

As initially forked.