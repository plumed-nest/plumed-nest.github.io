**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/4_Q6/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action LOCAL_AVERAGE with label @s29 : cannot understand the following words from the input line : LOWMEM
[pkrvm7jw40e0xgp:07700] *** Process received signal ***
[pkrvm7jw40e0xgp:07700] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07700] Signal code:  (-6)
[pkrvm7jw40e0xgp:07700] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9b8be45330]
[pkrvm7jw40e0xgp:07700] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9b8be9eb2c]
[pkrvm7jw40e0xgp:07700] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9b8be4527e]
[pkrvm7jw40e0xgp:07700] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9b8be288ff]
[pkrvm7jw40e0xgp:07700] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9b8c2a5ff5]
[pkrvm7jw40e0xgp:07700] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9b8c2bb0da]
[pkrvm7jw40e0xgp:07700] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9b8c2a5a55]
[pkrvm7jw40e0xgp:07700] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9b8c2a5a6f]
[pkrvm7jw40e0xgp:07700] [ 8] plumed_master(+0x146dd)[0x5570483466dd]
[pkrvm7jw40e0xgp:07700] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9b8be2a1ca]
[pkrvm7jw40e0xgp:07700] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9b8be2a28b]
[pkrvm7jw40e0xgp:07700] [11] plumed_master(+0x15365)[0x557048347365]
[pkrvm7jw40e0xgp:07700] *** End of error message ***
</pre>
{% endraw %}
