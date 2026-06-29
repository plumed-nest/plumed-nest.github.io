**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis_unbiased.dat   
Download: [zipped raw stdout](plumed_analysis_unbiased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_analysis_unbiased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[runnervmmklqx:09341] *** Process received signal ***
[runnervmmklqx:09341] Signal: Aborted (6)
[runnervmmklqx:09341] Signal code:  (-6)
[runnervmmklqx:09341] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3b6ea45330]
[runnervmmklqx:09341] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3b6ea9eb2c]
[runnervmmklqx:09341] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3b6ea4527e]
[runnervmmklqx:09341] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3b6ea288ff]
[runnervmmklqx:09341] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3b6eea5ff5]
[runnervmmklqx:09341] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3b6eebb0da]
[runnervmmklqx:09341] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3b6eea5a55]
[runnervmmklqx:09341] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3b6eea5a6f]
[runnervmmklqx:09341] [ 8] plumed(+0x146dd)[0x5627a5bb96dd]
[runnervmmklqx:09341] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3b6ea2a1ca]
[runnervmmklqx:09341] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3b6ea2a28b]
[runnervmmklqx:09341] [11] plumed(+0x15365)[0x5627a5bba365]
[runnervmmklqx:09341] *** End of error message ***
</pre>
{% endraw %}
