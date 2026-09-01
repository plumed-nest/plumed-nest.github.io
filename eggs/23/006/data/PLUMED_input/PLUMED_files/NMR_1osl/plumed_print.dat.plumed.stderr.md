**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  PLUMED_input/PLUMED_files/NMR_1osl/plumed_print.dat   
Download: [zipped raw stdout](plumed_print.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_print.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1osl_C52V_GMX_new_numbering.pdb
[runnervmgx7h7:06714] *** Process received signal ***
[runnervmgx7h7:06714] Signal: Aborted (6)
[runnervmgx7h7:06714] Signal code:  (-6)
[runnervmgx7h7:06714] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbe3d445330]
[runnervmgx7h7:06714] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbe3d49ec0c]
[runnervmgx7h7:06714] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbe3d44527e]
[runnervmgx7h7:06714] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbe3d4288ff]
[runnervmgx7h7:06714] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbe3d8a5ff5]
[runnervmgx7h7:06714] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbe3d8bb0da]
[runnervmgx7h7:06714] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbe3d8a5a55]
[runnervmgx7h7:06714] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbe3d8a5a6f]
[runnervmgx7h7:06714] [ 8] plumed(+0x146dd)[0x557cd869e6dd]
[runnervmgx7h7:06714] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbe3d42a1ca]
[runnervmgx7h7:06714] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbe3d42a28b]
[runnervmgx7h7:06714] [11] plumed(+0x15365)[0x557cd869f365]
[runnervmgx7h7:06714] *** End of error message ***
</pre>
{% endraw %}
