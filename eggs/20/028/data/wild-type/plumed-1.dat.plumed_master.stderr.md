**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  wild-type/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:173) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  461  97.1
[runnervm76f27:09676] *** Process received signal ***
[runnervm76f27:09676] Signal: Aborted (6)
[runnervm76f27:09676] Signal code:  (-6)
[runnervm76f27:09676] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc79b845330]
[runnervm76f27:09676] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc79b89ec0c]
[runnervm76f27:09676] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc79b84527e]
[runnervm76f27:09676] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc79b8288ff]
[runnervm76f27:09676] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc79bca5ff5]
[runnervm76f27:09676] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc79bcbb0da]
[runnervm76f27:09676] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc79bca5a55]
[runnervm76f27:09676] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc79bca5a6f]
[runnervm76f27:09676] [ 8] plumed_master(+0x146dd)[0x55b227dc36dd]
[runnervm76f27:09676] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc79b82a1ca]
[runnervm76f27:09676] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc79b82a28b]
[runnervm76f27:09676] [11] plumed_master(+0x15365)[0x55b227dc4365]
[runnervm76f27:09676] *** End of error message ***
</pre>
{% endraw %}
