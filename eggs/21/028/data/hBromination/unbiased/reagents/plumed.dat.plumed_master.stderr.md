**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/reagents/plumed.dat   
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
[runnervm76f27:10169] *** Process received signal ***
[runnervm76f27:10169] Signal: Aborted (6)
[runnervm76f27:10169] Signal code:  (-6)
[runnervm76f27:10169] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8c8dc45330]
[runnervm76f27:10169] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8c8dc9ec0c]
[runnervm76f27:10169] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8c8dc4527e]
[runnervm76f27:10169] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8c8dc288ff]
[runnervm76f27:10169] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8c8e0a5ff5]
[runnervm76f27:10169] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8c8e0bb0da]
[runnervm76f27:10169] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8c8e0a5a55]
[runnervm76f27:10169] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8c8e0a5a6f]
[runnervm76f27:10169] [ 8] plumed_master(+0x146dd)[0x55dd7ec3f6dd]
[runnervm76f27:10169] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8c8dc2a1ca]
[runnervm76f27:10169] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8c8dc2a28b]
[runnervm76f27:10169] [11] plumed_master(+0x15365)[0x55dd7ec40365]
[runnervm76f27:10169] *** End of error message ***
</pre>
{% endraw %}
