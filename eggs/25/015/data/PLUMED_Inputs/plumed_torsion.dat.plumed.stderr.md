**Project ID:** [plumID:25.015]({{ '/' | absolute_url }}eggs/25/015/)  
Stderr for source:  PLUMED_Inputs/plumed_torsion.dat   
Download: [zipped raw stdout](plumed_torsion.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_torsion.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPATOMS with label @6 : it was not possible to interpret atom name t1_grp
[pkrvm7jw40e0xgp:05755] *** Process received signal ***
[pkrvm7jw40e0xgp:05755] Signal: Aborted (6)
[pkrvm7jw40e0xgp:05755] Signal code:  (-6)
[pkrvm7jw40e0xgp:05755] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff6c5245330]
[pkrvm7jw40e0xgp:05755] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff6c529eb2c]
[pkrvm7jw40e0xgp:05755] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff6c524527e]
[pkrvm7jw40e0xgp:05755] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff6c52288ff]
[pkrvm7jw40e0xgp:05755] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff6c56a5ff5]
[pkrvm7jw40e0xgp:05755] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff6c56bb0da]
[pkrvm7jw40e0xgp:05755] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff6c56a5a55]
[pkrvm7jw40e0xgp:05755] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff6c56a5a6f]
[pkrvm7jw40e0xgp:05755] [ 8] plumed(+0x146dd)[0x55b0e68946dd]
[pkrvm7jw40e0xgp:05755] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff6c522a1ca]
[pkrvm7jw40e0xgp:05755] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff6c522a28b]
[pkrvm7jw40e0xgp:05755] [11] plumed(+0x15365)[0x55b0e6895365]
[pkrvm7jw40e0xgp:05755] *** End of error message ***
</pre>
{% endraw %}
