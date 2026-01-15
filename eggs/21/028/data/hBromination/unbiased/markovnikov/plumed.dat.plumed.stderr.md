**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/markovnikov/plumed.dat   
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
[runnervmi13qx:35581] *** Process received signal ***
[runnervmi13qx:35581] Signal: Aborted (6)
[runnervmi13qx:35581] Signal code:  (-6)
[runnervmi13qx:35581] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9376045330]
[runnervmi13qx:35581] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f937609eb2c]
[runnervmi13qx:35581] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f937604527e]
[runnervmi13qx:35581] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f93760288ff]
[runnervmi13qx:35581] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f93764a5ff5]
[runnervmi13qx:35581] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f93764bb0da]
[runnervmi13qx:35581] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f93764a5a55]
[runnervmi13qx:35581] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f93764a5a6f]
[runnervmi13qx:35581] [ 8] plumed(+0x146dd)[0x56472c11d6dd]
[runnervmi13qx:35581] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f937602a1ca]
[runnervmi13qx:35581] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f937602a28b]
[runnervmi13qx:35581] [11] plumed(+0x15365)[0x56472c11e365]
[runnervmi13qx:35581] *** End of error message ***
</pre>
{% endraw %}
