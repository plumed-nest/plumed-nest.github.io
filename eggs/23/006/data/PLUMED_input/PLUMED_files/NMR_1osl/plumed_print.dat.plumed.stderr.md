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
[runnervmw9dnm:08638] *** Process received signal ***
[runnervmw9dnm:08638] Signal: Aborted (6)
[runnervmw9dnm:08638] Signal code:  (-6)
[runnervmw9dnm:08638] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff65c045330]
[runnervmw9dnm:08638] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff65c09eb2c]
[runnervmw9dnm:08638] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff65c04527e]
[runnervmw9dnm:08638] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff65c0288ff]
[runnervmw9dnm:08638] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff65c4a5ff5]
[runnervmw9dnm:08638] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff65c4bb0da]
[runnervmw9dnm:08638] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff65c4a5a55]
[runnervmw9dnm:08638] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff65c4a5a6f]
[runnervmw9dnm:08638] [ 8] plumed(+0x146dd)[0x55f2ef14c6dd]
[runnervmw9dnm:08638] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff65c02a1ca]
[runnervmw9dnm:08638] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff65c02a28b]
[runnervmw9dnm:08638] [11] plumed(+0x15365)[0x55f2ef14d365]
[runnervmw9dnm:08638] *** End of error message ***
</pre>
{% endraw %}
