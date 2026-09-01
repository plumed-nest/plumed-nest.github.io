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
[runnervmgx7h7:04761] *** Process received signal ***
[runnervmgx7h7:04761] Signal: Aborted (6)
[runnervmgx7h7:04761] Signal code:  (-6)
[runnervmgx7h7:04761] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6a53445330]
[runnervmgx7h7:04761] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6a5349ec0c]
[runnervmgx7h7:04761] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6a5344527e]
[runnervmgx7h7:04761] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6a534288ff]
[runnervmgx7h7:04761] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6a538a5ff5]
[runnervmgx7h7:04761] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6a538bb0da]
[runnervmgx7h7:04761] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6a538a5a55]
[runnervmgx7h7:04761] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6a538a5a6f]
[runnervmgx7h7:04761] [ 8] plumed_master(+0x146dd)[0x564e04b926dd]
[runnervmgx7h7:04761] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6a5342a1ca]
[runnervmgx7h7:04761] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6a5342a28b]
[runnervmgx7h7:04761] [11] plumed_master(+0x15365)[0x564e04b93365]
[runnervmgx7h7:04761] *** End of error message ***
</pre>
{% endraw %}
