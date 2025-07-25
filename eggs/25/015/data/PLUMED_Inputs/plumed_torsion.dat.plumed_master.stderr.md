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
[pkrvmpptgkbjq6m:05640] *** Process received signal ***
[pkrvmpptgkbjq6m:05640] Signal: Aborted (6)
[pkrvmpptgkbjq6m:05640] Signal code:  (-6)
[pkrvmpptgkbjq6m:05640] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7289c45330]
[pkrvmpptgkbjq6m:05640] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7289c9eb2c]
[pkrvmpptgkbjq6m:05640] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7289c4527e]
[pkrvmpptgkbjq6m:05640] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7289c288ff]
[pkrvmpptgkbjq6m:05640] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f728a0a5ff5]
[pkrvmpptgkbjq6m:05640] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f728a0bb0da]
[pkrvmpptgkbjq6m:05640] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f728a0a5a55]
[pkrvmpptgkbjq6m:05640] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f728a0a5a6f]
[pkrvmpptgkbjq6m:05640] [ 8] plumed_master(+0x146dd)[0x55605229f6dd]
[pkrvmpptgkbjq6m:05640] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7289c2a1ca]
[pkrvmpptgkbjq6m:05640] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7289c2a28b]
[pkrvmpptgkbjq6m:05640] [11] plumed_master(+0x15365)[0x5560522a0365]
[pkrvmpptgkbjq6m:05640] *** End of error message ***
</pre>
{% endraw %}
