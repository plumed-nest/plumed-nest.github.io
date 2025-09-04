**Project ID:** [plumID:21.028]({{ '/' | absolute_url }}eggs/21/028/)  
Stderr for source:  hBromination/unbiased/reagents/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(tools/Keywords.cpp:483) void PLMD::Keywords::addFlag(std::string_view, bool, std::string_view)
+++ assertion failed: !defaultValue
the second argument to addFlag must be false COMPONENTS
[pkrvm7jw40e0xgp:12529] *** Process received signal ***
[pkrvm7jw40e0xgp:12529] Signal: Aborted (6)
[pkrvm7jw40e0xgp:12529] Signal code:  (-6)
[pkrvm7jw40e0xgp:12529] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2eb7645330]
[pkrvm7jw40e0xgp:12529] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2eb769eb2c]
[pkrvm7jw40e0xgp:12529] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2eb764527e]
[pkrvm7jw40e0xgp:12529] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2eb76288ff]
[pkrvm7jw40e0xgp:12529] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2eb7aa5ff5]
[pkrvm7jw40e0xgp:12529] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2eb7abb0da]
[pkrvm7jw40e0xgp:12529] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2eb7aa5a55]
[pkrvm7jw40e0xgp:12529] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2eb7aa5a6f]
[pkrvm7jw40e0xgp:12529] [ 8] plumed_master(+0x146dd)[0x5630056916dd]
[pkrvm7jw40e0xgp:12529] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2eb762a1ca]
[pkrvm7jw40e0xgp:12529] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2eb762a28b]
[pkrvm7jw40e0xgp:12529] [11] plumed_master(+0x15365)[0x563005692365]
[pkrvm7jw40e0xgp:12529] *** End of error message ***
</pre>
{% endraw %}
