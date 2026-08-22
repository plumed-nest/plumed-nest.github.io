**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  oncogenic/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:151) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  483  97.1
[runnervm76f27:09713] *** Process received signal ***
[runnervm76f27:09713] Signal: Aborted (6)
[runnervm76f27:09713] Signal code:  (-6)
[runnervm76f27:09713] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9905e45330]
[runnervm76f27:09713] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9905e9ec0c]
[runnervm76f27:09713] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9905e4527e]
[runnervm76f27:09713] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9905e288ff]
[runnervm76f27:09713] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f99062a5ff5]
[runnervm76f27:09713] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f99062bb0da]
[runnervm76f27:09713] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f99062a5a55]
[runnervm76f27:09713] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f99062a5a6f]
[runnervm76f27:09713] [ 8] plumed(+0x146dd)[0x560a7378f6dd]
[runnervm76f27:09713] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9905e2a1ca]
[runnervm76f27:09713] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9905e2a28b]
[runnervm76f27:09713] [11] plumed(+0x15365)[0x560a73790365]
[runnervm76f27:09713] *** End of error message ***
</pre>
{% endraw %}
