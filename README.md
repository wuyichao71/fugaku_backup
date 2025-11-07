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

`~/data3/igf1r/prod/grest_loop/wt/prod/1/run*` has been moved to `run420`
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

`~/data3/igf1r/prod/grest_loop/wt/prod/2/run*` has been moved to `run300`
**under rsync**

`~/data3/igf1r/prod/grest_loop/wt/prod/2/run*/sortwater` has been rsynced to `run395`.
`run1` to `run300` have been moved (`~/data2/trash/grest_loop/wt/2/run*/sortwater`).
**under rsync**

## `~/data3/igf1r/prod/grest_loop/dm/prod/1`

`~/data3/igf1r/prod/grest_loop/dm/prod/1/run*` has been moved to `run300`
**under rsync**

`~/data3/igf1r/prod/grest_loop/dm/prod/1/run*/sortwater` has been rsynced to `run401`.
`run1` to `run300` have been moved (`~/data2/trash/grest_loop/dm/1/run*/sortwater`).
**under rsync**

## `~/data3/igf1r/prod/grest_loop/dm/prod/2`

`~/data3/igf1r/prod/grest_loop/dm/prod/2/run*` has been moved to `run300`
**under rsync**
