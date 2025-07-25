**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[pkrvmpptgkbjq6m:07770] *** Process received signal ***
[pkrvmpptgkbjq6m:07770] Signal: Aborted (6)
[pkrvmpptgkbjq6m:07770] Signal code:  (-6)
[pkrvmpptgkbjq6m:07770] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f17d7a45330]
[pkrvmpptgkbjq6m:07770] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f17d7a9eb2c]
[pkrvmpptgkbjq6m:07770] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f17d7a4527e]
[pkrvmpptgkbjq6m:07770] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f17d7a288ff]
[pkrvmpptgkbjq6m:07770] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f17d7ea5ff5]
[pkrvmpptgkbjq6m:07770] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f17d7ebb0da]
[pkrvmpptgkbjq6m:07770] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f17d7ea5a55]
[pkrvmpptgkbjq6m:07770] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f17d7ea5a6f]
[pkrvmpptgkbjq6m:07770] [ 8] plumed_master(+0x146dd)[0x55d8ca7886dd]
[pkrvmpptgkbjq6m:07770] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f17d7a2a1ca]
[pkrvmpptgkbjq6m:07770] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f17d7a2a28b]
[pkrvmpptgkbjq6m:07770] [11] plumed_master(+0x15365)[0x55d8ca789365]
[pkrvmpptgkbjq6m:07770] *** End of error message ***
</pre>
{% endraw %}
