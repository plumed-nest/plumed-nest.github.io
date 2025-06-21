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
[pkrvmxyh4eaekms:07215] *** Process received signal ***
[pkrvmxyh4eaekms:07215] Signal: Aborted (6)
[pkrvmxyh4eaekms:07215] Signal code:  (-6)
[pkrvmxyh4eaekms:07215] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbc04c45330]
[pkrvmxyh4eaekms:07215] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbc04c9eb2c]
[pkrvmxyh4eaekms:07215] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbc04c4527e]
[pkrvmxyh4eaekms:07215] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbc04c288ff]
[pkrvmxyh4eaekms:07215] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbc050a5ff5]
[pkrvmxyh4eaekms:07215] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbc050bb0da]
[pkrvmxyh4eaekms:07215] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbc050a5a55]
[pkrvmxyh4eaekms:07215] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbc050a5a6f]
[pkrvmxyh4eaekms:07215] [ 8] plumed_master(+0x146dd)[0x5623393116dd]
[pkrvmxyh4eaekms:07215] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbc04c2a1ca]
[pkrvmxyh4eaekms:07215] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbc04c2a28b]
[pkrvmxyh4eaekms:07215] [11] plumed_master(+0x15365)[0x562339312365]
[pkrvmxyh4eaekms:07215] *** End of error message ***
</pre>
{% endraw %}
