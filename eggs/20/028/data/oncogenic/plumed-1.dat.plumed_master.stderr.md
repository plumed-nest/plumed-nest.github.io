**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  oncogenic/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:172) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  483  97.1
[runnervmkj6or:08862] *** Process received signal ***
[runnervmkj6or:08862] Signal: Aborted (6)
[runnervmkj6or:08862] Signal code:  (-6)
[runnervmkj6or:08862] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc9ae645330]
[runnervmkj6or:08862] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc9ae69eb2c]
[runnervmkj6or:08862] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc9ae64527e]
[runnervmkj6or:08862] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc9ae6288ff]
[runnervmkj6or:08862] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc9aeaa5ff5]
[runnervmkj6or:08862] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc9aeabb0da]
[runnervmkj6or:08862] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc9aeaa5a55]
[runnervmkj6or:08862] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc9aeaa5a6f]
[runnervmkj6or:08862] [ 8] plumed_master(+0x146dd)[0x55c3aaa6a6dd]
[runnervmkj6or:08862] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc9ae62a1ca]
[runnervmkj6or:08862] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc9ae62a28b]
[runnervmkj6or:08862] [11] plumed_master(+0x15365)[0x55c3aaa6b365]
[runnervmkj6or:08862] *** End of error message ***
</pre>
{% endraw %}
