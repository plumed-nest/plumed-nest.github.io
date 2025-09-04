**Project ID:** [plumID:23.004]({{ '/' | absolute_url }}eggs/23/004/)  
Stderr for source:  BiasedCoexistence/IceIII/1-distributions/3000bar-295K/CalculateOptimalSigma/IceIII/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @87 : keyword ARG is compulsory for this action
[pkrvm7jw40e0xgp:06987] *** Process received signal ***
[pkrvm7jw40e0xgp:06987] Signal: Aborted (6)
[pkrvm7jw40e0xgp:06987] Signal code:  (-6)
[pkrvm7jw40e0xgp:06987] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa4c3245330]
[pkrvm7jw40e0xgp:06987] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa4c329eb2c]
[pkrvm7jw40e0xgp:06987] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa4c324527e]
[pkrvm7jw40e0xgp:06987] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa4c32288ff]
[pkrvm7jw40e0xgp:06987] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa4c36a5ff5]
[pkrvm7jw40e0xgp:06987] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa4c36bb0da]
[pkrvm7jw40e0xgp:06987] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa4c36a5a55]
[pkrvm7jw40e0xgp:06987] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa4c36a5a6f]
[pkrvm7jw40e0xgp:06987] [ 8] plumed_master(+0x146dd)[0x564f77ac46dd]
[pkrvm7jw40e0xgp:06987] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa4c322a1ca]
[pkrvm7jw40e0xgp:06987] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa4c322a28b]
[pkrvm7jw40e0xgp:06987] [11] plumed_master(+0x15365)[0x564f77ac5365]
[pkrvm7jw40e0xgp:06987] *** End of error message ***
</pre>
{% endraw %}
