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
[fv-az1377-740:62665] *** Process received signal ***
[fv-az1377-740:62665] Signal: Aborted (6)
[fv-az1377-740:62665] Signal code:  (-6)
[fv-az1377-740:62665] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7b88e45330]
[fv-az1377-740:62665] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7b88e9eb2c]
[fv-az1377-740:62665] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7b88e4527e]
[fv-az1377-740:62665] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7b88e288ff]
[fv-az1377-740:62665] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7b892a5ff5]
[fv-az1377-740:62665] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7b892bb0da]
[fv-az1377-740:62665] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7b892a5a55]
[fv-az1377-740:62665] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7b892a5a6f]
[fv-az1377-740:62665] [ 8] plumed(+0x146dd)[0x55d54e39b6dd]
[fv-az1377-740:62665] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7b88e2a1ca]
[fv-az1377-740:62665] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7b88e2a28b]
[fv-az1377-740:62665] [11] plumed(+0x15365)[0x55d54e39c365]
[fv-az1377-740:62665] *** End of error message ***
</pre>
{% endraw %}
