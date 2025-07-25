**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @51 : keyword ARG is compulsory for this action
[pkrvmpptgkbjq6m:10200] *** Process received signal ***
[pkrvmpptgkbjq6m:10200] Signal: Aborted (6)
[pkrvmpptgkbjq6m:10200] Signal code:  (-6)
[pkrvmpptgkbjq6m:10200] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5a60a45330]
[pkrvmpptgkbjq6m:10200] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5a60a9eb2c]
[pkrvmpptgkbjq6m:10200] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5a60a4527e]
[pkrvmpptgkbjq6m:10200] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5a60a288ff]
[pkrvmpptgkbjq6m:10200] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5a60ea5ff5]
[pkrvmpptgkbjq6m:10200] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5a60ebb0da]
[pkrvmpptgkbjq6m:10200] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5a60ea5a55]
[pkrvmpptgkbjq6m:10200] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5a60ea5a6f]
[pkrvmpptgkbjq6m:10200] [ 8] plumed_master(+0x146dd)[0x556ab75ff6dd]
[pkrvmpptgkbjq6m:10200] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5a60a2a1ca]
[pkrvmpptgkbjq6m:10200] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5a60a2a28b]
[pkrvmpptgkbjq6m:10200] [11] plumed_master(+0x15365)[0x556ab7600365]
[pkrvmpptgkbjq6m:10200] *** End of error message ***
</pre>
{% endraw %}
