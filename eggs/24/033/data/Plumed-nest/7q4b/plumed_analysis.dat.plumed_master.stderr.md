**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action PRINT with label @333 : cannot use argument parabeta0_both.struct-1 in input as not all elements are computed
[pkrvmpptgkbjq6m:06394] *** Process received signal ***
[pkrvmpptgkbjq6m:06394] Signal: Aborted (6)
[pkrvmpptgkbjq6m:06394] Signal code:  (-6)
[pkrvmpptgkbjq6m:06394] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe6b6a45330]
[pkrvmpptgkbjq6m:06394] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe6b6a9eb2c]
[pkrvmpptgkbjq6m:06394] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe6b6a4527e]
[pkrvmpptgkbjq6m:06394] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe6b6a288ff]
[pkrvmpptgkbjq6m:06394] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe6b6ea5ff5]
[pkrvmpptgkbjq6m:06394] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe6b6ebb0da]
[pkrvmpptgkbjq6m:06394] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe6b6ea5a55]
[pkrvmpptgkbjq6m:06394] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe6b6ea5a6f]
[pkrvmpptgkbjq6m:06394] [ 8] plumed_master(+0x146dd)[0x55a96dc586dd]
[pkrvmpptgkbjq6m:06394] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe6b6a2a1ca]
[pkrvmpptgkbjq6m:06394] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe6b6a2a28b]
[pkrvmpptgkbjq6m:06394] [11] plumed_master(+0x15365)[0x55a96dc59365]
[pkrvmpptgkbjq6m:06394] *** End of error message ***
</pre>
{% endraw %}
