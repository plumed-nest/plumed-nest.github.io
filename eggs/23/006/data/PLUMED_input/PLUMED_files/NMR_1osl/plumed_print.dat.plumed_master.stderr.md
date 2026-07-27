**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  PLUMED_input/PLUMED_files/NMR_1osl/plumed_print.dat   
Download: [zipped raw stdout](plumed_print.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_print.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1osl_C52V_GMX_new_numbering.pdb
[runnervmvrwv9:06831] *** Process received signal ***
[runnervmvrwv9:06831] Signal: Aborted (6)
[runnervmvrwv9:06831] Signal code:  (-6)
[runnervmvrwv9:06831] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe7db445330]
[runnervmvrwv9:06831] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe7db49eb2c]
[runnervmvrwv9:06831] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe7db44527e]
[runnervmvrwv9:06831] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe7db4288ff]
[runnervmvrwv9:06831] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe7db8a5ff5]
[runnervmvrwv9:06831] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe7db8bb0da]
[runnervmvrwv9:06831] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe7db8a5a55]
[runnervmvrwv9:06831] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe7db8a5a6f]
[runnervmvrwv9:06831] [ 8] plumed_master(+0x146dd)[0x55b6cab5b6dd]
[runnervmvrwv9:06831] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe7db42a1ca]
[runnervmvrwv9:06831] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe7db42a28b]
[runnervmvrwv9:06831] [11] plumed_master(+0x15365)[0x55b6cab5c365]
[runnervmvrwv9:06831] *** End of error message ***
</pre>
{% endraw %}
