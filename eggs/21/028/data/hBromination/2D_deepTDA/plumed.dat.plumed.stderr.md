**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/2D_deepTDA/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:263) void PLMD::Keywords::addFlag(const std::string&, bool, const std::string&)
+++ assertion failed: !def
the second argument to addFlag must be false COMPONENTS
[runnervmw9dnm:10747] *** Process received signal ***
[runnervmw9dnm:10747] Signal: Aborted (6)
[runnervmw9dnm:10747] Signal code:  (-6)
[runnervmw9dnm:10747] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff9efe45330]
[runnervmw9dnm:10747] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff9efe9eb2c]
[runnervmw9dnm:10747] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff9efe4527e]
[runnervmw9dnm:10747] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff9efe288ff]
[runnervmw9dnm:10747] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff9f02a5ff5]
[runnervmw9dnm:10747] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff9f02bb0da]
[runnervmw9dnm:10747] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff9f02a5a55]
[runnervmw9dnm:10747] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff9f02a5a6f]
[runnervmw9dnm:10747] [ 8] plumed(+0x146dd)[0x557409d4b6dd]
[runnervmw9dnm:10747] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff9efe2a1ca]
[runnervmw9dnm:10747] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff9efe2a28b]
[runnervmw9dnm:10747] [11] plumed(+0x15365)[0x557409d4c365]
[runnervmw9dnm:10747] *** End of error message ***
</pre>
{% endraw %}
