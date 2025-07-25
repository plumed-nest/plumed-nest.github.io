**Project ID:** [plumID:22.044]({{ '/' | absolute_url }}eggs/22/044/)  
Stderr for source:  plumed-all-search.dat   
Download: [zipped raw stdout](plumed-all-search.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed-all-search.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label laq4_mat : problem reading switching function description found the following rogue keywords in switching function input : RATIONAL
[pkrvmpptgkbjq6m:09168] *** Process received signal ***
[pkrvmpptgkbjq6m:09168] Signal: Aborted (6)
[pkrvmpptgkbjq6m:09168] Signal code:  (-6)
[pkrvmpptgkbjq6m:09168] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff02f245330]
[pkrvmpptgkbjq6m:09168] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff02f29eb2c]
[pkrvmpptgkbjq6m:09168] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff02f24527e]
[pkrvmpptgkbjq6m:09168] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff02f2288ff]
[pkrvmpptgkbjq6m:09168] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff02f6a5ff5]
[pkrvmpptgkbjq6m:09168] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff02f6bb0da]
[pkrvmpptgkbjq6m:09168] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff02f6a5a55]
[pkrvmpptgkbjq6m:09168] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff02f6a5a6f]
[pkrvmpptgkbjq6m:09168] [ 8] plumed_master(+0x146dd)[0x5568bbd386dd]
[pkrvmpptgkbjq6m:09168] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff02f22a1ca]
[pkrvmpptgkbjq6m:09168] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff02f22a28b]
[pkrvmpptgkbjq6m:09168] [11] plumed_master(+0x15365)[0x5568bbd39365]
[pkrvmpptgkbjq6m:09168] *** End of error message ***
</pre>
{% endraw %}
