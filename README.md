# remove record

# `~/data`

It is linked to `/vol0402/data/hp150272/u12262/`

## `~/data/abltide`

### `~/data/abltide/old-data`

The directory is a sub-backup of `/vol0004/hp150272/data/u10374/abl-abltide`  
We backup the `.inp`, `.sh` for the last round of `3_rounds` (`/vol0004/hp150272/data/u10374/abl-abltide/tune-2d/atpcomplex-*rep/3_rounds/`)  
For rerun, we also backup the previous `.rst` (`/vol0004/hp150272/data/u12262/abltide/old-data/abl-abltide/tune-2d/atpcomplex-*rep/2_tune/*.rst`) and `files` (`/vol0004/hp150272/data/u12262/abltide/old-data/abl-abltide/files`)

`abl-abltide/tune-2d/atpcomplex-240rep/3_rounds/240rep` is linked to `/vol0402/data/hp150272/u10374/abl-abltide/tune-2d/atpcomplex-240rep/3_rounds/31_round31`  
Total `73G`  
It is the round of 2D gREST/REUS (adjust the parameter slightly).  
It used an insufficiently large water layer (`atp-complex-solv.prmtop`, not 35)  
We backup `reus-tune-atpcomplex-240rep-tune31.inp`, `reus-tune-atpcomplex-240rep-tune31.sh`, `output.29520396`.  
I do not have permission for `output.29520396`  
**finished**

`abl-abltide/tune-2d/atpcomplex-288rep/3_rounds/288rep` is linked to `/vol0402/data/hp150272/u10374/abl-abltide/tune-2d/atpcomplex-288rep/3_rounds/34_round34`  
Total `307G`  
It is the round of 2D gREST/REUS (adjust the parameter slightly).  
It used a 35 water layer (`atp-complex-solv35.prmtop`)  
We backup `reus-tune-atpcomplex-288rep-tune34.inp`, `reus-tune-atpcomplex-288rep-tune34.sh`, `output.29601559`.  
I do not have permission for `output.29601559`  
**finished**

`abl-abltide/tune-2d/atpcomplex-336rep/3_rounds/336rep` is linked to `/vol0402/data/hp150272/u10374/abl-abltide/tune-2d/atpcomplex-336rep/3_rounds/40_round40`  
Total `358G`  
It is the round of 2D gREST/REUS (adjust the parameter slightly).  
It used a 35 water layer (`atp-complex-solv35.prmtop`)  
We backup `reus-tune-atpcomplex-336rep-tune40.inp`, `reus-tune-atpcomplex-336rep-tune40.sh`, `output.29726777`.  
I do not have permission for `output.29726777`  
**finished**

`abl-abltide/tune-2d/atpcomplex-384rep/3_rounds/384rep` is linked to `/vol0402/data/hp150272/u10374/abl-abltide/tune-2d/atpcomplex-384rep/3_rounds/33_round33`  
Total `409G`  
It is the round of 2D gREST/REUS (adjust the parameter slightly).  
It used a 35 water layer (`atp-complex-solv35.prmtop`)  
We backup `reus-tune-atpcomplex-384rep-tune33.inp`, `reus-tune-atpcomplex-384rep-tune33.sh`, `output.29690389`.  
I do not have permission for `output.29690389`  
**finished**

`~/data/abltide/old-data` backup in `~/Documents/abltide/old-data` and `/work/wuyichao/work/abltide/old-data`.

### `~/data/abltide/abl-abltide`

This is a link of `/vol0004/hp150272/data/u10374/abl-abltide`  
Just for convenience, do not need backup

### `~/data/abltide/old-analy-data`

