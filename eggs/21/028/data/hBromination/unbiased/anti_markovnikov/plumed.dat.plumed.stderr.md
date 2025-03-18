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
[fv-az1377-740:62721] *** Process received signal ***
[fv-az1377-740:62721] Signal: Aborted (6)
[fv-az1377-740:62721] Signal code:  (-6)
[fv-az1377-740:62721] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f29d1845330]
[fv-az1377-740:62721] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f29d189eb2c]
[fv-az1377-740:62721] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f29d184527e]
[fv-az1377-740:62721] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f29d18288ff]
[fv-az1377-740:62721] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f29d1ca5ff5]
[fv-az1377-740:62721] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f29d1cbb0da]
[fv-az1377-740:62721] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f29d1ca5a55]
[fv-az1377-740:62721] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f29d1ca5a6f]
[fv-az1377-740:62721] [ 8] plumed(+0x146dd)[0x56083860a6dd]
[fv-az1377-740:62721] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f29d182a1ca]
[fv-az1377-740:62721] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f29d182a28b]
[fv-az1377-740:62721] [11] plumed(+0x15365)[0x56083860b365]
[fv-az1377-740:62721] *** End of error message ***
</pre>
{% endraw %}
