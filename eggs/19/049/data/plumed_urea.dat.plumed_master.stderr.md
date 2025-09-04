**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX with label @s43 : missing SWITCH11 keyword
[pkrvm7jw40e0xgp:11962] *** Process received signal ***
[pkrvm7jw40e0xgp:11962] Signal: Aborted (6)
[pkrvm7jw40e0xgp:11962] Signal code:  (-6)
[pkrvm7jw40e0xgp:11962] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4887a45330]
[pkrvm7jw40e0xgp:11962] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4887a9eb2c]
[pkrvm7jw40e0xgp:11962] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4887a4527e]
[pkrvm7jw40e0xgp:11962] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4887a288ff]
[pkrvm7jw40e0xgp:11962] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4887ea5ff5]
[pkrvm7jw40e0xgp:11962] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4887ebb0da]
[pkrvm7jw40e0xgp:11962] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4887ea5a55]
[pkrvm7jw40e0xgp:11962] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4887ea5a6f]
[pkrvm7jw40e0xgp:11962] [ 8] plumed_master(+0x146dd)[0x5566f67306dd]
[pkrvm7jw40e0xgp:11962] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4887a2a1ca]
[pkrvm7jw40e0xgp:11962] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4887a2a28b]
[pkrvm7jw40e0xgp:11962] [11] plumed_master(+0x15365)[0x5566f6731365]
[pkrvm7jw40e0xgp:11962] *** End of error message ***
</pre>
{% endraw %}
