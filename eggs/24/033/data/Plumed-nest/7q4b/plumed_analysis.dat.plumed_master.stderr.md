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
[runnervmvrwv9:05061] *** Process received signal ***
[runnervmvrwv9:05061] Signal: Aborted (6)
[runnervmvrwv9:05061] Signal code:  (-6)
[runnervmvrwv9:05061] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f840d645330]
[runnervmvrwv9:05061] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f840d69eb2c]
[runnervmvrwv9:05061] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f840d64527e]
[runnervmvrwv9:05061] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f840d6288ff]
[runnervmvrwv9:05061] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f840daa5ff5]
[runnervmvrwv9:05061] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f840dabb0da]
[runnervmvrwv9:05061] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f840daa5a55]
[runnervmvrwv9:05061] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f840daa5a6f]
[runnervmvrwv9:05061] [ 8] plumed_master(+0x146dd)[0x55c5790aa6dd]
[runnervmvrwv9:05061] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f840d62a1ca]
[runnervmvrwv9:05061] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f840d62a28b]
[runnervmvrwv9:05061] [11] plumed_master(+0x15365)[0x55c5790ab365]
[runnervmvrwv9:05061] *** End of error message ***
</pre>
{% endraw %}
