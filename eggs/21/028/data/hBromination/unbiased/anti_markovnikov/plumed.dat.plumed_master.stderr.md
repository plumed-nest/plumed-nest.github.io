**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/anti_markovnikov/plumed.dat   
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
[runnervm76f27:10058] *** Process received signal ***
[runnervm76f27:10058] Signal: Aborted (6)
[runnervm76f27:10058] Signal code:  (-6)
[runnervm76f27:10058] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa1fba45330]
[runnervm76f27:10058] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa1fba9ec0c]
[runnervm76f27:10058] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa1fba4527e]
[runnervm76f27:10058] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa1fba288ff]
[runnervm76f27:10058] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa1fbea5ff5]
[runnervm76f27:10058] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa1fbebb0da]
[runnervm76f27:10058] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa1fbea5a55]
[runnervm76f27:10058] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa1fbea5a6f]
[runnervm76f27:10058] [ 8] plumed_master(+0x146dd)[0x55e105bcf6dd]
[runnervm76f27:10058] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa1fba2a1ca]
[runnervm76f27:10058] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa1fba2a28b]
[runnervm76f27:10058] [11] plumed_master(+0x15365)[0x55e105bd0365]
[runnervm76f27:10058] *** End of error message ***
</pre>
{% endraw %}
