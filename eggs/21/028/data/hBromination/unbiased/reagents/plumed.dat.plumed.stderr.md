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
[fv-az1374-933:11806] *** Process received signal ***
[fv-az1374-933:11806] Signal: Aborted (6)
[fv-az1374-933:11806] Signal code:  (-6)
[fv-az1374-933:11806] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4ae2045330]
[fv-az1374-933:11806] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4ae209eb2c]
[fv-az1374-933:11806] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4ae204527e]
[fv-az1374-933:11806] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4ae20288ff]
[fv-az1374-933:11806] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4ae24a5ff5]
[fv-az1374-933:11806] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4ae24bb0da]
[fv-az1374-933:11806] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4ae24a5a55]
[fv-az1374-933:11806] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4ae24a5a6f]
[fv-az1374-933:11806] [ 8] plumed(+0x146dd)[0x5628e75406dd]
[fv-az1374-933:11806] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4ae202a1ca]
[fv-az1374-933:11806] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4ae202a28b]
[fv-az1374-933:11806] [11] plumed(+0x15365)[0x5628e7541365]
[fv-az1374-933:11806] *** End of error message ***
</pre>
{% endraw %}
