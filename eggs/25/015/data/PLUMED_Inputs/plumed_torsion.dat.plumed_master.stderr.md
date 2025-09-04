**Project ID:** [plumID:25.015]({{ '/' | absolute_url }}eggs/25/015/)  
Stderr for source:  PLUMED_Inputs/plumed_torsion.dat   
Download: [zipped raw stdout](plumed_torsion.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_torsion.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPATOMS with label @6 : it was not possible to interpret atom name t1_grp
[pkrvm7jw40e0xgp:05771] *** Process received signal ***
[pkrvm7jw40e0xgp:05771] Signal: Aborted (6)
[pkrvm7jw40e0xgp:05771] Signal code:  (-6)
[pkrvm7jw40e0xgp:05771] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fef4c245330]
[pkrvm7jw40e0xgp:05771] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fef4c29eb2c]
[pkrvm7jw40e0xgp:05771] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fef4c24527e]
[pkrvm7jw40e0xgp:05771] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fef4c2288ff]
[pkrvm7jw40e0xgp:05771] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fef4c6a5ff5]
[pkrvm7jw40e0xgp:05771] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fef4c6bb0da]
[pkrvm7jw40e0xgp:05771] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fef4c6a5a55]
[pkrvm7jw40e0xgp:05771] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fef4c6a5a6f]
[pkrvm7jw40e0xgp:05771] [ 8] plumed_master(+0x146dd)[0x5590aed236dd]
[pkrvm7jw40e0xgp:05771] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fef4c22a1ca]
[pkrvm7jw40e0xgp:05771] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fef4c22a28b]
[pkrvm7jw40e0xgp:05771] [11] plumed_master(+0x15365)[0x5590aed24365]
[pkrvm7jw40e0xgp:05771] *** End of error message ***
</pre>
{% endraw %}
