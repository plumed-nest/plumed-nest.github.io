**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action PRINT with label @333 : cannot use argument parabeta0_both.struct-1 in input as not all elements are computed
[runnervmi13qx:32405] *** Process received signal ***
[runnervmi13qx:32405] Signal: Aborted (6)
[runnervmi13qx:32405] Signal code:  (-6)
[runnervmi13qx:32405] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6358445330]
[runnervmi13qx:32405] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f635849eb2c]
[runnervmi13qx:32405] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f635844527e]
[runnervmi13qx:32405] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f63584288ff]
[runnervmi13qx:32405] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f63588a5ff5]
[runnervmi13qx:32405] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f63588bb0da]
[runnervmi13qx:32405] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f63588a5a55]
[runnervmi13qx:32405] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f63588a5a6f]
[runnervmi13qx:32405] [ 8] plumed_master(+0x146dd)[0x5597c407d6dd]
[runnervmi13qx:32405] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f635842a1ca]
[runnervmi13qx:32405] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f635842a28b]
[runnervmi13qx:32405] [11] plumed_master(+0x15365)[0x5597c407e365]
[runnervmi13qx:32405] *** End of error message ***
</pre>
{% endraw %}
