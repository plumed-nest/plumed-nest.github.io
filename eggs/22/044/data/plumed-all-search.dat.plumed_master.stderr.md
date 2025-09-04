**Project ID:** [plumID:22.044]({{ '/' | absolute_url }}eggs/22/044/)  
Stderr for source:  plumed-all-search.dat   
Download: [zipped raw stdout](plumed-all-search.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-all-search.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label laq4_mat : problem reading switching function description found the following rogue keywords in switching function input : RATIONAL
[pkrvm7jw40e0xgp:07774] *** Process received signal ***
[pkrvm7jw40e0xgp:07774] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07774] Signal code:  (-6)
[pkrvm7jw40e0xgp:07774] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fefe4845330]
[pkrvm7jw40e0xgp:07774] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fefe489eb2c]
[pkrvm7jw40e0xgp:07774] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fefe484527e]
[pkrvm7jw40e0xgp:07774] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fefe48288ff]
[pkrvm7jw40e0xgp:07774] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fefe4ca5ff5]
[pkrvm7jw40e0xgp:07774] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fefe4cbb0da]
[pkrvm7jw40e0xgp:07774] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fefe4ca5a55]
[pkrvm7jw40e0xgp:07774] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fefe4ca5a6f]
[pkrvm7jw40e0xgp:07774] [ 8] plumed_master(+0x146dd)[0x5648ff4d76dd]
[pkrvm7jw40e0xgp:07774] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fefe482a1ca]
[pkrvm7jw40e0xgp:07774] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fefe482a28b]
[pkrvm7jw40e0xgp:07774] [11] plumed_master(+0x15365)[0x5648ff4d8365]
[pkrvm7jw40e0xgp:07774] *** End of error message ***
</pre>
{% endraw %}
