**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4m/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PRINT with label @252 : cannot use argument parabeta0_both.struct-1 in input as not all elements are computed
[runnervmeorf1:05223] *** Process received signal ***
[runnervmeorf1:05223] Signal: Aborted (6)
[runnervmeorf1:05223] Signal code:  (-6)
[runnervmeorf1:05223] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9131045330]
[runnervmeorf1:05223] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f913109eb2c]
[runnervmeorf1:05223] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f913104527e]
[runnervmeorf1:05223] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f91310288ff]
[runnervmeorf1:05223] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f91314a5ff5]
[runnervmeorf1:05223] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f91314bb0da]
[runnervmeorf1:05223] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f91314a5a55]
[runnervmeorf1:05223] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f91314a5a6f]
[runnervmeorf1:05223] [ 8] plumed_master(+0x146dd)[0x55cd0b7cf6dd]
[runnervmeorf1:05223] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f913102a1ca]
[runnervmeorf1:05223] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f913102a28b]
[runnervmeorf1:05223] [11] plumed_master(+0x15365)[0x55cd0b7d0365]
[runnervmeorf1:05223] *** End of error message ***
</pre>
{% endraw %}
