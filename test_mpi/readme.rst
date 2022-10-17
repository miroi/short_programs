MPI short test
==============

https://github.com/firemodels/fds/issues/10989#issuecomment-1281128188


milias@labs.fpv.umb.sk:~/work/programming/short_programs/test_mpi/.mpif90 --version
GNU Fortran (Debian 8.3.0-6) 8.3.0
Copyright (C) 2018 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

milias@labs.fpv.umb.sk:~/work/programming/short_programs/test_mpi/.mpif90 test_mpi.f90
milias@labs.fpv.umb.sk:~/work/programming/short_programs/test_mpi/.mpirun --version
mpirun (Open MPI) 3.1.3

Report bugs to http://www.open-mpi.org/community/help/
milias@labs.fpv.umb.sk:~/work/programming/short_programs/test_mpi/.mpirun -np 4 ./a.out
 Hello world: rank            0  of            4  running on labs.fpv.umb.sk                                                                                                                                                                                      
 Hello world: rank            1  of            4  running on labs.fpv.umb.sk                                                                                                                                                                                      
 Hello world: rank            2  of            4  running on labs.fpv.umb.sk                                                                                                                                                                                      
 Hello world: rank            3  of            4  running on labs.fpv.umb.sk                                                                                                                                                                                      
milias@labs.fpv.umb.sk:~/work/programming/short_programs/test_mpi/.

