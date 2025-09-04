**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/3_BAD_PIV/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvm7jw40e0xgp:07633] *** Process received signal ***
[pkrvm7jw40e0xgp:07633] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07633] Signal code:  (-6)
[pkrvm7jw40e0xgp:07633] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1018045330]
[pkrvm7jw40e0xgp:07633] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f101809eb2c]
[pkrvm7jw40e0xgp:07633] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f101804527e]
[pkrvm7jw40e0xgp:07633] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f10180288ff]
[pkrvm7jw40e0xgp:07633] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f10184a5ff5]
[pkrvm7jw40e0xgp:07633] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f10184bb0da]
[pkrvm7jw40e0xgp:07633] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f10184a5a55]
[pkrvm7jw40e0xgp:07633] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f10184a5a6f]
[pkrvm7jw40e0xgp:07633] [ 8] plumed(+0x146dd)[0x559f348266dd]
[pkrvm7jw40e0xgp:07633] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f101802a1ca]
[pkrvm7jw40e0xgp:07633] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f101802a28b]
[pkrvm7jw40e0xgp:07633] [11] plumed(+0x15365)[0x559f34827365]
[pkrvm7jw40e0xgp:07633] *** End of error message ***
</pre>
{% endraw %}
