**Project ID:** [plumID:20.000]({{ '/' | absolute_url }}eggs/20/000/)  
Stderr for source:  reweighting/reweighting.dat   
Download: [zipped raw stdout](reweighting.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweighting.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @17 : keyword ARG is compulsory for this action
[pkrvmpptgkbjq6m:12737] *** Process received signal ***
[pkrvmpptgkbjq6m:12737] Signal: Aborted (6)
[pkrvmpptgkbjq6m:12737] Signal code:  (-6)
[pkrvmpptgkbjq6m:12737] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe8fd045330]
[pkrvmpptgkbjq6m:12737] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe8fd09eb2c]
[pkrvmpptgkbjq6m:12737] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe8fd04527e]
[pkrvmpptgkbjq6m:12737] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe8fd0288ff]
[pkrvmpptgkbjq6m:12737] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe8fd4a5ff5]
[pkrvmpptgkbjq6m:12737] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe8fd4bb0da]
[pkrvmpptgkbjq6m:12737] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe8fd4a5a55]
[pkrvmpptgkbjq6m:12737] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe8fd4a5a6f]
[pkrvmpptgkbjq6m:12737] [ 8] plumed_master(+0x146dd)[0x55c71eaa56dd]
[pkrvmpptgkbjq6m:12737] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe8fd02a1ca]
[pkrvmpptgkbjq6m:12737] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe8fd02a28b]
[pkrvmpptgkbjq6m:12737] [11] plumed_master(+0x15365)[0x55c71eaa6365]
[pkrvmpptgkbjq6m:12737] *** End of error message ***
</pre>
{% endraw %}
