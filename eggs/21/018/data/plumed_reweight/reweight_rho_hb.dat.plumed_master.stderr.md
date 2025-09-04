**Project ID:** [plumID:21.018]({{ '/' | absolute_url }}eggs/21/018/)  
Stderr for source:  plumed_reweight/reweight_rho_hb.dat   
Download: [zipped raw stdout](reweight_rho_hb.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweight_rho_hb.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
WARNING: IFile closed in the middle of reading. seems strange!
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @33 : keyword ARG is compulsory for this action
[pkrvm7jw40e0xgp:11840] *** Process received signal ***
[pkrvm7jw40e0xgp:11840] Signal: Aborted (6)
[pkrvm7jw40e0xgp:11840] Signal code:  (-6)
[pkrvm7jw40e0xgp:11840] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7feb78445330]
[pkrvm7jw40e0xgp:11840] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7feb7849eb2c]
[pkrvm7jw40e0xgp:11840] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7feb7844527e]
[pkrvm7jw40e0xgp:11840] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7feb784288ff]
[pkrvm7jw40e0xgp:11840] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7feb788a5ff5]
[pkrvm7jw40e0xgp:11840] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7feb788bb0da]
[pkrvm7jw40e0xgp:11840] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7feb788a5a55]
[pkrvm7jw40e0xgp:11840] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7feb788a5a6f]
[pkrvm7jw40e0xgp:11840] [ 8] plumed_master(+0x146dd)[0x55f6c1f736dd]
[pkrvm7jw40e0xgp:11840] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7feb7842a1ca]
[pkrvm7jw40e0xgp:11840] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7feb7842a28b]
[pkrvm7jw40e0xgp:11840] [11] plumed_master(+0x15365)[0x55f6c1f74365]
[pkrvm7jw40e0xgp:11840] *** End of error message ***
</pre>
{% endraw %}
