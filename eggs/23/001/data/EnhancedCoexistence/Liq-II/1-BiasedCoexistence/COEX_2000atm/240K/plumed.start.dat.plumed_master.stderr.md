**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[pkrvmpptgkbjq6m:08829] *** Process received signal ***
[pkrvmpptgkbjq6m:08829] Signal: Aborted (6)
[pkrvmpptgkbjq6m:08829] Signal code:  (-6)
[pkrvmpptgkbjq6m:08829] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f868a445330]
[pkrvmpptgkbjq6m:08829] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f868a49eb2c]
[pkrvmpptgkbjq6m:08829] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f868a44527e]
[pkrvmpptgkbjq6m:08829] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f868a4288ff]
[pkrvmpptgkbjq6m:08829] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f868a8a5ff5]
[pkrvmpptgkbjq6m:08829] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f868a8bb0da]
[pkrvmpptgkbjq6m:08829] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f868a8a5a55]
[pkrvmpptgkbjq6m:08829] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f868a8a5a6f]
[pkrvmpptgkbjq6m:08829] [ 8] plumed_master(+0x146dd)[0x561b6ed406dd]
[pkrvmpptgkbjq6m:08829] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f868a42a1ca]
[pkrvmpptgkbjq6m:08829] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f868a42a28b]
[pkrvmpptgkbjq6m:08829] [11] plumed_master(+0x15365)[0x561b6ed41365]
[pkrvmpptgkbjq6m:08829] *** End of error message ***
</pre>
{% endraw %}
