**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/markovnikov/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:483) void PLMD::Keywords::addFlag(std::string_view, bool, std::string_view)
+++ assertion failed: !defaultValue
the second argument to addFlag must be false COMPONENTS
[runnervm76f27:10113] *** Process received signal ***
[runnervm76f27:10113] Signal: Aborted (6)
[runnervm76f27:10113] Signal code:  (-6)
[runnervm76f27:10113] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2d86c45330]
[runnervm76f27:10113] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2d86c9ec0c]
[runnervm76f27:10113] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2d86c4527e]
[runnervm76f27:10113] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2d86c288ff]
[runnervm76f27:10113] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2d870a5ff5]
[runnervm76f27:10113] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2d870bb0da]
[runnervm76f27:10113] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2d870a5a55]
[runnervm76f27:10113] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2d870a5a6f]
[runnervm76f27:10113] [ 8] plumed_master(+0x146dd)[0x5611cd2e56dd]
[runnervm76f27:10113] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2d86c2a1ca]
[runnervm76f27:10113] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2d86c2a28b]
[runnervm76f27:10113] [11] plumed_master(+0x15365)[0x5611cd2e6365]
[runnervm76f27:10113] *** End of error message ***
</pre>
{% endraw %}
