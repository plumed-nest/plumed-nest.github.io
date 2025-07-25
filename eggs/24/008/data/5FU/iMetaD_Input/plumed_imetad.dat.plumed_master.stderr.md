**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  5FU/iMetaD_Input/plumed_imetad.dat   
Download: [zipped raw stdout](plumed_imetad.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_imetad.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action PATH with label @s13 : keyword LAMBDA is compulsory for this action
[pkrvmpptgkbjq6m:07861] *** Process received signal ***
[pkrvmpptgkbjq6m:07861] Signal: Aborted (6)
[pkrvmpptgkbjq6m:07861] Signal code:  (-6)
[pkrvmpptgkbjq6m:07861] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f68a9045330]
[pkrvmpptgkbjq6m:07861] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f68a909eb2c]
[pkrvmpptgkbjq6m:07861] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f68a904527e]
[pkrvmpptgkbjq6m:07861] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f68a90288ff]
[pkrvmpptgkbjq6m:07861] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f68a94a5ff5]
[pkrvmpptgkbjq6m:07861] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f68a94bb0da]
[pkrvmpptgkbjq6m:07861] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f68a94a5a55]
[pkrvmpptgkbjq6m:07861] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f68a94a5a6f]
[pkrvmpptgkbjq6m:07861] [ 8] plumed_master(+0x146dd)[0x5565b98826dd]
[pkrvmpptgkbjq6m:07861] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f68a902a1ca]
[pkrvmpptgkbjq6m:07861] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f68a902a28b]
[pkrvmpptgkbjq6m:07861] [11] plumed_master(+0x15365)[0x5565b9883365]
[pkrvmpptgkbjq6m:07861] *** End of error message ***
</pre>
{% endraw %}
