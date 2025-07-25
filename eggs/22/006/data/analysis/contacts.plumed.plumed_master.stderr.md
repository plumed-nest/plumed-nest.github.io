**Project ID:** [plumID:22.006]({{ '/' | absolute_url }}eggs/22/006/)  
Stderr for source:  analysis/contacts.plumed   
Download: [zipped raw stdout](contacts.plumed.plumed_master.stdout.txt.zip) - [zipped raw stderr](contacts.plumed.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @88 : keyword ARG is compulsory for this action
[pkrvmpptgkbjq6m:09532] *** Process received signal ***
[pkrvmpptgkbjq6m:09532] Signal: Aborted (6)
[pkrvmpptgkbjq6m:09532] Signal code:  (-6)
[pkrvmpptgkbjq6m:09532] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8d10e45330]
[pkrvmpptgkbjq6m:09532] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8d10e9eb2c]
[pkrvmpptgkbjq6m:09532] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8d10e4527e]
[pkrvmpptgkbjq6m:09532] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8d10e288ff]
[pkrvmpptgkbjq6m:09532] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8d112a5ff5]
[pkrvmpptgkbjq6m:09532] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8d112bb0da]
[pkrvmpptgkbjq6m:09532] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8d112a5a55]
[pkrvmpptgkbjq6m:09532] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8d112a5a6f]
[pkrvmpptgkbjq6m:09532] [ 8] plumed_master(+0x146dd)[0x562c9dce16dd]
[pkrvmpptgkbjq6m:09532] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8d10e2a1ca]
[pkrvmpptgkbjq6m:09532] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8d10e2a28b]
[pkrvmpptgkbjq6m:09532] [11] plumed_master(+0x15365)[0x562c9dce2365]
[pkrvmpptgkbjq6m:09532] *** End of error message ***
</pre>
{% endraw %}
