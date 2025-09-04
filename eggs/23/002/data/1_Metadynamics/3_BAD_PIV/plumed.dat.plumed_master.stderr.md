**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/3_BAD_PIV/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvm7jw40e0xgp:07649] *** Process received signal ***
[pkrvm7jw40e0xgp:07649] Signal: Aborted (6)
[pkrvm7jw40e0xgp:07649] Signal code:  (-6)
[pkrvm7jw40e0xgp:07649] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f72fb245330]
[pkrvm7jw40e0xgp:07649] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f72fb29eb2c]
[pkrvm7jw40e0xgp:07649] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f72fb24527e]
[pkrvm7jw40e0xgp:07649] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f72fb2288ff]
[pkrvm7jw40e0xgp:07649] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f72fb6a5ff5]
[pkrvm7jw40e0xgp:07649] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f72fb6bb0da]
[pkrvm7jw40e0xgp:07649] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f72fb6a5a55]
[pkrvm7jw40e0xgp:07649] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f72fb6a5a6f]
[pkrvm7jw40e0xgp:07649] [ 8] plumed_master(+0x146dd)[0x564383c536dd]
[pkrvm7jw40e0xgp:07649] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f72fb22a1ca]
[pkrvm7jw40e0xgp:07649] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f72fb22a28b]
[pkrvm7jw40e0xgp:07649] [11] plumed_master(+0x15365)[0x564383c54365]
[pkrvm7jw40e0xgp:07649] *** End of error message ***
</pre>
{% endraw %}
