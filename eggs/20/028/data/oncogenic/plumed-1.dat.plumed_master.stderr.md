**Project ID:** [plumID:20.028]({{ '/' | absolute_url }}eggs/20/028/)  
Stderr for source:  oncogenic/plumed-1.dat   
Download: [zipped raw stdout](plumed-1.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-1.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Tools.h:173) static void PLMD::Tools::convert(const T&, U&) [with T = std::__cxx11::basic_string<char>; U = double]
+++ assertion failed: convertNoexcept(t,u)
Error converting  483  97.1
[runnervmeorf1:10288] *** Process received signal ***
[runnervmeorf1:10288] Signal: Aborted (6)
[runnervmeorf1:10288] Signal code:  (-6)
[runnervmeorf1:10288] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f05c3645330]
[runnervmeorf1:10288] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f05c369eb2c]
[runnervmeorf1:10288] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f05c364527e]
[runnervmeorf1:10288] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f05c36288ff]
[runnervmeorf1:10288] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f05c3aa5ff5]
[runnervmeorf1:10288] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f05c3abb0da]
[runnervmeorf1:10288] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f05c3aa5a55]
[runnervmeorf1:10288] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f05c3aa5a6f]
[runnervmeorf1:10288] [ 8] plumed_master(+0x146dd)[0x5620196ac6dd]
[runnervmeorf1:10288] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f05c362a1ca]
[runnervmeorf1:10288] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f05c362a28b]
[runnervmeorf1:10288] [11] plumed_master(+0x15365)[0x5620196ad365]
[runnervmeorf1:10288] *** End of error message ***
</pre>
{% endraw %}
