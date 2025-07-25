**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_forward.dat   
Download: [zipped raw stdout](plumed_Argon_forward.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_forward.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[pkrvmpptgkbjq6m:06792] *** Process received signal ***
[pkrvmpptgkbjq6m:06792] Signal: Aborted (6)
[pkrvmpptgkbjq6m:06792] Signal code:  (-6)
[pkrvmpptgkbjq6m:06792] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f77c3045330]
[pkrvmpptgkbjq6m:06792] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f77c309eb2c]
[pkrvmpptgkbjq6m:06792] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f77c304527e]
[pkrvmpptgkbjq6m:06792] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f77c30288ff]
[pkrvmpptgkbjq6m:06792] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f77c34a5ff5]
[pkrvmpptgkbjq6m:06792] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f77c34bb0da]
[pkrvmpptgkbjq6m:06792] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f77c34a5a55]
[pkrvmpptgkbjq6m:06792] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f77c34a5a6f]
[pkrvmpptgkbjq6m:06792] [ 8] plumed_master(+0x146dd)[0x5578246a86dd]
[pkrvmpptgkbjq6m:06792] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f77c302a1ca]
[pkrvmpptgkbjq6m:06792] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f77c302a28b]
[pkrvmpptgkbjq6m:06792] [11] plumed_master(+0x15365)[0x5578246a9365]
[pkrvmpptgkbjq6m:06792] *** End of error message ***
</pre>
{% endraw %}
