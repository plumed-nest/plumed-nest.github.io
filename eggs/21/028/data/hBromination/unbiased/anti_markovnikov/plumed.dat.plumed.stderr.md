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
[pkrvm7jw40e0xgp:12398] *** Process received signal ***
[pkrvm7jw40e0xgp:12398] Signal: Aborted (6)
[pkrvm7jw40e0xgp:12398] Signal code:  (-6)
[pkrvm7jw40e0xgp:12398] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa94de45330]
[pkrvm7jw40e0xgp:12398] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa94de9eb2c]
[pkrvm7jw40e0xgp:12398] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa94de4527e]
[pkrvm7jw40e0xgp:12398] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa94de288ff]
[pkrvm7jw40e0xgp:12398] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa94e2a5ff5]
[pkrvm7jw40e0xgp:12398] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa94e2bb0da]
[pkrvm7jw40e0xgp:12398] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa94e2a5a55]
[pkrvm7jw40e0xgp:12398] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa94e2a5a6f]
[pkrvm7jw40e0xgp:12398] [ 8] plumed(+0x146dd)[0x55766fea36dd]
[pkrvm7jw40e0xgp:12398] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa94de2a1ca]
[pkrvm7jw40e0xgp:12398] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa94de2a28b]
[pkrvm7jw40e0xgp:12398] [11] plumed(+0x15365)[0x55766fea4365]
[pkrvm7jw40e0xgp:12398] *** End of error message ***
</pre>
{% endraw %}