This is a link of `/vol0004/hp150272/data/u10374/share/abl-abltide-test`  
This is data shared by others.  
`analysis`: I do not have permission, do not backup.  
`files`: `atp-complex-prot.inpcrd`, `atp-complex-prot.pdb`, `atp-complex-prot.prmtop` copied to `~/data/abltide/old-data/abl-abltide/files`, do not backup  
We just link it to `~/data/abltide/old-data/abl-abltide/files/*`  
`grest`: `grest/1-prod` seems the runned of `/vol0004/hp150272/data/u10374/abl-abltide/tune-grest/atpcmoplex-solv35/round6_final`.  
we backup those files.

```bash
grest/1-prod/grest_prod.inp
grest/1-prod/grest_prod.sh
grest/1-prod/grest_prod.out
grest/1-prod/conv/grest_conv.inp
grest/1-prod/conv/grest_conv.sh
grest/1-prod/sort/grest_sort.inp
grest/1-prod/sort/grest_sort.sh
grest/1-prod/sorthyd/grest_sorthyd.inp
grest/1-prod/sorthyd/grest_sorthyd.sh
```

`grest-reus`: `reus/1-grest-reus`, the rstfile backup in `~/data/abltide/old-data/abl-abltide/tune-2d/atpcomplex-240rep/2_tune/reus-tune-atpcomplex-240rep-tune-rep*.rst`.  
we backup those files.

```bash
grest-reus/1-grest-reus/grest_reus_prod.inp
grest-reus/1-grest-reus/grest_reus_prod.sh
grest-reus/1-grest-reus/output.29136526/0/1/stdout.1.0
grest-reus/1-grest-reus/conv/grest_reus_conv.inp
grest-reus/1-grest-reus/conv/grest_reus_conv.sh
grest-reus/1-grest-reus/sort/grest_reus_sort.inp
grest-reus/1-grest-reus/sort/grest_reus_sort.sh
grest-reus/1-grest-reus/sorthyd/grest_reus_sorthyd.inp
grest-reus/1-grest-reus/sorthyd/grest_reus_sorthyd.sh
```

`reus`: `reus/1-reus`, the rstfile backup in `~/data/abltide/old-data/abl-abltide/tune-reus/atpcomplex-30rep/2_tune/reus-tune-atpcomplex-solv14-30rep-tune-rep*.rst`  
we backup those files.

```bash
reus/1-reus/reus_prod.inp
reus/1-reus/reus_prod.sh
reus/1-reus/output.29136543/0/1/stdout.1.0
reus/1-reus/conv/reus_conv.inp
reus/1-reus/conv/reus_conv.sh
reus/1-reus/sort/reus_sort.inp
reus/1-reus/sort/reus_sort.sh
reus/1-reus/sorthyd/reus_sorthyd.inp
reus/1-reus/sorthyd/reus_sorthyd.sh
```

**finished**

### `~/data/abltide/old-analy`

The `.dcd`, `.log`, `.pdb` are remove from this directory.  
Only backup input and script.  
In `cell` local, there are some analysis script.  
We remove the trajectories and save the analyzed data.

**finished**

### `~/data/abltide/production`

#### `~/data/abltide/production/analy`

##### `~/data/abltide/production/analy/288rep`

`0.1_correct_run172` is backup and checked all the script. **finished**
`0.2_rerun` is backup and checked all the script. **finished**
`0_standard` is backup and checked all the script. **finished**
`1_comdist` is backup and checked all the script. **finished**
`3_contact_number` is bakcup and checked all the scripts. **finished**
`5_sort_comdist` is backup and checked all the scripts. **finished**
`11_qval` is backup and checked all the script. **finished**
`12_rmsd` is backup and checked all the script. **finished**
`16_mbar_reus` is backup and checked all the script. **finished**
`17_plot_reweight` is backup and checked all the script. **finished**
`18_comdist_check` is backup and checked all the script. **finished**
`19_kmeans_check` is backup and checked all the script. **finished**
`20_kmeans` 

##### `~/data/abltide/production/analy/336rep`

