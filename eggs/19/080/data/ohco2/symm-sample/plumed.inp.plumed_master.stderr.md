**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  ohco2/symm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[pkrvm7jw40e0xgp:11270] *** Process received signal ***
[pkrvm7jw40e0xgp:11270] Signal: Aborted (6)
[pkrvm7jw40e0xgp:11270] Signal code:  (-6)
[pkrvm7jw40e0xgp:11270] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9bd6645330]
[pkrvm7jw40e0xgp:11270] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9bd669eb2c]
[pkrvm7jw40e0xgp:11270] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9bd664527e]
[pkrvm7jw40e0xgp:11270] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9bd66288ff]
[pkrvm7jw40e0xgp:11270] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9bd6aa5ff5]
[pkrvm7jw40e0xgp:11270] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9bd6abb0da]
[pkrvm7jw40e0xgp:11270] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9bd6aa5a55]
[pkrvm7jw40e0xgp:11270] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9bd6aa5a6f]
[pkrvm7jw40e0xgp:11270] [ 8] plumed_master(+0x146dd)[0x564de48ca6dd]
[pkrvm7jw40e0xgp:11270] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9bd662a1ca]
[pkrvm7jw40e0xgp:11270] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9bd662a28b]
[pkrvm7jw40e0xgp:11270] [11] plumed_master(+0x15365)[0x564de48cb365]
[pkrvm7jw40e0xgp:11270] *** End of error message ***
</pre>
{% endraw %}
