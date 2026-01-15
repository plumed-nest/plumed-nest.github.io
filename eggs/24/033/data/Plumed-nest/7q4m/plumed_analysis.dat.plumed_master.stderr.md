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
[runnervmi13qx:32551] *** Process received signal ***
[runnervmi13qx:32551] Signal: Aborted (6)
[runnervmi13qx:32551] Signal code:  (-6)
[runnervmi13qx:32551] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe5c2a45330]
[runnervmi13qx:32551] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe5c2a9eb2c]
[runnervmi13qx:32551] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe5c2a4527e]
[runnervmi13qx:32551] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe5c2a288ff]
[runnervmi13qx:32551] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe5c2ea5ff5]
[runnervmi13qx:32551] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe5c2ebb0da]
[runnervmi13qx:32551] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe5c2ea5a55]
[runnervmi13qx:32551] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe5c2ea5a6f]
[runnervmi13qx:32551] [ 8] plumed_master(+0x146dd)[0x556c4cb3f6dd]
[runnervmi13qx:32551] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe5c2a2a1ca]
[runnervmi13qx:32551] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe5c2a2a28b]
[runnervmi13qx:32551] [11] plumed_master(+0x15365)[0x556c4cb40365]
[runnervmi13qx:32551] *** End of error message ***
</pre>
{% endraw %}
