# UOUMiner

#Binary release v1.0.0 

https://github.com/UOUPROJECT/UOUMiner/blob/master/uouminer-1.0.0.rar


At present, we only provide the miner based on CUDA. In the pipe-algorithm repository, the source code of the pipe algo has already been published . We warmly welcome you to write miner based on OpenCL for UOU.

###sample parameters for command line for pool mining:


uouminer -a pipe -o stratum+tcp://eu.gos.cx:8334 -u wallet.rigName -p x -i 20

###also for solo mining:


uouminer -a pipe -o stratum+tcp://eu.gos.cx:8334 -u wallet.rigName -p m=solo -i 20

