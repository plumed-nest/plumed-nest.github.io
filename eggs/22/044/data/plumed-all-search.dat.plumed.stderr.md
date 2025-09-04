**Project ID:** [plumID:22.044]({{ '/' | absolute_url }}eggs/22/044/)  
Stderr for source:  plumed-all-search.dat   
Download: [zipped raw stdout](plumed-all-search.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-all-search.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label laq4_mat : problem reading switching function description found the following rogue keywords in switching function input : RATIONAL
[pkrvm7jw40e0xgp:07758] *** Process received signal ***
[pkrvm7jw40e0xgp:07758] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07758] Signal code:  (-6)
[pkrvm7jw40e0xgp:07758] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f41b8045330]
[pkrvm7jw40e0xgp:07758] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f41b809eb2c]
[pkrvm7jw40e0xgp:07758] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f41b804527e]
[pkrvm7jw40e0xgp:07758] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f41b80288ff]
[pkrvm7jw40e0xgp:07758] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f41b84a5ff5]
[pkrvm7jw40e0xgp:07758] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f41b84bb0da]
[pkrvm7jw40e0xgp:07758] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f41b84a5a55]
[pkrvm7jw40e0xgp:07758] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f41b84a5a6f]
[pkrvm7jw40e0xgp:07758] [ 8] plumed(+0x146dd)[0x55bae16a96dd]
[pkrvm7jw40e0xgp:07758] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f41b802a1ca]
[pkrvm7jw40e0xgp:07758] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f41b802a28b]
[pkrvm7jw40e0xgp:07758] [11] plumed(+0x15365)[0x55bae16aa365]
[pkrvm7jw40e0xgp:07758] *** End of error message ***
</pre>
{% endraw %}
