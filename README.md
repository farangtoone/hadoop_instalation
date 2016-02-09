# hadoop custom scheduler

Hadoop's pluggable capacity scheduler was modified in order to implement a multi-level privacy model (Bell-LaPadula) for using Hadoop in hybrid cloud. The custom scheduler sends tasks only to trusted nodes in the cluster depending in authorization and clearance levels of different cloud and data involved.

The concept was proven on a cluster of 3 Virtual Box machines, only modified files are listed in this repo plus the bash file used to copy configuration in the cluster and starting a job.

