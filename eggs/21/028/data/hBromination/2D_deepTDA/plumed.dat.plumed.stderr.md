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
[fv-az1374-933:11637] *** Process received signal ***
[fv-az1374-933:11637] Signal: Aborted (6)
[fv-az1374-933:11637] Signal code:  (-6)
[fv-az1374-933:11637] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f110dc45330]
[fv-az1374-933:11637] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f110dc9eb2c]
[fv-az1374-933:11637] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f110dc4527e]
[fv-az1374-933:11637] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f110dc288ff]
[fv-az1374-933:11637] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f110e0a5ff5]
[fv-az1374-933:11637] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f110e0bb0da]
[fv-az1374-933:11637] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f110e0a5a55]
[fv-az1374-933:11637] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f110e0a5a6f]
[fv-az1374-933:11637] [ 8] plumed(+0x146dd)[0x55b9b99c36dd]
[fv-az1374-933:11637] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f110dc2a1ca]
[fv-az1374-933:11637] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f110dc2a28b]
[fv-az1374-933:11637] [11] plumed(+0x15365)[0x55b9b99c4365]
[fv-az1374-933:11637] *** End of error message ***
</pre>
{% endraw %}
