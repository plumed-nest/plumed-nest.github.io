**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[pkrvmpptgkbjq6m:07754] *** Process received signal ***
[pkrvmpptgkbjq6m:07754] Signal: Aborted (6)
[pkrvmpptgkbjq6m:07754] Signal code:  (-6)
[pkrvmpptgkbjq6m:07754] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc0b2c45330]
[pkrvmpptgkbjq6m:07754] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc0b2c9eb2c]
[pkrvmpptgkbjq6m:07754] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc0b2c4527e]
[pkrvmpptgkbjq6m:07754] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc0b2c288ff]
[pkrvmpptgkbjq6m:07754] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc0b30a5ff5]
[pkrvmpptgkbjq6m:07754] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc0b30bb0da]
[pkrvmpptgkbjq6m:07754] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc0b30a5a55]
[pkrvmpptgkbjq6m:07754] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc0b30a5a6f]
[pkrvmpptgkbjq6m:07754] [ 8] plumed(+0x146dd)[0x5599de1a46dd]
[pkrvmpptgkbjq6m:07754] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc0b2c2a1ca]
[pkrvmpptgkbjq6m:07754] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc0b2c2a28b]
[pkrvmpptgkbjq6m:07754] [11] plumed(+0x15365)[0x5599de1a5365]
[pkrvmpptgkbjq6m:07754] *** End of error message ***
</pre>
{% endraw %}
