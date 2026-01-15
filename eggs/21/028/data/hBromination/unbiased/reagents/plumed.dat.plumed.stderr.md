**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/reagents/plumed.dat   
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
[runnervmi13qx:35637] *** Process received signal ***
[runnervmi13qx:35637] Signal: Aborted (6)
[runnervmi13qx:35637] Signal code:  (-6)
[runnervmi13qx:35637] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9043e45330]
[runnervmi13qx:35637] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9043e9eb2c]
[runnervmi13qx:35637] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9043e4527e]
[runnervmi13qx:35637] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9043e288ff]
[runnervmi13qx:35637] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f90442a5ff5]
[runnervmi13qx:35637] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f90442bb0da]
[runnervmi13qx:35637] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f90442a5a55]
[runnervmi13qx:35637] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f90442a5a6f]
[runnervmi13qx:35637] [ 8] plumed(+0x146dd)[0x55a42e9916dd]
[runnervmi13qx:35637] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9043e2a1ca]
[runnervmi13qx:35637] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9043e2a28b]
[runnervmi13qx:35637] [11] plumed(+0x15365)[0x55a42e992365]
[runnervmi13qx:35637] *** End of error message ***
</pre>
{% endraw %}
