**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[runnervmmtnos:34494] *** Process received signal ***
[runnervmmtnos:34494] Signal: Aborted (6)
[runnervmmtnos:34494] Signal code:  (-6)
[runnervmmtnos:34494] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdc3ee45330]
[runnervmmtnos:34494] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdc3ee9eb2c]
[runnervmmtnos:34494] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdc3ee4527e]
[runnervmmtnos:34494] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdc3ee288ff]
[runnervmmtnos:34494] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdc3f2a5ff5]
[runnervmmtnos:34494] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdc3f2bb0da]
[runnervmmtnos:34494] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdc3f2a5a55]
[runnervmmtnos:34494] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdc3f2a5a6f]
[runnervmmtnos:34494] [ 8] plumed_master(+0x146dd)[0x55c2a39d96dd]
[runnervmmtnos:34494] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdc3ee2a1ca]
[runnervmmtnos:34494] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdc3ee2a28b]
[runnervmmtnos:34494] [11] plumed_master(+0x15365)[0x55c2a39da365]
[runnervmmtnos:34494] *** End of error message ***
</pre>
{% endraw %}
