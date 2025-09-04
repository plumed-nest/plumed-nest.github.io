**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-base/sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @28 : keyword ARG is compulsory for this action
[pkrvm7jw40e0xgp:10994] *** Process received signal ***
[pkrvm7jw40e0xgp:10994] Signal: Aborted (6)
[pkrvm7jw40e0xgp:10994] Signal code:  (-6)
[pkrvm7jw40e0xgp:10994] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fed83045330]
[pkrvm7jw40e0xgp:10994] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fed8309eb2c]
[pkrvm7jw40e0xgp:10994] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fed8304527e]
[pkrvm7jw40e0xgp:10994] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fed830288ff]
[pkrvm7jw40e0xgp:10994] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fed834a5ff5]
[pkrvm7jw40e0xgp:10994] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fed834bb0da]
[pkrvm7jw40e0xgp:10994] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fed834a5a55]
[pkrvm7jw40e0xgp:10994] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fed834a5a6f]
[pkrvm7jw40e0xgp:10994] [ 8] plumed_master(+0x146dd)[0x555a0da456dd]
[pkrvm7jw40e0xgp:10994] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fed8302a1ca]
[pkrvm7jw40e0xgp:10994] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fed8302a28b]
[pkrvm7jw40e0xgp:10994] [11] plumed_master(+0x15365)[0x555a0da46365]
[pkrvm7jw40e0xgp:10994] *** End of error message ***
</pre>
{% endraw %}
