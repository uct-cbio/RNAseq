If you are using this pipeline on UCT's HPC cluster, please note the following:

Settings specific to the HPC environment are specified in https://github.com/uct-cbio/RNAseq-pipeline/blob/uct-dev/conf/hpc.config
Most of these should be fine for you as is but you will need to specify your own group membership as a command line flag e.g. `--hpc_account cbio` or `--hpc_account biosci`
If you don't know what your account (group membership) is do:
`sacctmgr show associations where user=yourUserName` on HPC
