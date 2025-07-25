**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  h3/sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @32 : keyword ARG is compulsory for this action
[pkrvmpptgkbjq6m:11794] *** Process received signal ***
[pkrvmpptgkbjq6m:11794] Signal: Aborted (6)
[pkrvmpptgkbjq6m:11794] Signal code:  (-6)
[pkrvmpptgkbjq6m:11794] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f618f845330]
[pkrvmpptgkbjq6m:11794] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f618f89eb2c]
[pkrvmpptgkbjq6m:11794] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f618f84527e]
[pkrvmpptgkbjq6m:11794] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f618f8288ff]
[pkrvmpptgkbjq6m:11794] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f618fca5ff5]
[pkrvmpptgkbjq6m:11794] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f618fcbb0da]
[pkrvmpptgkbjq6m:11794] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f618fca5a55]
[pkrvmpptgkbjq6m:11794] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f618fca5a6f]
[pkrvmpptgkbjq6m:11794] [ 8] plumed_master(+0x146dd)[0x564c76f896dd]
[pkrvmpptgkbjq6m:11794] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f618f82a1ca]
[pkrvmpptgkbjq6m:11794] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f618f82a28b]
[pkrvmpptgkbjq6m:11794] [11] plumed_master(+0x15365)[0x564c76f8a365]
[pkrvmpptgkbjq6m:11794] *** End of error message ***
</pre>
{% endraw %}
