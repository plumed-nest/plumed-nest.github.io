**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PRINT with label @333 : cannot use argument parabeta0_both.struct-1 in input as not all elements are computed
[runnervmmklqx:06015] *** Process received signal ***
[runnervmmklqx:06015] Signal: Aborted (6)
[runnervmmklqx:06015] Signal code:  (-6)
[runnervmmklqx:06015] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa88c245330]
[runnervmmklqx:06015] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa88c29eb2c]
[runnervmmklqx:06015] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa88c24527e]
[runnervmmklqx:06015] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa88c2288ff]
[runnervmmklqx:06015] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa88c6a5ff5]
[runnervmmklqx:06015] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa88c6bb0da]
[runnervmmklqx:06015] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa88c6a5a55]
[runnervmmklqx:06015] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa88c6a5a6f]
[runnervmmklqx:06015] [ 8] plumed_master(+0x146dd)[0x55da93ee46dd]
[runnervmmklqx:06015] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa88c22a1ca]
[runnervmmklqx:06015] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa88c22a28b]
[runnervmmklqx:06015] [11] plumed_master(+0x15365)[0x55da93ee5365]
[runnervmmklqx:06015] *** End of error message ***
</pre>
{% endraw %}
