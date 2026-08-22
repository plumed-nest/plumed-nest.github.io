**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  wild-type/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:151) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  461  97.1
[runnervm76f27:09659] *** Process received signal ***
[runnervm76f27:09659] Signal: Aborted (6)
[runnervm76f27:09659] Signal code:  (-6)
[runnervm76f27:09659] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f73aec45330]
[runnervm76f27:09659] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f73aec9ec0c]
[runnervm76f27:09659] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f73aec4527e]
[runnervm76f27:09659] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f73aec288ff]
[runnervm76f27:09659] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f73af0a5ff5]
[runnervm76f27:09659] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f73af0bb0da]
[runnervm76f27:09659] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f73af0a5a55]
[runnervm76f27:09659] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f73af0a5a6f]
[runnervm76f27:09659] [ 8] plumed(+0x146dd)[0x556d8b84c6dd]
[runnervm76f27:09659] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f73aec2a1ca]
[runnervm76f27:09659] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f73aec2a28b]
[runnervm76f27:09659] [11] plumed(+0x15365)[0x556d8b84d365]
[runnervm76f27:09659] *** End of error message ***
</pre>
{% endraw %}
