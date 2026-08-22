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
[runnervm76f27:06158] *** Process received signal ***
[runnervm76f27:06158] Signal: Aborted (6)
[runnervm76f27:06158] Signal code:  (-6)
[runnervm76f27:06158] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe479645330]
[runnervm76f27:06158] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe47969ec0c]
[runnervm76f27:06158] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe47964527e]
[runnervm76f27:06158] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe4796288ff]
[runnervm76f27:06158] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe479aa5ff5]
[runnervm76f27:06158] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe479abb0da]
[runnervm76f27:06158] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe479aa5a55]
[runnervm76f27:06158] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe479aa5a6f]
[runnervm76f27:06158] [ 8] plumed_master(+0x146dd)[0x56214b2ee6dd]
[runnervm76f27:06158] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe47962a1ca]
[runnervm76f27:06158] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe47962a28b]
[runnervm76f27:06158] [11] plumed_master(+0x15365)[0x56214b2ef365]
[runnervm76f27:06158] *** End of error message ***
</pre>
{% endraw %}
