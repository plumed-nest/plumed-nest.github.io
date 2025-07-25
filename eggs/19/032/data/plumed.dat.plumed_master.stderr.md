**Project ID:** [plumID:19.032]({{ '/' | absolute_url }}eggs/19/032/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action PDB2CONSTANT with label @s83 : argument O1O_lessthan was not set in pdb input
[pkrvmpptgkbjq6m:13254] *** Process received signal ***
[pkrvmpptgkbjq6m:13254] Signal: Aborted (6)
[pkrvmpptgkbjq6m:13254] Signal code:  (-6)
[pkrvmpptgkbjq6m:13254] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8f55445330]
[pkrvmpptgkbjq6m:13254] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8f5549eb2c]
[pkrvmpptgkbjq6m:13254] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8f5544527e]
[pkrvmpptgkbjq6m:13254] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8f554288ff]
[pkrvmpptgkbjq6m:13254] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8f558a5ff5]
[pkrvmpptgkbjq6m:13254] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8f558bb0da]
[pkrvmpptgkbjq6m:13254] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8f558a5a55]
[pkrvmpptgkbjq6m:13254] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8f558a5a6f]
[pkrvmpptgkbjq6m:13254] [ 8] plumed_master(+0x146dd)[0x5559273f26dd]
[pkrvmpptgkbjq6m:13254] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8f5542a1ca]
[pkrvmpptgkbjq6m:13254] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8f5542a28b]
[pkrvmpptgkbjq6m:13254] [11] plumed_master(+0x15365)[0x5559273f3365]
[pkrvmpptgkbjq6m:13254] *** End of error message ***
</pre>
{% endraw %}
