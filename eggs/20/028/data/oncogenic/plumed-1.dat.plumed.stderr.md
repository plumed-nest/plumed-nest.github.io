**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  oncogenic/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:151) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  483  97.1
[runnervm0kj6c:11109] *** Process received signal ***
[runnervm0kj6c:11109] Signal: Aborted (6)
[runnervm0kj6c:11109] Signal code:  (-6)
[runnervm0kj6c:11109] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdf46e45330]
[runnervm0kj6c:11109] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdf46e9eb2c]
[runnervm0kj6c:11109] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdf46e4527e]
[runnervm0kj6c:11109] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdf46e288ff]
[runnervm0kj6c:11109] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdf472a5ff5]
[runnervm0kj6c:11109] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdf472bb0da]
[runnervm0kj6c:11109] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdf472a5a55]
[runnervm0kj6c:11109] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdf472a5a6f]
[runnervm0kj6c:11109] [ 8] plumed(+0x146dd)[0x556eff3516dd]
[runnervm0kj6c:11109] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdf46e2a1ca]
[runnervm0kj6c:11109] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdf46e2a28b]
[runnervm0kj6c:11109] [11] plumed(+0x15365)[0x556eff352365]
[runnervm0kj6c:11109] *** End of error message ***
</pre>
{% endraw %}
