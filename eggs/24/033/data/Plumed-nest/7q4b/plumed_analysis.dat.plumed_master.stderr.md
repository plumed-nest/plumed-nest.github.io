**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action PRINT with label @333 : cannot use argument parabeta0_both.struct-1 in input as not all elements are computed
[pkrvm7jw40e0xgp:05985] *** Process received signal ***
[pkrvm7jw40e0xgp:05985] Signal: Aborted (6)
[pkrvm7jw40e0xgp:05985] Signal code:  (-6)
[pkrvm7jw40e0xgp:05985] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8db4e45330]
[pkrvm7jw40e0xgp:05985] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8db4e9eb2c]
[pkrvm7jw40e0xgp:05985] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8db4e4527e]
[pkrvm7jw40e0xgp:05985] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8db4e288ff]
[pkrvm7jw40e0xgp:05985] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8db52a5ff5]
[pkrvm7jw40e0xgp:05985] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8db52bb0da]
[pkrvm7jw40e0xgp:05985] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8db52a5a55]
[pkrvm7jw40e0xgp:05985] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8db52a5a6f]
[pkrvm7jw40e0xgp:05985] [ 8] plumed_master(+0x146dd)[0x55e531f1e6dd]
[pkrvm7jw40e0xgp:05985] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8db4e2a1ca]
[pkrvm7jw40e0xgp:05985] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8db4e2a28b]
[pkrvm7jw40e0xgp:05985] [11] plumed_master(+0x15365)[0x55e531f1f365]
[pkrvm7jw40e0xgp:05985] *** End of error message ***
</pre>
{% endraw %}
