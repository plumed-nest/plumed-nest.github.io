**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_backward.dat   
Download: [zipped raw stdout](plumed_Argon_backward.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_backward.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[pkrvm7jw40e0xgp:08749] *** Process received signal ***
[pkrvm7jw40e0xgp:08749] Signal: Aborted (6)
[pkrvm7jw40e0xgp:08749] Signal code:  (-6)
[pkrvm7jw40e0xgp:08749] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f56d1445330]
[pkrvm7jw40e0xgp:08749] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f56d149eb2c]
[pkrvm7jw40e0xgp:08749] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f56d144527e]
[pkrvm7jw40e0xgp:08749] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f56d14288ff]
[pkrvm7jw40e0xgp:08749] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f56d18a5ff5]
[pkrvm7jw40e0xgp:08749] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f56d18bb0da]
[pkrvm7jw40e0xgp:08749] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f56d18a5a55]
[pkrvm7jw40e0xgp:08749] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f56d18a5a6f]
[pkrvm7jw40e0xgp:08749] [ 8] plumed_master(+0x146dd)[0x55cd849bd6dd]
[pkrvm7jw40e0xgp:08749] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f56d142a1ca]
[pkrvm7jw40e0xgp:08749] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f56d142a28b]
[pkrvm7jw40e0xgp:08749] [11] plumed_master(+0x15365)[0x55cd849be365]
[pkrvm7jw40e0xgp:08749] *** End of error message ***
</pre>
{% endraw %}
