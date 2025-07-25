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
[pkrvmpptgkbjq6m:08853] *** Process received signal ***
[pkrvmpptgkbjq6m:08853] Signal: Aborted (6)
[pkrvmpptgkbjq6m:08853] Signal code:  (-6)
[pkrvmpptgkbjq6m:08853] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f941fc45330]
[pkrvmpptgkbjq6m:08853] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f941fc9eb2c]
[pkrvmpptgkbjq6m:08853] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f941fc4527e]
[pkrvmpptgkbjq6m:08853] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f941fc288ff]
[pkrvmpptgkbjq6m:08853] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f94200a5ff5]
[pkrvmpptgkbjq6m:08853] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f94200bb0da]
[pkrvmpptgkbjq6m:08853] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f94200a5a55]
[pkrvmpptgkbjq6m:08853] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f94200a5a6f]
[pkrvmpptgkbjq6m:08853] [ 8] plumed_master(+0x146dd)[0x555b94c886dd]
[pkrvmpptgkbjq6m:08853] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f941fc2a1ca]
[pkrvmpptgkbjq6m:08853] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f941fc2a28b]
[pkrvmpptgkbjq6m:08853] [11] plumed_master(+0x15365)[0x555b94c89365]
[pkrvmpptgkbjq6m:08853] *** End of error message ***
</pre>
{% endraw %}
