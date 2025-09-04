**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_get_weights.dat   
Download: [zipped raw stdout](plumed_get_weights.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_get_weights.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[pkrvm7jw40e0xgp:08361] *** Process received signal ***
[pkrvm7jw40e0xgp:08361] Signal: Aborted (6)
[pkrvm7jw40e0xgp:08361] Signal code:  (-6)
[pkrvm7jw40e0xgp:08361] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6ed2c45330]
[pkrvm7jw40e0xgp:08361] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6ed2c9eb2c]
[pkrvm7jw40e0xgp:08361] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6ed2c4527e]
[pkrvm7jw40e0xgp:08361] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6ed2c288ff]
[pkrvm7jw40e0xgp:08361] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6ed30a5ff5]
[pkrvm7jw40e0xgp:08361] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6ed30bb0da]
[pkrvm7jw40e0xgp:08361] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6ed30a5a55]
[pkrvm7jw40e0xgp:08361] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6ed30a5a6f]
[pkrvm7jw40e0xgp:08361] [ 8] plumed_master(+0x146dd)[0x556523a746dd]
[pkrvm7jw40e0xgp:08361] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6ed2c2a1ca]
[pkrvm7jw40e0xgp:08361] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6ed2c2a28b]
[pkrvm7jw40e0xgp:08361] [11] plumed_master(+0x15365)[0x556523a75365]
[pkrvm7jw40e0xgp:08361] *** End of error message ***
</pre>
{% endraw %}
