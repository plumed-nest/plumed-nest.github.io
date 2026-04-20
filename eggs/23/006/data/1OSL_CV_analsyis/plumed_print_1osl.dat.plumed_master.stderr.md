**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  1OSL_CV_analsyis/plumed_print_1osl.dat   
Download: [zipped raw stdout](plumed_print_1osl.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_print_1osl.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1efa_NOD_S99_mod_ID.pdb
[runnervmeorf1:05795] *** Process received signal ***
[runnervmeorf1:05795] Signal: Aborted (6)
[runnervmeorf1:05795] Signal code:  (-6)
[runnervmeorf1:05795] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f65c4e45330]
[runnervmeorf1:05795] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f65c4e9eb2c]
[runnervmeorf1:05795] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f65c4e4527e]
[runnervmeorf1:05795] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f65c4e288ff]
[runnervmeorf1:05795] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f65c52a5ff5]
[runnervmeorf1:05795] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f65c52bb0da]
[runnervmeorf1:05795] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f65c52a5a55]
[runnervmeorf1:05795] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f65c52a5a6f]
[runnervmeorf1:05795] [ 8] plumed_master(+0x146dd)[0x55a7485686dd]
[runnervmeorf1:05795] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f65c4e2a1ca]
[runnervmeorf1:05795] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f65c4e2a28b]
[runnervmeorf1:05795] [11] plumed_master(+0x15365)[0x55a748569365]
[runnervmeorf1:05795] *** End of error message ***
</pre>
{% endraw %}
