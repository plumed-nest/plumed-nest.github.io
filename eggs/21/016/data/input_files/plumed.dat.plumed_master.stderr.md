**Project ID:** [plumID:21.016]({{ '/' | absolute_url }}eggs/21/016/)  
Stderr for source:  input_files/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label saxs : cannot understand the following words from the input line : SCALEINT=1
[pkrvmpptgkbjq6m:10689] *** Process received signal ***
[pkrvmpptgkbjq6m:10689] Signal: Aborted (6)
[pkrvmpptgkbjq6m:10689] Signal code:  (-6)
[pkrvmpptgkbjq6m:10689] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6086e45330]
[pkrvmpptgkbjq6m:10689] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6086e9eb2c]
[pkrvmpptgkbjq6m:10689] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6086e4527e]
[pkrvmpptgkbjq6m:10689] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6086e288ff]
[pkrvmpptgkbjq6m:10689] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f60872a5ff5]
[pkrvmpptgkbjq6m:10689] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f60872bb0da]
[pkrvmpptgkbjq6m:10689] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f60872a5a55]
[pkrvmpptgkbjq6m:10689] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f60872a5a6f]
[pkrvmpptgkbjq6m:10689] [ 8] plumed_master(+0x146dd)[0x55b7e44eb6dd]
[pkrvmpptgkbjq6m:10689] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6086e2a1ca]
[pkrvmpptgkbjq6m:10689] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6086e2a28b]
[pkrvmpptgkbjq6m:10689] [11] plumed_master(+0x15365)[0x55b7e44ec365]
[pkrvmpptgkbjq6m:10689] *** End of error message ***
</pre>
{% endraw %}
