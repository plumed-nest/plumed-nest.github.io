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
[pkrvm7jw40e0xgp:12342] *** Process received signal ***
[pkrvm7jw40e0xgp:12342] Signal: Aborted (6)
[pkrvm7jw40e0xgp:12342] Signal code:  (-6)
[pkrvm7jw40e0xgp:12342] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f120de45330]
[pkrvm7jw40e0xgp:12342] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f120de9eb2c]
[pkrvm7jw40e0xgp:12342] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f120de4527e]
[pkrvm7jw40e0xgp:12342] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f120de288ff]
[pkrvm7jw40e0xgp:12342] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f120e2a5ff5]
[pkrvm7jw40e0xgp:12342] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f120e2bb0da]
[pkrvm7jw40e0xgp:12342] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f120e2a5a55]
[pkrvm7jw40e0xgp:12342] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f120e2a5a6f]
[pkrvm7jw40e0xgp:12342] [ 8] plumed(+0x146dd)[0x55895400b6dd]
[pkrvm7jw40e0xgp:12342] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f120de2a1ca]
[pkrvm7jw40e0xgp:12342] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f120de2a28b]
[pkrvm7jw40e0xgp:12342] [11] plumed(+0x15365)[0x55895400c365]
[pkrvm7jw40e0xgp:12342] *** End of error message ***
</pre>
{% endraw %}
