**Project ID:** [plumID:19.017]({{ '/' | absolute_url }}eggs/19/017/)  
Stderr for source:  plumed_reweight/reweight_rho_c.dat   
Download: [zipped raw stdout](reweight_rho_c.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweight_rho_c.dat.plumed_master.stderr.txt.zip) 
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
ERROR in input to action DUMPGRID with label @17 : keyword ARG is compulsory for this action
[pkrvm7jw40e0xgp:11410] *** Process received signal ***
[pkrvm7jw40e0xgp:11410] Signal: Aborted (6)
[pkrvm7jw40e0xgp:11410] Signal code:  (-6)
[pkrvm7jw40e0xgp:11410] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa997645330]
[pkrvm7jw40e0xgp:11410] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa99769eb2c]
[pkrvm7jw40e0xgp:11410] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa99764527e]
[pkrvm7jw40e0xgp:11410] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa9976288ff]
[pkrvm7jw40e0xgp:11410] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa997aa5ff5]
[pkrvm7jw40e0xgp:11410] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa997abb0da]
[pkrvm7jw40e0xgp:11410] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa997aa5a55]
[pkrvm7jw40e0xgp:11410] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa997aa5a6f]
[pkrvm7jw40e0xgp:11410] [ 8] plumed_master(+0x146dd)[0x5652899616dd]
[pkrvm7jw40e0xgp:11410] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa99762a1ca]
[pkrvm7jw40e0xgp:11410] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa99762a28b]
[pkrvm7jw40e0xgp:11410] [11] plumed_master(+0x15365)[0x565289962365]
[pkrvm7jw40e0xgp:11410] *** End of error message ***
</pre>
{% endraw %}
