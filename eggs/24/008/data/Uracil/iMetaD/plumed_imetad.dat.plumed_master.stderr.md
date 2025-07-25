**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Uracil/iMetaD/plumed_imetad.dat   
Download: [zipped raw stdout](plumed_imetad.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_imetad.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action PATH with label @s13 : keyword LAMBDA is compulsory for this action
[pkrvmpptgkbjq6m:08034] *** Process received signal ***
[pkrvmpptgkbjq6m:08034] Signal: Aborted (6)
[pkrvmpptgkbjq6m:08034] Signal code:  (-6)
[pkrvmpptgkbjq6m:08034] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0770a45330]
[pkrvmpptgkbjq6m:08034] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0770a9eb2c]
[pkrvmpptgkbjq6m:08034] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0770a4527e]
[pkrvmpptgkbjq6m:08034] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0770a288ff]
[pkrvmpptgkbjq6m:08034] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0770ea5ff5]
[pkrvmpptgkbjq6m:08034] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0770ebb0da]
[pkrvmpptgkbjq6m:08034] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0770ea5a55]
[pkrvmpptgkbjq6m:08034] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0770ea5a6f]
[pkrvmpptgkbjq6m:08034] [ 8] plumed_master(+0x146dd)[0x5612652986dd]
[pkrvmpptgkbjq6m:08034] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0770a2a1ca]
[pkrvmpptgkbjq6m:08034] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0770a2a28b]
[pkrvmpptgkbjq6m:08034] [11] plumed_master(+0x15365)[0x561265299365]
[pkrvmpptgkbjq6m:08034] *** End of error message ***
</pre>
{% endraw %}
