**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_get_weights.dat   
Download: [zipped raw stdout](plumed_get_weights.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_get_weights.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[pkrvm7jw40e0xgp:08345] *** Process received signal ***
[pkrvm7jw40e0xgp:08345] Signal: Aborted (6)
[pkrvm7jw40e0xgp:08345] Signal code:  (-6)
[pkrvm7jw40e0xgp:08345] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa91ca45330]
[pkrvm7jw40e0xgp:08345] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa91ca9eb2c]
[pkrvm7jw40e0xgp:08345] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa91ca4527e]
[pkrvm7jw40e0xgp:08345] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa91ca288ff]
[pkrvm7jw40e0xgp:08345] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa91cea5ff5]
[pkrvm7jw40e0xgp:08345] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa91cebb0da]
[pkrvm7jw40e0xgp:08345] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa91cea5a55]
[pkrvm7jw40e0xgp:08345] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa91cea5a6f]
[pkrvm7jw40e0xgp:08345] [ 8] plumed(+0x146dd)[0x5568091cc6dd]
[pkrvm7jw40e0xgp:08345] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa91ca2a1ca]
[pkrvm7jw40e0xgp:08345] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa91ca2a28b]
[pkrvm7jw40e0xgp:08345] [11] plumed(+0x15365)[0x5568091cd365]
[pkrvm7jw40e0xgp:08345] *** End of error message ***
</pre>
{% endraw %}
