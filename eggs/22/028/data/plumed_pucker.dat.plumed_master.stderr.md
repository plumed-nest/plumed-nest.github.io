**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[pkrvm7jw40e0xgp:08176] *** Process received signal ***
[pkrvm7jw40e0xgp:08176] Signal: Aborted (6)
[pkrvm7jw40e0xgp:08176] Signal code:  (-6)
[pkrvm7jw40e0xgp:08176] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f707d845330]
[pkrvm7jw40e0xgp:08176] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f707d89eb2c]
[pkrvm7jw40e0xgp:08176] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f707d84527e]
[pkrvm7jw40e0xgp:08176] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f707d8288ff]
[pkrvm7jw40e0xgp:08176] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f707dca5ff5]
[pkrvm7jw40e0xgp:08176] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f707dcbb0da]
[pkrvm7jw40e0xgp:08176] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f707dca5a55]
[pkrvm7jw40e0xgp:08176] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f707dca5a6f]
[pkrvm7jw40e0xgp:08176] [ 8] plumed_master(+0x146dd)[0x55885e5456dd]
[pkrvm7jw40e0xgp:08176] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f707d82a1ca]
[pkrvm7jw40e0xgp:08176] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f707d82a28b]
[pkrvm7jw40e0xgp:08176] [11] plumed_master(+0x15365)[0x55885e546365]
[pkrvm7jw40e0xgp:08176] *** End of error message ***
</pre>
{% endraw %}
