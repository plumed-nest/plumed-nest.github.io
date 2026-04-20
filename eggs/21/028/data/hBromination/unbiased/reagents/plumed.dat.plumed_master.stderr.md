**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/reagents/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:483) void PLMD::Keywords::addFlag(std::string_view, bool, std::string_view)
+++ assertion failed: !defaultValue
the second argument to addFlag must be false COMPONENTS
[runnervmeorf1:10325] *** Process received signal ***
[runnervmeorf1:10325] Signal: Aborted (6)
[runnervmeorf1:10325] Signal code:  (-6)
[runnervmeorf1:10325] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8f49045330]
[runnervmeorf1:10325] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8f4909eb2c]
[runnervmeorf1:10325] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8f4904527e]
[runnervmeorf1:10325] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8f490288ff]
[runnervmeorf1:10325] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8f494a5ff5]
[runnervmeorf1:10325] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8f494bb0da]
[runnervmeorf1:10325] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8f494a5a55]
[runnervmeorf1:10325] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8f494a5a6f]
[runnervmeorf1:10325] [ 8] plumed_master(+0x146dd)[0x5572b46be6dd]
[runnervmeorf1:10325] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8f4902a1ca]
[runnervmeorf1:10325] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8f4902a28b]
[runnervmeorf1:10325] [11] plumed_master(+0x15365)[0x5572b46bf365]
[runnervmeorf1:10325] *** End of error message ***
</pre>
{% endraw %}
