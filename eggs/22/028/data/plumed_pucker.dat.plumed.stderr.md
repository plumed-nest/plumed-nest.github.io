**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[pkrvm7jw40e0xgp:08159] *** Process received signal ***
[pkrvm7jw40e0xgp:08159] Signal: Aborted (6)
[pkrvm7jw40e0xgp:08159] Signal code:  (-6)
[pkrvm7jw40e0xgp:08159] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f11a2645330]
[pkrvm7jw40e0xgp:08159] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f11a269eb2c]
[pkrvm7jw40e0xgp:08159] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f11a264527e]
[pkrvm7jw40e0xgp:08159] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f11a26288ff]
[pkrvm7jw40e0xgp:08159] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f11a2aa5ff5]
[pkrvm7jw40e0xgp:08159] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f11a2abb0da]
[pkrvm7jw40e0xgp:08159] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f11a2aa5a55]
[pkrvm7jw40e0xgp:08159] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f11a2aa5a6f]
[pkrvm7jw40e0xgp:08159] [ 8] plumed(+0x146dd)[0x55affd8b46dd]
[pkrvm7jw40e0xgp:08159] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f11a262a1ca]
[pkrvm7jw40e0xgp:08159] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f11a262a28b]
[pkrvm7jw40e0xgp:08159] [11] plumed(+0x15365)[0x55affd8b5365]
[pkrvm7jw40e0xgp:08159] *** End of error message ***
</pre>
{% endraw %}
