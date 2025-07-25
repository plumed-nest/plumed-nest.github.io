**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s10 : missing input file ice.pdb
[pkrvmpptgkbjq6m:08660] *** Process received signal ***
[pkrvmpptgkbjq6m:08660] Signal: Aborted (6)
[pkrvmpptgkbjq6m:08660] Signal code:  (-6)
[pkrvmpptgkbjq6m:08660] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f42d7e45330]
[pkrvmpptgkbjq6m:08660] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f42d7e9eb2c]
[pkrvmpptgkbjq6m:08660] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f42d7e4527e]
[pkrvmpptgkbjq6m:08660] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f42d7e288ff]
[pkrvmpptgkbjq6m:08660] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f42d82a5ff5]
[pkrvmpptgkbjq6m:08660] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f42d82bb0da]
[pkrvmpptgkbjq6m:08660] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f42d82a5a55]
[pkrvmpptgkbjq6m:08660] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f42d82a5a6f]
[pkrvmpptgkbjq6m:08660] [ 8] plumed(+0x146dd)[0x55a0c14a46dd]
[pkrvmpptgkbjq6m:08660] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f42d7e2a1ca]
[pkrvmpptgkbjq6m:08660] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f42d7e2a28b]
[pkrvmpptgkbjq6m:08660] [11] plumed(+0x15365)[0x55a0c14a5365]
[pkrvmpptgkbjq6m:08660] *** End of error message ***
</pre>
{% endraw %}
