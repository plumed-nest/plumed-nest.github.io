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
[pkrvm7jw40e0xgp:12511] *** Process received signal ***
[pkrvm7jw40e0xgp:12511] Signal: Aborted (6)
[pkrvm7jw40e0xgp:12511] Signal code:  (-6)
[pkrvm7jw40e0xgp:12511] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe9a6245330]
[pkrvm7jw40e0xgp:12511] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe9a629eb2c]
[pkrvm7jw40e0xgp:12511] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe9a624527e]
[pkrvm7jw40e0xgp:12511] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe9a62288ff]
[pkrvm7jw40e0xgp:12511] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe9a66a5ff5]
[pkrvm7jw40e0xgp:12511] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe9a66bb0da]
[pkrvm7jw40e0xgp:12511] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe9a66a5a55]
[pkrvm7jw40e0xgp:12511] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe9a66a5a6f]
[pkrvm7jw40e0xgp:12511] [ 8] plumed(+0x146dd)[0x55f573aa56dd]
[pkrvm7jw40e0xgp:12511] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe9a622a1ca]
[pkrvm7jw40e0xgp:12511] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe9a622a28b]
[pkrvm7jw40e0xgp:12511] [11] plumed(+0x15365)[0x55f573aa6365]
[pkrvm7jw40e0xgp:12511] *** End of error message ***
</pre>
{% endraw %}
