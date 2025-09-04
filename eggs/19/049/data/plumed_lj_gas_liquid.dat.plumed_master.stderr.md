**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_lj_gas_liquid.dat   
Download: [zipped raw stdout](plumed_lj_gas_liquid.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_lj_gas_liquid.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs : keyword ARG is compulsory for this action
[pkrvm7jw40e0xgp:11914] *** Process received signal ***
[pkrvm7jw40e0xgp:11914] Signal: Aborted (6)
[pkrvm7jw40e0xgp:11914] Signal code:  (-6)
[pkrvm7jw40e0xgp:11914] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f26b4645330]
[pkrvm7jw40e0xgp:11914] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f26b469eb2c]
[pkrvm7jw40e0xgp:11914] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f26b464527e]
[pkrvm7jw40e0xgp:11914] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f26b46288ff]
[pkrvm7jw40e0xgp:11914] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f26b4aa5ff5]
[pkrvm7jw40e0xgp:11914] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f26b4abb0da]
[pkrvm7jw40e0xgp:11914] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f26b4aa5a55]
[pkrvm7jw40e0xgp:11914] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f26b4aa5a6f]
[pkrvm7jw40e0xgp:11914] [ 8] plumed_master(+0x146dd)[0x55cfb67d86dd]
[pkrvm7jw40e0xgp:11914] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f26b462a1ca]
[pkrvm7jw40e0xgp:11914] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f26b462a28b]
[pkrvm7jw40e0xgp:11914] [11] plumed_master(+0x15365)[0x55cfb67d9365]
[pkrvm7jw40e0xgp:11914] *** End of error message ***
</pre>
{% endraw %}
