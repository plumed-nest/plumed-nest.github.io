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
[runnervmi13qx:33548] *** Process received signal ***
[runnervmi13qx:33548] Signal: Aborted (6)
[runnervmi13qx:33548] Signal code:  (-6)
[runnervmi13qx:33548] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff755045330]
[runnervmi13qx:33548] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff75509eb2c]
[runnervmi13qx:33548] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff75504527e]
[runnervmi13qx:33548] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff7550288ff]
[runnervmi13qx:33548] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff7554a5ff5]
[runnervmi13qx:33548] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff7554bb0da]
[runnervmi13qx:33548] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff7554a5a55]
[runnervmi13qx:33548] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff7554a5a6f]
[runnervmi13qx:33548] [ 8] plumed_master(+0x146dd)[0x5642c9b7e6dd]
[runnervmi13qx:33548] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff75502a1ca]
[runnervmi13qx:33548] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff75502a28b]
[runnervmi13qx:33548] [11] plumed_master(+0x15365)[0x5642c9b7f365]
[runnervmi13qx:33548] *** End of error message ***
</pre>
{% endraw %}
