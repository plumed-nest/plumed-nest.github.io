**Project ID:** [plumID:19.050]({{ '/' | absolute_url }}eggs/19/050/)  
Stderr for source:  plumed_histogram.dat   
Download: [zipped raw stdout](plumed_histogram.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_histogram.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @32 : keyword ARG is compulsory for this action
[pkrvmpptgkbjq6m:13146] *** Process received signal ***
[pkrvmpptgkbjq6m:13146] Signal: Aborted (6)
[pkrvmpptgkbjq6m:13146] Signal code:  (-6)
[pkrvmpptgkbjq6m:13146] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5829c45330]
[pkrvmpptgkbjq6m:13146] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5829c9eb2c]
[pkrvmpptgkbjq6m:13146] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5829c4527e]
[pkrvmpptgkbjq6m:13146] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5829c288ff]
[pkrvmpptgkbjq6m:13146] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f582a0a5ff5]
[pkrvmpptgkbjq6m:13146] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f582a0bb0da]
[pkrvmpptgkbjq6m:13146] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f582a0a5a55]
[pkrvmpptgkbjq6m:13146] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f582a0a5a6f]
[pkrvmpptgkbjq6m:13146] [ 8] plumed_master(+0x146dd)[0x5602ad27f6dd]
[pkrvmpptgkbjq6m:13146] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5829c2a1ca]
[pkrvmpptgkbjq6m:13146] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5829c2a28b]
[pkrvmpptgkbjq6m:13146] [11] plumed_master(+0x15365)[0x5602ad280365]
[pkrvmpptgkbjq6m:13146] *** End of error message ***
</pre>
{% endraw %}
