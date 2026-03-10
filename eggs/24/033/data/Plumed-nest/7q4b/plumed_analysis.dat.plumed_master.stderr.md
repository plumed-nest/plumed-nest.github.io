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
[runnervm0kj6c:05297] *** Process received signal ***
[runnervm0kj6c:05297] Signal: Aborted (6)
[runnervm0kj6c:05297] Signal code:  (-6)
[runnervm0kj6c:05297] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff31a245330]
[runnervm0kj6c:05297] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff31a29eb2c]
[runnervm0kj6c:05297] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff31a24527e]
[runnervm0kj6c:05297] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff31a2288ff]
[runnervm0kj6c:05297] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff31a6a5ff5]
[runnervm0kj6c:05297] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff31a6bb0da]
[runnervm0kj6c:05297] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff31a6a5a55]
[runnervm0kj6c:05297] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff31a6a5a6f]
[runnervm0kj6c:05297] [ 8] plumed_master(+0x146dd)[0x55af19e8e6dd]
[runnervm0kj6c:05297] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff31a22a1ca]
[runnervm0kj6c:05297] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff31a22a28b]
[runnervm0kj6c:05297] [11] plumed_master(+0x15365)[0x55af19e8f365]
[runnervm0kj6c:05297] *** End of error message ***
</pre>
{% endraw %}
