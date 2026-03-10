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
[runnervm0kj6c:05450] *** Process received signal ***
[runnervm0kj6c:05450] Signal: Aborted (6)
[runnervm0kj6c:05450] Signal code:  (-6)
[runnervm0kj6c:05450] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa49fe45330]
[runnervm0kj6c:05450] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa49fe9eb2c]
[runnervm0kj6c:05450] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa49fe4527e]
[runnervm0kj6c:05450] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa49fe288ff]
[runnervm0kj6c:05450] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa4a02a5ff5]
[runnervm0kj6c:05450] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa4a02bb0da]
[runnervm0kj6c:05450] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa4a02a5a55]
[runnervm0kj6c:05450] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa4a02a5a6f]
[runnervm0kj6c:05450] [ 8] plumed_master(+0x146dd)[0x55cf67c2b6dd]
[runnervm0kj6c:05450] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa49fe2a1ca]
[runnervm0kj6c:05450] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa49fe2a28b]
[runnervm0kj6c:05450] [11] plumed_master(+0x15365)[0x55cf67c2c365]
[runnervm0kj6c:05450] *** End of error message ***
</pre>
{% endraw %}
