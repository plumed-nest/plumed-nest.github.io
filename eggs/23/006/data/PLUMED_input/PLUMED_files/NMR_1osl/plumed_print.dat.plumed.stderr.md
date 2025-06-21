**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  PLUMED_input/PLUMED_files/NMR_1osl/plumed_print.dat   
Download: [zipped raw stdout](plumed_print.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_print.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1osl_C52V_GMX_new_numbering.pdb
[pkrvmxyh4eaekms:07200] *** Process received signal ***
[pkrvmxyh4eaekms:07200] Signal: Aborted (6)
[pkrvmxyh4eaekms:07200] Signal code:  (-6)
[pkrvmxyh4eaekms:07200] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f64a1e45330]
[pkrvmxyh4eaekms:07200] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f64a1e9eb2c]
[pkrvmxyh4eaekms:07200] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f64a1e4527e]
[pkrvmxyh4eaekms:07200] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f64a1e288ff]
[pkrvmxyh4eaekms:07200] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f64a22a5ff5]
[pkrvmxyh4eaekms:07200] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f64a22bb0da]
[pkrvmxyh4eaekms:07200] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f64a22a5a55]
[pkrvmxyh4eaekms:07200] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f64a22a5a6f]
[pkrvmxyh4eaekms:07200] [ 8] plumed(+0x146dd)[0x5594025bf6dd]
[pkrvmxyh4eaekms:07200] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f64a1e2a1ca]
[pkrvmxyh4eaekms:07200] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f64a1e2a28b]
[pkrvmxyh4eaekms:07200] [11] plumed(+0x15365)[0x5594025c0365]
[pkrvmxyh4eaekms:07200] *** End of error message ***
</pre>
{% endraw %}
