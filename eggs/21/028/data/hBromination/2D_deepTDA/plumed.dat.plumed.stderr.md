**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/2D_deepTDA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[runnervm76f27:09985] *** Process received signal ***
[runnervm76f27:09985] Signal: Aborted (6)
[runnervm76f27:09985] Signal code:  (-6)
[runnervm76f27:09985] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f506f845330]
[runnervm76f27:09985] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f506f89ec0c]
[runnervm76f27:09985] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f506f84527e]
[runnervm76f27:09985] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f506f8288ff]
[runnervm76f27:09985] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f506fca5ff5]
[runnervm76f27:09985] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f506fcbb0da]
[runnervm76f27:09985] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f506fca5a55]
[runnervm76f27:09985] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f506fca5a6f]
[runnervm76f27:09985] [ 8] plumed(+0x146dd)[0x557081d5a6dd]
[runnervm76f27:09985] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f506f82a1ca]
[runnervm76f27:09985] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f506f82a28b]
[runnervm76f27:09985] [11] plumed(+0x15365)[0x557081d5b365]
[runnervm76f27:09985] *** End of error message ***
</pre>
{% endraw %}
