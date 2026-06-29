**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4m/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PRINT with label @252 : cannot use argument parabeta0_both.struct-1 in input as not all elements are computed
[runnervmmklqx:06164] *** Process received signal ***
[runnervmmklqx:06164] Signal: Aborted (6)
[runnervmmklqx:06164] Signal code:  (-6)
[runnervmmklqx:06164] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbe66a45330]
[runnervmmklqx:06164] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbe66a9eb2c]
[runnervmmklqx:06164] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbe66a4527e]
[runnervmmklqx:06164] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbe66a288ff]
[runnervmmklqx:06164] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbe66ea5ff5]
[runnervmmklqx:06164] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbe66ebb0da]
[runnervmmklqx:06164] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbe66ea5a55]
[runnervmmklqx:06164] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbe66ea5a6f]
[runnervmmklqx:06164] [ 8] plumed_master(+0x146dd)[0x55637d24c6dd]
[runnervmmklqx:06164] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbe66a2a1ca]
[runnervmmklqx:06164] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbe66a2a28b]
[runnervmmklqx:06164] [11] plumed_master(+0x15365)[0x55637d24d365]
[runnervmmklqx:06164] *** End of error message ***
</pre>
{% endraw %}
