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
[fv-az1921-959:66811] *** Process received signal ***
[fv-az1921-959:66811] Signal: Aborted (6)
[fv-az1921-959:66811] Signal code:  (-6)
[fv-az1921-959:66811] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1bd6045330]
[fv-az1921-959:66811] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1bd609eb2c]
[fv-az1921-959:66811] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1bd604527e]
[fv-az1921-959:66811] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1bd60288ff]
[fv-az1921-959:66811] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1bd64a5ff5]
[fv-az1921-959:66811] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1bd64bb0da]
[fv-az1921-959:66811] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1bd64a5a55]
[fv-az1921-959:66811] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1bd64a5a6f]
[fv-az1921-959:66811] [ 8] plumed(+0x146dd)[0x55a82ea6a6dd]
[fv-az1921-959:66811] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1bd602a1ca]
[fv-az1921-959:66811] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1bd602a28b]
[fv-az1921-959:66811] [11] plumed(+0x15365)[0x55a82ea6b365]
[fv-az1921-959:66811] *** End of error message ***
</pre>
{% endraw %}
