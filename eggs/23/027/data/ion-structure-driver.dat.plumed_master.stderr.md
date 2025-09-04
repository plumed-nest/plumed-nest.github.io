**Project ID:** [plumID:23.027]({{ '/' | absolute_url }}eggs/23/027/)  
Stderr for source:  ion-structure-driver.dat   
Download: [zipped raw stdout](ion-structure-driver.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](ion-structure-driver.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs0l : keyword ARG is compulsory for this action
[pkrvm7jw40e0xgp:07472] *** Process received signal ***
[pkrvm7jw40e0xgp:07472] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07472] Signal code:  (-6)
[pkrvm7jw40e0xgp:07472] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8fa4845330]
[pkrvm7jw40e0xgp:07472] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8fa489eb2c]
[pkrvm7jw40e0xgp:07472] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8fa484527e]
[pkrvm7jw40e0xgp:07472] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8fa48288ff]
[pkrvm7jw40e0xgp:07472] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8fa4ca5ff5]
[pkrvm7jw40e0xgp:07472] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8fa4cbb0da]
[pkrvm7jw40e0xgp:07472] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8fa4ca5a55]
[pkrvm7jw40e0xgp:07472] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8fa4ca5a6f]
[pkrvm7jw40e0xgp:07472] [ 8] plumed_master(+0x146dd)[0x55d95082c6dd]
[pkrvm7jw40e0xgp:07472] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8fa482a1ca]
[pkrvm7jw40e0xgp:07472] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8fa482a28b]
[pkrvm7jw40e0xgp:07472] [11] plumed_master(+0x15365)[0x55d95082d365]
[pkrvm7jw40e0xgp:07472] *** End of error message ***
</pre>
{% endraw %}
