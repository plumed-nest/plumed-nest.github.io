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
[runnervmi13qx:33426] *** Process received signal ***
[runnervmi13qx:33426] Signal: Aborted (6)
[runnervmi13qx:33426] Signal code:  (-6)
[runnervmi13qx:33426] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5c8e245330]
[runnervmi13qx:33426] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5c8e29eb2c]
[runnervmi13qx:33426] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5c8e24527e]
[runnervmi13qx:33426] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5c8e2288ff]
[runnervmi13qx:33426] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5c8e6a5ff5]
[runnervmi13qx:33426] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5c8e6bb0da]
[runnervmi13qx:33426] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5c8e6a5a55]
[runnervmi13qx:33426] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5c8e6a5a6f]
[runnervmi13qx:33426] [ 8] plumed(+0x146dd)[0x55882f2046dd]
[runnervmi13qx:33426] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5c8e22a1ca]
[runnervmi13qx:33426] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5c8e22a28b]
[runnervmi13qx:33426] [11] plumed(+0x15365)[0x55882f205365]
[runnervmi13qx:33426] *** End of error message ***
</pre>
{% endraw %}
