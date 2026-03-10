**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  wild-type/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:173) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  461  97.1
[runnervm0kj6c:11073] *** Process received signal ***
[runnervm0kj6c:11073] Signal: Aborted (6)
[runnervm0kj6c:11073] Signal code:  (-6)
[runnervm0kj6c:11073] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f83b4645330]
[runnervm0kj6c:11073] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f83b469eb2c]
[runnervm0kj6c:11073] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f83b464527e]
[runnervm0kj6c:11073] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f83b46288ff]
[runnervm0kj6c:11073] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f83b4aa5ff5]
[runnervm0kj6c:11073] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f83b4abb0da]
[runnervm0kj6c:11073] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f83b4aa5a55]
[runnervm0kj6c:11073] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f83b4aa5a6f]
[runnervm0kj6c:11073] [ 8] plumed_master(+0x146dd)[0x563b296c56dd]
[runnervm0kj6c:11073] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f83b462a1ca]
[runnervm0kj6c:11073] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f83b462a28b]
[runnervm0kj6c:11073] [11] plumed_master(+0x15365)[0x563b296c6365]
[runnervm0kj6c:11073] *** End of error message ***
</pre>
{% endraw %}
