**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/4_Q6/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action LOCAL_AVERAGE with label @s28 : cannot understand the following words from the input line : LOWMEM
[pkrvm7jw40e0xgp:07684] *** Process received signal ***
[pkrvm7jw40e0xgp:07684] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07684] Signal code:  (-6)
[pkrvm7jw40e0xgp:07684] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f715e245330]
[pkrvm7jw40e0xgp:07684] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f715e29eb2c]
[pkrvm7jw40e0xgp:07684] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f715e24527e]
[pkrvm7jw40e0xgp:07684] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f715e2288ff]
[pkrvm7jw40e0xgp:07684] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f715e6a5ff5]
[pkrvm7jw40e0xgp:07684] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f715e6bb0da]
[pkrvm7jw40e0xgp:07684] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f715e6a5a55]
[pkrvm7jw40e0xgp:07684] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f715e6a5a6f]
[pkrvm7jw40e0xgp:07684] [ 8] plumed(+0x146dd)[0x56000c7226dd]
[pkrvm7jw40e0xgp:07684] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f715e22a1ca]
[pkrvm7jw40e0xgp:07684] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f715e22a28b]
[pkrvm7jw40e0xgp:07684] [11] plumed(+0x15365)[0x56000c723365]
[pkrvm7jw40e0xgp:07684] *** End of error message ***
</pre>
{% endraw %}
