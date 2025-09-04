**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_forward.dat   
Download: [zipped raw stdout](plumed_Argon_forward.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_forward.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[pkrvm7jw40e0xgp:08801] *** Process received signal ***
[pkrvm7jw40e0xgp:08801] Signal: Aborted (6)
[pkrvm7jw40e0xgp:08801] Signal code:  (-6)
[pkrvm7jw40e0xgp:08801] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0700845330]
[pkrvm7jw40e0xgp:08801] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f070089eb2c]
[pkrvm7jw40e0xgp:08801] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f070084527e]
[pkrvm7jw40e0xgp:08801] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f07008288ff]
[pkrvm7jw40e0xgp:08801] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0700ca5ff5]
[pkrvm7jw40e0xgp:08801] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0700cbb0da]
[pkrvm7jw40e0xgp:08801] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0700ca5a55]
[pkrvm7jw40e0xgp:08801] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0700ca5a6f]
[pkrvm7jw40e0xgp:08801] [ 8] plumed_master(+0x146dd)[0x563049fc16dd]
[pkrvm7jw40e0xgp:08801] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f070082a1ca]
[pkrvm7jw40e0xgp:08801] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f070082a28b]
[pkrvm7jw40e0xgp:08801] [11] plumed_master(+0x15365)[0x563049fc2365]
[pkrvm7jw40e0xgp:08801] *** End of error message ***
</pre>
{% endraw %}
