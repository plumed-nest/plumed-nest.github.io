**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4m/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action PRINT with label @252 : cannot use argument parabeta0_both.struct-1 in input as not all elements are computed
[pkrvmpptgkbjq6m:06551] *** Process received signal ***
[pkrvmpptgkbjq6m:06551] Signal: Aborted (6)
[pkrvmpptgkbjq6m:06551] Signal code:  (-6)
[pkrvmpptgkbjq6m:06551] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7faef7245330]
[pkrvmpptgkbjq6m:06551] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7faef729eb2c]
[pkrvmpptgkbjq6m:06551] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7faef724527e]
[pkrvmpptgkbjq6m:06551] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7faef72288ff]
[pkrvmpptgkbjq6m:06551] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7faef76a5ff5]
[pkrvmpptgkbjq6m:06551] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7faef76bb0da]
[pkrvmpptgkbjq6m:06551] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7faef76a5a55]
[pkrvmpptgkbjq6m:06551] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7faef76a5a6f]
[pkrvmpptgkbjq6m:06551] [ 8] plumed_master(+0x146dd)[0x55d5af40c6dd]
[pkrvmpptgkbjq6m:06551] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7faef722a1ca]
[pkrvmpptgkbjq6m:06551] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7faef722a28b]
[pkrvmpptgkbjq6m:06551] [11] plumed_master(+0x15365)[0x55d5af40d365]
[pkrvmpptgkbjq6m:06551] *** End of error message ***
</pre>
{% endraw %}
