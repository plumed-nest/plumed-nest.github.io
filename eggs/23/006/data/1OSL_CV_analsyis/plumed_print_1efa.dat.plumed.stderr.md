**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  1OSL_CV_analsyis/plumed_print_1efa.dat   
Download: [zipped raw stdout](plumed_print_1efa.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_print_1efa.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1efa_noTet_99sbws_proc_mod_resID.pdb
[runnervmeorf1:05727] *** Process received signal ***
[runnervmeorf1:05727] Signal: Aborted (6)
[runnervmeorf1:05727] Signal code:  (-6)
[runnervmeorf1:05727] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9de8845330]
[runnervmeorf1:05727] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9de889eb2c]
[runnervmeorf1:05727] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9de884527e]
[runnervmeorf1:05727] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9de88288ff]
[runnervmeorf1:05727] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9de8ca5ff5]
[runnervmeorf1:05727] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9de8cbb0da]
[runnervmeorf1:05727] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9de8ca5a55]
[runnervmeorf1:05727] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9de8ca5a6f]
[runnervmeorf1:05727] [ 8] plumed(+0x146dd)[0x562a346b96dd]
[runnervmeorf1:05727] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9de882a1ca]
[runnervmeorf1:05727] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9de882a28b]
[runnervmeorf1:05727] [11] plumed(+0x15365)[0x562a346ba365]
[runnervmeorf1:05727] *** End of error message ***
</pre>
{% endraw %}
