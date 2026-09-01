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
[runnervmgx7h7:04906] *** Process received signal ***
[runnervmgx7h7:04906] Signal: Aborted (6)
[runnervmgx7h7:04906] Signal code:  (-6)
[runnervmgx7h7:04906] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa9a3845330]
[runnervmgx7h7:04906] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa9a389ec0c]
[runnervmgx7h7:04906] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa9a384527e]
[runnervmgx7h7:04906] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa9a38288ff]
[runnervmgx7h7:04906] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa9a3ca5ff5]
[runnervmgx7h7:04906] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa9a3cbb0da]
[runnervmgx7h7:04906] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa9a3ca5a55]
[runnervmgx7h7:04906] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa9a3ca5a6f]
[runnervmgx7h7:04906] [ 8] plumed_master(+0x146dd)[0x562e076b36dd]
[runnervmgx7h7:04906] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa9a382a1ca]
[runnervmgx7h7:04906] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa9a382a28b]
[runnervmgx7h7:04906] [11] plumed_master(+0x15365)[0x562e076b4365]
[runnervmgx7h7:04906] *** End of error message ***
</pre>
{% endraw %}
