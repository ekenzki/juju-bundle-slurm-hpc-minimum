# Slurm HPC Minimum
This bundle provisions the minimum components
of a Slurm HPC job scheduling system.

### Usage
```
$ juju deploy cs:~omnivector/bundle/slurm-hpc-min-<version>
```

Once the bundle has been deployed you can login to the controller node and do srun as normal for testing that it works.
```
$ srun -p partition1 -N 1 hostname
```

### Contact
* [Omnivector Solutions](http://omnivector.solutions)

### Copyright
* AGPLv3 (see `copyright` file)
