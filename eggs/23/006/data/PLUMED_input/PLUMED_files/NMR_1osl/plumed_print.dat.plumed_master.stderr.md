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
[runnervmw9dnm:08654] *** Process received signal ***
[runnervmw9dnm:08654] Signal: Aborted (6)
[runnervmw9dnm:08654] Signal code:  (-6)
[runnervmw9dnm:08654] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7139e45330]
[runnervmw9dnm:08654] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7139e9eb2c]
[runnervmw9dnm:08654] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7139e4527e]
[runnervmw9dnm:08654] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7139e288ff]
[runnervmw9dnm:08654] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f713a2a5ff5]
[runnervmw9dnm:08654] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f713a2bb0da]
[runnervmw9dnm:08654] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f713a2a5a55]
[runnervmw9dnm:08654] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f713a2a5a6f]
[runnervmw9dnm:08654] [ 8] plumed_master(+0x146dd)[0x55d28ae986dd]
[runnervmw9dnm:08654] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7139e2a1ca]
[runnervmw9dnm:08654] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7139e2a28b]
[runnervmw9dnm:08654] [11] plumed_master(+0x15365)[0x55d28ae99365]
[runnervmw9dnm:08654] *** End of error message ***
</pre>
{% endraw %}
