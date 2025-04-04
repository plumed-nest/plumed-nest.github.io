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
[fv-az805-507:08310] *** Process received signal ***
[fv-az805-507:08310] Signal: Aborted (6)
[fv-az805-507:08310] Signal code:  (-6)
[fv-az805-507:08310] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe6a5e45330]
[fv-az805-507:08310] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe6a5e9eb2c]
[fv-az805-507:08310] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe6a5e4527e]
[fv-az805-507:08310] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe6a5e288ff]
[fv-az805-507:08310] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe6a62a5ff5]
[fv-az805-507:08310] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe6a62bb0da]
[fv-az805-507:08310] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe6a62a5a55]
[fv-az805-507:08310] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe6a62a5a6f]
[fv-az805-507:08310] [ 8] plumed(+0x146dd)[0x56537b16b6dd]
[fv-az805-507:08310] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe6a5e2a1ca]
[fv-az805-507:08310] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe6a5e2a28b]
[fv-az805-507:08310] [11] plumed(+0x15365)[0x56537b16c365]
[fv-az805-507:08310] *** End of error message ***
</pre>
{% endraw %}
