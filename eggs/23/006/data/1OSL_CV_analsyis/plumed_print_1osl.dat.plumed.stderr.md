**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  1OSL_CV_analsyis/plumed_print_1osl.dat   
Download: [zipped raw stdout](plumed_print_1osl.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_print_1osl.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1efa_NOD_S99_mod_ID.pdb
[runnervmmklqx:05729] *** Process received signal ***
[runnervmmklqx:05729] Signal: Aborted (6)
[runnervmmklqx:05729] Signal code:  (-6)
[runnervmmklqx:05729] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8f2d645330]
[runnervmmklqx:05729] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8f2d69eb2c]
[runnervmmklqx:05729] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8f2d64527e]
[runnervmmklqx:05729] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8f2d6288ff]
[runnervmmklqx:05729] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8f2daa5ff5]
[runnervmmklqx:05729] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8f2dabb0da]
[runnervmmklqx:05729] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8f2daa5a55]
[runnervmmklqx:05729] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8f2daa5a6f]
[runnervmmklqx:05729] [ 8] plumed(+0x146dd)[0x5632052c16dd]
[runnervmmklqx:05729] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8f2d62a1ca]
[runnervmmklqx:05729] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8f2d62a28b]
[runnervmmklqx:05729] [11] plumed(+0x15365)[0x5632052c2365]
[runnervmmklqx:05729] *** End of error message ***
</pre>
{% endraw %}
