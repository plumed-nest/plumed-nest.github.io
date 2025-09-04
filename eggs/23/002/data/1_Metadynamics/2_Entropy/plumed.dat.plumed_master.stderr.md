**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/2_Entropy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvm7jw40e0xgp:07598] *** Process received signal ***
[pkrvm7jw40e0xgp:07598] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07598] Signal code:  (-6)
[pkrvm7jw40e0xgp:07598] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcfe4245330]
[pkrvm7jw40e0xgp:07598] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcfe429eb2c]
[pkrvm7jw40e0xgp:07598] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcfe424527e]
[pkrvm7jw40e0xgp:07598] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcfe42288ff]
[pkrvm7jw40e0xgp:07598] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcfe46a5ff5]
[pkrvm7jw40e0xgp:07598] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcfe46bb0da]
[pkrvm7jw40e0xgp:07598] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcfe46a5a55]
[pkrvm7jw40e0xgp:07598] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcfe46a5a6f]
[pkrvm7jw40e0xgp:07598] [ 8] plumed_master(+0x146dd)[0x556c12b296dd]
[pkrvm7jw40e0xgp:07598] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcfe422a1ca]
[pkrvm7jw40e0xgp:07598] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcfe422a28b]
[pkrvm7jw40e0xgp:07598] [11] plumed_master(+0x15365)[0x556c12b2a365]
[pkrvm7jw40e0xgp:07598] *** End of error message ***
</pre>
{% endraw %}
