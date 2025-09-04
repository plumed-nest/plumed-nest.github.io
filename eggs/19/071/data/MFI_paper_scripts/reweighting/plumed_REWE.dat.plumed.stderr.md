**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/reweighting/plumed_REWE.dat   
Download: [zipped raw stdout](plumed_REWE.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_REWE.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : cannot understand the following words from the input line : REWEIGHTING_NGRID=200, REWEIGHTING_NHILLS=10
[pkrvm7jw40e0xgp:13019] *** Process received signal ***
[pkrvm7jw40e0xgp:13019] Signal: Aborted (6)
[pkrvm7jw40e0xgp:13019] Signal code:  (-6)
[pkrvm7jw40e0xgp:13019] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa228045330]
[pkrvm7jw40e0xgp:13019] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa22809eb2c]
[pkrvm7jw40e0xgp:13019] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa22804527e]
[pkrvm7jw40e0xgp:13019] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa2280288ff]
[pkrvm7jw40e0xgp:13019] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa2284a5ff5]
[pkrvm7jw40e0xgp:13019] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa2284bb0da]
[pkrvm7jw40e0xgp:13019] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa2284a5a55]
[pkrvm7jw40e0xgp:13019] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa2284a5a6f]
[pkrvm7jw40e0xgp:13019] [ 8] plumed(+0x146dd)[0x563835e9f6dd]
[pkrvm7jw40e0xgp:13019] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa22802a1ca]
[pkrvm7jw40e0xgp:13019] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa22802a28b]
[pkrvm7jw40e0xgp:13019] [11] plumed(+0x15365)[0x563835ea0365]
[pkrvm7jw40e0xgp:13019] *** End of error message ***
</pre>
{% endraw %}
