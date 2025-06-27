**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  PLUMED_input/PLUMED_files/NMR_1osl/plumed_print.dat   
Download: [zipped raw stdout](plumed_print.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_print.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1osl_C52V_GMX_new_numbering.pdb
[pkrvmbietmlfzoi:64068] *** Process received signal ***
[pkrvmbietmlfzoi:64068] Signal: Aborted (6)
[pkrvmbietmlfzoi:64068] Signal code:  (-6)
[pkrvmbietmlfzoi:64068] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb803845330]
[pkrvmbietmlfzoi:64068] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb80389eb2c]
[pkrvmbietmlfzoi:64068] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb80384527e]
[pkrvmbietmlfzoi:64068] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb8038288ff]
[pkrvmbietmlfzoi:64068] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb803ca5ff5]
[pkrvmbietmlfzoi:64068] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb803cbb0da]
[pkrvmbietmlfzoi:64068] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb803ca5a55]
[pkrvmbietmlfzoi:64068] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb803ca5a6f]
[pkrvmbietmlfzoi:64068] [ 8] plumed_master(+0x146dd)[0x55bfcd0226dd]
[pkrvmbietmlfzoi:64068] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb80382a1ca]
[pkrvmbietmlfzoi:64068] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb80382a28b]
[pkrvmbietmlfzoi:64068] [11] plumed_master(+0x15365)[0x55bfcd023365]
[pkrvmbietmlfzoi:64068] *** End of error message ***
</pre>
{% endraw %}
