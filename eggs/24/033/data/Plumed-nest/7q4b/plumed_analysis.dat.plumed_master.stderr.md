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
[runnervm76f27:06008] *** Process received signal ***
[runnervm76f27:06008] Signal: Aborted (6)
[runnervm76f27:06008] Signal code:  (-6)
[runnervm76f27:06008] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2fd9e45330]
[runnervm76f27:06008] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2fd9e9ec0c]
[runnervm76f27:06008] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2fd9e4527e]
[runnervm76f27:06008] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2fd9e288ff]
[runnervm76f27:06008] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2fda2a5ff5]
[runnervm76f27:06008] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2fda2bb0da]
[runnervm76f27:06008] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2fda2a5a55]
[runnervm76f27:06008] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2fda2a5a6f]
[runnervm76f27:06008] [ 8] plumed_master(+0x146dd)[0x55d4bf7776dd]
[runnervm76f27:06008] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2fd9e2a1ca]
[runnervm76f27:06008] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2fd9e2a28b]
[runnervm76f27:06008] [11] plumed_master(+0x15365)[0x55d4bf778365]
[runnervm76f27:06008] *** End of error message ***
</pre>
{% endraw %}
