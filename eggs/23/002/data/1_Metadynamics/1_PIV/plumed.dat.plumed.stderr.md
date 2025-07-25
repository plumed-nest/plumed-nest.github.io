**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/1_PIV/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvmpptgkbjq6m:08785] *** Process received signal ***
[pkrvmpptgkbjq6m:08785] Signal: Aborted (6)
[pkrvmpptgkbjq6m:08785] Signal code:  (-6)
[pkrvmpptgkbjq6m:08785] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0afdc45330]
[pkrvmpptgkbjq6m:08785] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0afdc9eb2c]
[pkrvmpptgkbjq6m:08785] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0afdc4527e]
[pkrvmpptgkbjq6m:08785] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0afdc288ff]
[pkrvmpptgkbjq6m:08785] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0afe0a5ff5]
[pkrvmpptgkbjq6m:08785] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0afe0bb0da]
[pkrvmpptgkbjq6m:08785] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0afe0a5a55]
[pkrvmpptgkbjq6m:08785] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0afe0a5a6f]
[pkrvmpptgkbjq6m:08785] [ 8] plumed(+0x146dd)[0x560346adc6dd]
[pkrvmpptgkbjq6m:08785] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0afdc2a1ca]
[pkrvmpptgkbjq6m:08785] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0afdc2a28b]
[pkrvmpptgkbjq6m:08785] [11] plumed(+0x15365)[0x560346add365]
[pkrvmpptgkbjq6m:08785] *** End of error message ***
</pre>
{% endraw %}
