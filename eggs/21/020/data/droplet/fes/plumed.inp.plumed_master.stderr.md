**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  droplet/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:378) void PLMD::Keywords::use(std::string_view)
+++ assertion failed: reserved(k)
the ARG keyword is not reserved
[runnervm76f27:08407] *** Process received signal ***
[runnervm76f27:08407] Signal: Aborted (6)
[runnervm76f27:08407] Signal code:  (-6)
[runnervm76f27:08407] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6c20645330]
[runnervm76f27:08407] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6c2069ec0c]
[runnervm76f27:08407] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6c2064527e]
[runnervm76f27:08407] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6c206288ff]
[runnervm76f27:08407] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6c20aa5ff5]
[runnervm76f27:08407] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6c20abb0da]
[runnervm76f27:08407] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6c20aa5a55]
[runnervm76f27:08407] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6c20aa5a6f]
[runnervm76f27:08407] [ 8] plumed_master(+0x146dd)[0x562fc02e16dd]
[runnervm76f27:08407] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6c2062a1ca]
[runnervm76f27:08407] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6c2062a28b]
[runnervm76f27:08407] [11] plumed_master(+0x15365)[0x562fc02e2365]
[runnervm76f27:08407] *** End of error message ***
</pre>
{% endraw %}
