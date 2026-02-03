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
[runnervmkj6or:06261] *** Process received signal ***
[runnervmkj6or:06261] Signal: Aborted (6)
[runnervmkj6or:06261] Signal code:  (-6)
[runnervmkj6or:06261] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc892e45330]
[runnervmkj6or:06261] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc892e9eb2c]
[runnervmkj6or:06261] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc892e4527e]
[runnervmkj6or:06261] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc892e288ff]
[runnervmkj6or:06261] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc8932a5ff5]
[runnervmkj6or:06261] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc8932bb0da]
[runnervmkj6or:06261] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc8932a5a55]
[runnervmkj6or:06261] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc8932a5a6f]
[runnervmkj6or:06261] [ 8] plumed_master(+0x146dd)[0x55ba470ba6dd]
[runnervmkj6or:06261] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc892e2a1ca]
[runnervmkj6or:06261] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc892e2a28b]
[runnervmkj6or:06261] [11] plumed_master(+0x15365)[0x55ba470bb365]
[runnervmkj6or:06261] *** End of error message ***
</pre>
{% endraw %}
