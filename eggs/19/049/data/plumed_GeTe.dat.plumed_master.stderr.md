**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_GeTe.dat   
Download: [zipped raw stdout](plumed_GeTe.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_GeTe.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label cc_cmat : it was not possible to interpret atom name flq6
[pkrvm7jw40e0xgp:11873] *** Process received signal ***
[pkrvm7jw40e0xgp:11873] Signal: Aborted (6)
[pkrvm7jw40e0xgp:11873] Signal code:  (-6)
[pkrvm7jw40e0xgp:11873] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6a98645330]
[pkrvm7jw40e0xgp:11873] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6a9869eb2c]
[pkrvm7jw40e0xgp:11873] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6a9864527e]
[pkrvm7jw40e0xgp:11873] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6a986288ff]
[pkrvm7jw40e0xgp:11873] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6a98aa5ff5]
[pkrvm7jw40e0xgp:11873] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6a98abb0da]
[pkrvm7jw40e0xgp:11873] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6a98aa5a55]
[pkrvm7jw40e0xgp:11873] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6a98aa5a6f]
[pkrvm7jw40e0xgp:11873] [ 8] plumed_master(+0x146dd)[0x55e059cd66dd]
[pkrvm7jw40e0xgp:11873] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6a9862a1ca]
[pkrvm7jw40e0xgp:11873] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6a9862a28b]
[pkrvm7jw40e0xgp:11873] [11] plumed_master(+0x15365)[0x55e059cd7365]
[pkrvm7jw40e0xgp:11873] *** End of error message ***
</pre>
{% endraw %}
