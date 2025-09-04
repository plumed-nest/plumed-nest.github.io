**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  dimer/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @39 : keyword ARG is compulsory for this action
[pkrvm7jw40e0xgp:10335] *** Process received signal ***
[pkrvm7jw40e0xgp:10335] Signal: Aborted (6)
[pkrvm7jw40e0xgp:10335] Signal code:  (-6)
[pkrvm7jw40e0xgp:10335] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5e03645330]
[pkrvm7jw40e0xgp:10335] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5e0369eb2c]
[pkrvm7jw40e0xgp:10335] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5e0364527e]
[pkrvm7jw40e0xgp:10335] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5e036288ff]
[pkrvm7jw40e0xgp:10335] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5e03aa5ff5]
[pkrvm7jw40e0xgp:10335] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5e03abb0da]
[pkrvm7jw40e0xgp:10335] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5e03aa5a55]
[pkrvm7jw40e0xgp:10335] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5e03aa5a6f]
[pkrvm7jw40e0xgp:10335] [ 8] plumed_master(+0x146dd)[0x55b6c4b0d6dd]
[pkrvm7jw40e0xgp:10335] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5e0362a1ca]
[pkrvm7jw40e0xgp:10335] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5e0362a28b]
[pkrvm7jw40e0xgp:10335] [11] plumed_master(+0x15365)[0x55b6c4b0e365]
[pkrvm7jw40e0xgp:10335] *** End of error message ***
</pre>
{% endraw %}
