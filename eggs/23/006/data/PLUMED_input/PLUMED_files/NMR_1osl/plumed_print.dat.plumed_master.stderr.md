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
[runnervmmklqx:05796] *** Process received signal ***
[runnervmmklqx:05796] Signal: Aborted (6)
[runnervmmklqx:05796] Signal code:  (-6)
[runnervmmklqx:05796] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3eb1645330]
[runnervmmklqx:05796] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3eb169eb2c]
[runnervmmklqx:05796] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3eb164527e]
[runnervmmklqx:05796] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3eb16288ff]
[runnervmmklqx:05796] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3eb1aa5ff5]
[runnervmmklqx:05796] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3eb1abb0da]
[runnervmmklqx:05796] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3eb1aa5a55]
[runnervmmklqx:05796] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3eb1aa5a6f]
[runnervmmklqx:05796] [ 8] plumed_master(+0x146dd)[0x562d91e0f6dd]
[runnervmmklqx:05796] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3eb162a1ca]
[runnervmmklqx:05796] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3eb162a28b]
[runnervmmklqx:05796] [11] plumed_master(+0x15365)[0x562d91e10365]
[runnervmmklqx:05796] *** End of error message ***
</pre>
{% endraw %}
