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
[pkrvmpptgkbjq6m:13238] *** Process received signal ***
[pkrvmpptgkbjq6m:13238] Signal: Aborted (6)
[pkrvmpptgkbjq6m:13238] Signal code:  (-6)
[pkrvmpptgkbjq6m:13238] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efd39c45330]
[pkrvmpptgkbjq6m:13238] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efd39c9eb2c]
[pkrvmpptgkbjq6m:13238] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efd39c4527e]
[pkrvmpptgkbjq6m:13238] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efd39c288ff]
[pkrvmpptgkbjq6m:13238] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efd3a0a5ff5]
[pkrvmpptgkbjq6m:13238] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efd3a0bb0da]
[pkrvmpptgkbjq6m:13238] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efd3a0a5a55]
[pkrvmpptgkbjq6m:13238] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efd3a0a5a6f]
[pkrvmpptgkbjq6m:13238] [ 8] plumed(+0x146dd)[0x559e63b476dd]
[pkrvmpptgkbjq6m:13238] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efd39c2a1ca]
[pkrvmpptgkbjq6m:13238] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efd39c2a28b]
[pkrvmpptgkbjq6m:13238] [11] plumed(+0x15365)[0x559e63b48365]
[pkrvmpptgkbjq6m:13238] *** End of error message ***
</pre>
{% endraw %}
