**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/anti_markovnikov/plumed.dat   
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
[fv-az805-507:08255] *** Process received signal ***
[fv-az805-507:08255] Signal: Aborted (6)
[fv-az805-507:08255] Signal code:  (-6)
[fv-az805-507:08255] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa05e645330]
[fv-az805-507:08255] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa05e69eb2c]
[fv-az805-507:08255] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa05e64527e]
[fv-az805-507:08255] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa05e6288ff]
[fv-az805-507:08255] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa05eaa5ff5]
[fv-az805-507:08255] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa05eabb0da]
[fv-az805-507:08255] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa05eaa5a55]
[fv-az805-507:08255] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa05eaa5a6f]
[fv-az805-507:08255] [ 8] plumed(+0x146dd)[0x5593295536dd]
[fv-az805-507:08255] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa05e62a1ca]
[fv-az805-507:08255] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa05e62a28b]
[fv-az805-507:08255] [11] plumed(+0x15365)[0x559329554365]
[fv-az805-507:08255] *** End of error message ***
</pre>
{% endraw %}
