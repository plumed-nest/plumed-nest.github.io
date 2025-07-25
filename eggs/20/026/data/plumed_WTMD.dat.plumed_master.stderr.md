**Project ID:** [plumID:20.026]({{ '/' | absolute_url }}eggs/20/026/)  
Stderr for source:  plumed_WTMD.dat   
Download: [zipped raw stdout](plumed_WTMD.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_WTMD.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @78 : keyword ARG is compulsory for this action
[pkrvmpptgkbjq6m:12517] *** Process received signal ***
[pkrvmpptgkbjq6m:12517] Signal: Aborted (6)
[pkrvmpptgkbjq6m:12517] Signal code:  (-6)
[pkrvmpptgkbjq6m:12517] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0d42e45330]
[pkrvmpptgkbjq6m:12517] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0d42e9eb2c]
[pkrvmpptgkbjq6m:12517] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0d42e4527e]
[pkrvmpptgkbjq6m:12517] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0d42e288ff]
[pkrvmpptgkbjq6m:12517] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0d432a5ff5]
[pkrvmpptgkbjq6m:12517] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0d432bb0da]
[pkrvmpptgkbjq6m:12517] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0d432a5a55]
[pkrvmpptgkbjq6m:12517] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0d432a5a6f]
[pkrvmpptgkbjq6m:12517] [ 8] plumed_master(+0x146dd)[0x56256d8ef6dd]
[pkrvmpptgkbjq6m:12517] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0d42e2a1ca]
[pkrvmpptgkbjq6m:12517] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0d42e2a28b]
[pkrvmpptgkbjq6m:12517] [11] plumed_master(+0x15365)[0x56256d8f0365]
[pkrvmpptgkbjq6m:12517] *** End of error message ***
</pre>
{% endraw %}
