**Project ID:** [plumID:23.016]({{ '/' | absolute_url }}eggs/23/016/)  
Stderr for source:  plumed_reweight_microsw_adr_bin.dat   
Download: [zipped raw stdout](plumed_reweight_microsw_adr_bin.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_microsw_adr_bin.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @167 : keyword ARG is compulsory for this action
[pkrvmpptgkbjq6m:07740] *** Process received signal ***
[pkrvmpptgkbjq6m:07740] Signal: Aborted (6)
[pkrvmpptgkbjq6m:07740] Signal code:  (-6)
[pkrvmpptgkbjq6m:07740] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7faf91a45330]
[pkrvmpptgkbjq6m:07740] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7faf91a9eb2c]
[pkrvmpptgkbjq6m:07740] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7faf91a4527e]
[pkrvmpptgkbjq6m:07740] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7faf91a288ff]
[pkrvmpptgkbjq6m:07740] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7faf91ea5ff5]
[pkrvmpptgkbjq6m:07740] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7faf91ebb0da]
[pkrvmpptgkbjq6m:07740] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7faf91ea5a55]
[pkrvmpptgkbjq6m:07740] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7faf91ea5a6f]
[pkrvmpptgkbjq6m:07740] [ 8] plumed_master(+0x146dd)[0x557d3488d6dd]
[pkrvmpptgkbjq6m:07740] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7faf91a2a1ca]
[pkrvmpptgkbjq6m:07740] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7faf91a2a28b]
[pkrvmpptgkbjq6m:07740] [11] plumed_master(+0x15365)[0x557d3488e365]
[pkrvmpptgkbjq6m:07740] *** End of error message ***
</pre>
{% endraw %}
