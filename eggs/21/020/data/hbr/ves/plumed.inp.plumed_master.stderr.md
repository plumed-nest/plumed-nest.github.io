**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/ves/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @51 : keyword ARG is compulsory for this action
[pkrvmpptgkbjq6m:10327] *** Process received signal ***
[pkrvmpptgkbjq6m:10327] Signal: Aborted (6)
[pkrvmpptgkbjq6m:10327] Signal code:  (-6)
[pkrvmpptgkbjq6m:10327] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f497d445330]
[pkrvmpptgkbjq6m:10327] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f497d49eb2c]
[pkrvmpptgkbjq6m:10327] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f497d44527e]
[pkrvmpptgkbjq6m:10327] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f497d4288ff]
[pkrvmpptgkbjq6m:10327] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f497d8a5ff5]
[pkrvmpptgkbjq6m:10327] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f497d8bb0da]
[pkrvmpptgkbjq6m:10327] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f497d8a5a55]
[pkrvmpptgkbjq6m:10327] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f497d8a5a6f]
[pkrvmpptgkbjq6m:10327] [ 8] plumed_master(+0x146dd)[0x55dd76c546dd]
[pkrvmpptgkbjq6m:10327] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f497d42a1ca]
[pkrvmpptgkbjq6m:10327] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f497d42a28b]
[pkrvmpptgkbjq6m:10327] [11] plumed_master(+0x15365)[0x55dd76c55365]
[pkrvmpptgkbjq6m:10327] *** End of error message ***
</pre>
{% endraw %}
