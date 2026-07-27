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
[runnervmvrwv9:05208] *** Process received signal ***
[runnervmvrwv9:05208] Signal: Aborted (6)
[runnervmvrwv9:05208] Signal code:  (-6)
[runnervmvrwv9:05208] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc854045330]
[runnervmvrwv9:05208] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc85409eb2c]
[runnervmvrwv9:05208] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc85404527e]
[runnervmvrwv9:05208] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc8540288ff]
[runnervmvrwv9:05208] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc8544a5ff5]
[runnervmvrwv9:05208] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc8544bb0da]
[runnervmvrwv9:05208] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc8544a5a55]
[runnervmvrwv9:05208] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc8544a5a6f]
[runnervmvrwv9:05208] [ 8] plumed_master(+0x146dd)[0x563b1bf4b6dd]
[runnervmvrwv9:05208] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc85402a1ca]
[runnervmvrwv9:05208] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc85402a28b]
[runnervmvrwv9:05208] [11] plumed_master(+0x15365)[0x563b1bf4c365]
[runnervmvrwv9:05208] *** End of error message ***
</pre>
{% endraw %}
