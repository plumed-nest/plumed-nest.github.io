**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_GeTe.dat   
Download: [zipped raw stdout](plumed_GeTe.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_GeTe.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label cc_cmat : it was not possible to interpret atom name flq6
[pkrvmpptgkbjq6m:11061] *** Process received signal ***
[pkrvmpptgkbjq6m:11061] Signal: Aborted (6)
[pkrvmpptgkbjq6m:11061] Signal code:  (-6)
[pkrvmpptgkbjq6m:11061] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f844ca45330]
[pkrvmpptgkbjq6m:11061] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f844ca9eb2c]
[pkrvmpptgkbjq6m:11061] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f844ca4527e]
[pkrvmpptgkbjq6m:11061] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f844ca288ff]
[pkrvmpptgkbjq6m:11061] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f844cea5ff5]
[pkrvmpptgkbjq6m:11061] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f844cebb0da]
[pkrvmpptgkbjq6m:11061] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f844cea5a55]
[pkrvmpptgkbjq6m:11061] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f844cea5a6f]
[pkrvmpptgkbjq6m:11061] [ 8] plumed_master(+0x146dd)[0x55e4b7f8d6dd]
[pkrvmpptgkbjq6m:11061] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f844ca2a1ca]
[pkrvmpptgkbjq6m:11061] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f844ca2a28b]
[pkrvmpptgkbjq6m:11061] [11] plumed_master(+0x15365)[0x55e4b7f8e365]
[pkrvmpptgkbjq6m:11061] *** End of error message ***
</pre>
{% endraw %}
