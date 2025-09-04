**Project ID:** [plumID:19.032]({{ '/' | absolute_url }}eggs/19/032/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PDB2CONSTANT with label @s95 : argument O1O_lessthan was not set in pdb input
[pkrvm7jw40e0xgp:12264] *** Process received signal ***
[pkrvm7jw40e0xgp:12264] Signal: Aborted (6)
[pkrvm7jw40e0xgp:12264] Signal code:  (-6)
[pkrvm7jw40e0xgp:12264] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe3f6445330]
[pkrvm7jw40e0xgp:12264] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe3f649eb2c]
[pkrvm7jw40e0xgp:12264] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe3f644527e]
[pkrvm7jw40e0xgp:12264] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe3f64288ff]
[pkrvm7jw40e0xgp:12264] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe3f68a5ff5]
[pkrvm7jw40e0xgp:12264] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe3f68bb0da]
[pkrvm7jw40e0xgp:12264] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe3f68a5a55]
[pkrvm7jw40e0xgp:12264] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe3f68a5a6f]
[pkrvm7jw40e0xgp:12264] [ 8] plumed(+0x146dd)[0x5578afa316dd]
[pkrvm7jw40e0xgp:12264] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe3f642a1ca]
[pkrvm7jw40e0xgp:12264] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe3f642a28b]
[pkrvm7jw40e0xgp:12264] [11] plumed(+0x15365)[0x5578afa32365]
[pkrvm7jw40e0xgp:12264] *** End of error message ***
</pre>
{% endraw %}
