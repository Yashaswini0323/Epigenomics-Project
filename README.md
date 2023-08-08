# Epigenomics-Project

@@ -1,4 +1,9 @@
```sh 
## To log into compute node
srun -p normal --time 1-00 --mem=8G --ntasks=8 --pty bash -i
# Once you're logged into a node
compute $ exit

## Load anaconda3
ml load anaconda3

## To log out of compute node
exit