`0.1_correct_run139`
`0.2_rerun`
`0_standard`
`1_comdist`
`5_sort_comdist`
`11_qval`
`12_rmsd`
`16_mbar_reus`
`17_plot_reweight`
`18_comdist_check`

##### `~/data/abltide/production/analy/atpcomplex-cmd`

##### `~/data/abltide/production/analy/atpcomplex-cmd-unbound`

<!-- ========================================= -->

# abltide

## `atpcomplex-cmd`

`atpcomplex-cmd` is in `~/data/abltide/production/atpcomplex-cmd`
It preforms cMD from the binding states of abltide.

## `atpcomplex-cmd-unbound`

`atpcomplex-cmd-unbound` is in `~/data/abltide/production/atpcomplex-cmd-unbound`
It preforms cMD from the unbinding states of abltide.

## `atpcomplex-288rep`

`atpcomplex-288rep` is linked from `../../../u10374/abl-abltide/production/atpcomplex-288rep/`
It used 288 replicas to perform gREST/REUS simulation.
Some parts have been saved to `cell`
The `run172` is broken.
For this part, we need to handle it carefully

## `atpcomplex-336rep`

`atpcomplex-336rep` is linked from `/vol0402/data/hp150272/u10374/abl-abltide/production/atpcomplex-336rep/`
It used 336 replicas to perform gREST/REUS simulation.
Some parts have been saved to `cell`
The `run139` is broken.
For this part, we need to handle it carefully
**under rsync**

# igf1r

## `~/data3/igf1r/prod/grest_loop/wt/prod/1`

`~/data3/igf1r/prod/grest_loop/wt/prod/1/run*` has been moved to `run500`
**under rsync**

`~/data3/igf1r/prod/grest_loop/wt/prod/1/run*/sortwater` has been rsynced to `run500`.
`run1` to `run500` have been moved (`~/data2/trash/grest_loop/wt/1/run*/sortwater/grest*_sortwater.pdb`).
`run1` to `run500` have been moved (`~/data2/trash/grest_loop/wt/1/run*/sortwater/grest*_sortwater_rep1.dcd`).
`run1` to `run500` have been moved (`~/data2/trash/grest_loop/wt/1/run*/sortwater/grest*_sortwater_rep1.log`).

`~/data3/igf1r/prod/grest_loop/wt/prod/1/run*/conv` has been rsynced to `run500`.
`run1` to `run500` have been moved (`~/data2/trash/grest_loop/wt/1/run*/conv`).
`run1` to `run500` have been moved (`~/data2/trash/grest_loop/wt/1/run*/sort/grest*_sort.pdb`).
`run1` to `run500` have been moved (`~/data2/trash/grest_loop/wt/1/run*/sort/grest*_sort_rep*.dcd`).
`run1` to `run500` have been moved (`~/data2/trash/grest_loop/wt/1/run*/sort/grest*_sort_rep*.log`).
`run1` to `run500` have been moved (`~/data2/trash/grest_loop/wt/1/run*/sort/grest*_sort_rep*.ene`).

`~/data3/igf1r/prod/grest_loop/wt/prod/1/run*/sort` has been rsynced to `run500`.
`run1` to `run500` have been moved (`~/data2/trash/grest_loop/wt/1/run*/sort`).
`run1` to `run500` have been moved (`~/data2/trash/grest_loop/wt/1/run*/sort/grest*_sort.pdb`).
`run1` to `run500` have been moved (`~/data2/trash/grest_loop/wt/1/run*/sort/grest*_sort_rep*.dcd`).
`run1` to `run500` have been moved (`~/data2/trash/grest_loop/wt/1/run*/sort/grest*_sort_rep*.log`).
`run1` to `run500` have been moved (`~/data2/trash/grest_loop/wt/1/run*/sort/grest*_sort_rep*.ene`).

## `~/data3/igf1r/prod/grest_loop/wt/prod/2`

`~/data3/igf1r/prod/grest_loop/wt/prod/2/run*` has been moved to `run500`
**under rsync**

