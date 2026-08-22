**Project ID:** [plumID:23.027]({{ '/' | absolute_url }}eggs/23/027/)  
Stderr for source:  water-structure-driver.dat   
Download: [zipped raw stdout](water-structure-driver.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](water-structure-driver.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @150 : keyword ARG is compulsory for this action
[runnervm76f27:07591] *** Process received signal ***
[runnervm76f27:07591] Signal: Aborted (6)
[runnervm76f27:07591] Signal code:  (-6)
[runnervm76f27:07591] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdd47245330]
[runnervm76f27:07591] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdd4729ec0c]
[runnervm76f27:07591] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdd4724527e]
[runnervm76f27:07591] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdd472288ff]
[runnervm76f27:07591] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdd476a5ff5]
[runnervm76f27:07591] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdd476bb0da]
[runnervm76f27:07591] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdd476a5a55]
[runnervm76f27:07591] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdd476a5a6f]
[runnervm76f27:07591] [ 8] plumed_master(+0x146dd)[0x5594b80096dd]
[runnervm76f27:07591] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdd4722a1ca]
[runnervm76f27:07591] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdd4722a28b]
[runnervm76f27:07591] [11] plumed_master(+0x15365)[0x5594b800a365]
[runnervm76f27:07591] *** End of error message ***
</pre>
{% endraw %}
