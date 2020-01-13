# AutoFIO
To run FIO jobfile,
1- Create fio jobfile
2- Create fio user on all loadgens or use default user
3- Add all the loadgen IP Addresses, fio username on loadgen and keypath in jobrun_fio2.py script
4- Run jobrun_fio2.py script 
   $ jobrun_fio2.py  <jobfile-path> <Result-Dir> 
5- To aggregate results, run cbt_fio_results_aggr_script.py scriptname 
   $ cbt_fio_results_aggr_script.py <Result-Dir> 