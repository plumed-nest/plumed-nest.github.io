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
[pkrvm7jw40e0xgp:12455] *** Process received signal ***
[pkrvm7jw40e0xgp:12455] Signal: Aborted (6)
[pkrvm7jw40e0xgp:12455] Signal code:  (-6)
[pkrvm7jw40e0xgp:12455] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9cf5e45330]
[pkrvm7jw40e0xgp:12455] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9cf5e9eb2c]
[pkrvm7jw40e0xgp:12455] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9cf5e4527e]
[pkrvm7jw40e0xgp:12455] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9cf5e288ff]
[pkrvm7jw40e0xgp:12455] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9cf62a5ff5]
[pkrvm7jw40e0xgp:12455] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9cf62bb0da]
[pkrvm7jw40e0xgp:12455] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9cf62a5a55]
[pkrvm7jw40e0xgp:12455] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9cf62a5a6f]
[pkrvm7jw40e0xgp:12455] [ 8] plumed(+0x146dd)[0x561949e0b6dd]
[pkrvm7jw40e0xgp:12455] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9cf5e2a1ca]
[pkrvm7jw40e0xgp:12455] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9cf5e2a28b]
[pkrvm7jw40e0xgp:12455] [11] plumed(+0x15365)[0x561949e0c365]
[pkrvm7jw40e0xgp:12455] *** End of error message ***
</pre>
{% endraw %}
