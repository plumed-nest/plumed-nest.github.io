**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/bend-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @59 : keyword ARG is compulsory for this action
[pkrvm7jw40e0xgp:10354] *** Process received signal ***
[pkrvm7jw40e0xgp:10354] Signal: Aborted (6)
[pkrvm7jw40e0xgp:10354] Signal code:  (-6)
[pkrvm7jw40e0xgp:10354] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa8eb645330]
[pkrvm7jw40e0xgp:10354] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa8eb69eb2c]
[pkrvm7jw40e0xgp:10354] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa8eb64527e]
[pkrvm7jw40e0xgp:10354] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa8eb6288ff]
[pkrvm7jw40e0xgp:10354] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa8ebaa5ff5]
[pkrvm7jw40e0xgp:10354] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa8ebabb0da]
[pkrvm7jw40e0xgp:10354] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa8ebaa5a55]
[pkrvm7jw40e0xgp:10354] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa8ebaa5a6f]
[pkrvm7jw40e0xgp:10354] [ 8] plumed_master(+0x146dd)[0x55f9940e66dd]
[pkrvm7jw40e0xgp:10354] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa8eb62a1ca]
[pkrvm7jw40e0xgp:10354] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa8eb62a28b]
[pkrvm7jw40e0xgp:10354] [11] plumed_master(+0x15365)[0x55f9940e7365]
[pkrvm7jw40e0xgp:10354] *** End of error message ***
</pre>
{% endraw %}
