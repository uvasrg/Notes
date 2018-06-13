# SRG Notes

This repository is for notes that will be useful to SRG researchers. 

## How to set up the UVA CS department GPU servers for EvadeML-Zoo

Once you have a CS department account, you should be able to ssh into the GPU servers: `gpusrv01`, `gpusrv02`, `gpusrv03`. 


Run the following command to load the required modules:

```
module load python cudnn-7.0.5 cuda-toolkit-9.0
```

Then set up a `virtualenv`, and install the required dependencies of
EvadeML-Zoo (as instructed in the EvadeML-Zoo documentation).
