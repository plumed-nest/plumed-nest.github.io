**Project ID:** [plumID:20.026]({{ '/' | absolute_url }}eggs/20/026/)  
Stderr for source:  plumed_WTMD.dat   
Download: [zipped raw stdout](plumed_WTMD.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_WTMD.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s58 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmmklqx:10086] *** Process received signal ***
[runnervmmklqx:10086] Signal: Aborted (6)
[runnervmmklqx:10086] Signal code:  (-6)
[runnervmmklqx:10086] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7e11245330]
[runnervmmklqx:10086] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7e1129eb2c]
[runnervmmklqx:10086] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7e1124527e]
[runnervmmklqx:10086] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7e112288ff]
[runnervmmklqx:10086] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7e116a5ff5]
[runnervmmklqx:10086] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7e116bb0da]
[runnervmmklqx:10086] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7e116a5a55]
[runnervmmklqx:10086] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7e116a5a6f]
[runnervmmklqx:10086] [ 8] plumed(+0x146dd)[0x56261fe856dd]
[runnervmmklqx:10086] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7e1122a1ca]
[runnervmmklqx:10086] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7e1122a28b]
[runnervmmklqx:10086] [11] plumed(+0x15365)[0x56261fe86365]
[runnervmmklqx:10086] *** End of error message ***
</pre>
{% endraw %}