`~/data3/igf1r/prod/grest_loop/wt/prod/2/run*/sortwater` has been rsynced to `run500`.
`run1` to `run500` have been moved (`~/data2/trash/grest_loop/wt/2/run*/sortwater/grest*_sortwater.pdb`).
`run1` to `run500` have been moved (`~/data2/trash/grest_loop/wt/2/run*/sortwater/grest*_sortwater_rep1.dcd`).
`run1` to `run500` have been moved (`~/data2/trash/grest_loop/wt/2/run*/sortwater/grest*_sortwater_rep1.log`).

`~/data3/igf1r/prod/grest_loop/wt/prod/2/run*/conv` has been rsynced to `run500`.
`run1` to `run500` have been moved (`~/data2/trash/grest_loop/wt/2/run*/conv`).
`run1` to `run500` have been moved (`~/data2/trash/grest_loop/wt/2/run*/sort/grest*_sort.pdb`).
`run1` to `run500` have been moved (`~/data2/trash/grest_loop/wt/2/run*/sort/grest*_sort_rep*.dcd`).
`run1` to `run500` have been moved (`~/data2/trash/grest_loop/wt/2/run*/sort/grest*_sort_rep*.log`).
`run1` to `run500` have been moved (`~/data2/trash/grest_loop/wt/2/run*/sort/grest*_sort_rep*.ene`).

`~/data3/igf1r/prod/grest_loop/wt/prod/1/run*/sort` has been rsynced to `run500`.
`run1` to `run500` have been moved (`~/data2/trash/grest_loop/wt/2/run*/sort`).
`run1` to `run500` have been moved (`~/data2/trash/grest_loop/wt/2/run*/sort/grest*_sort.pdb`).
`run1` to `run500` have been moved (`~/data2/trash/grest_loop/wt/2/run*/sort/grest*_sort_rep*.dcd`).
`run1` to `run500` have been moved (`~/data2/trash/grest_loop/wt/2/run*/sort/grest*_sort_rep*.log`).
`run1` to `run500` have been moved (`~/data2/trash/grest_loop/wt/2/run*/sort/grest*_sort_rep*.ene`).

## `~/data3/igf1r/prod/grest_loop/dm/prod/1`

`~/data3/igf1r/prod/grest_loop/dm/prod/1/run*` has been moved to `run500`
**under rsync**

`~/data3/igf1r/prod/grest_loop/dm/prod/1/run*/sortwater` has been rsynced to `run500`.
`run1` to `run500` have been moved (`~/data2/trash/grest_loop/dm/1/run*/sortwater/grest*_sortwater.pdb`).
`run1` to `run500` have been moved (`~/data2/trash/grest_loop/dm/1/run*/sortwater/grest*_sortwater_rep1.dcd`).
`run1` to `run500` have been moved (`~/data2/trash/grest_loop/dm/1/run*/sortwater/grest*_sortwater_rep1.log`).

`~/data3/igf1r/prod/grest_loop/dm/prod/1/run*/conv` has been rsynced to `run500`.
`run1` to `run500` have been moved (`~/data2/trash/grest_loop/dm/1/run*/conv`).
`run1` to `run500` have been moved (`~/data2/trash/grest_loop/dm/1/run*/sort/grest*_sort.pdb`).
`run1` to `run500` have been moved (`~/data2/trash/grest_loop/dm/1/run*/sort/grest*_sort_rep*.dcd`).
`run1` to `run500` have been moved (`~/data2/trash/grest_loop/dm/1/run*/sort/grest*_sort_rep*.log`).
`run1` to `run500` have been moved (`~/data2/trash/grest_loop/dm/1/run*/sort/grest*_sort_rep*.ene`).

## `~/data3/igf1r/prod/grest_loop/dm/prod/2`

`~/data3/igf1r/prod/grest_loop/dm/prod/2/run*` has been moved to `run500`
**under rsync**
