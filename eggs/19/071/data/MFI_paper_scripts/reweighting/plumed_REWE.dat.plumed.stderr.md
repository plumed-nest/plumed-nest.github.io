**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/reweighting/plumed_REWE.dat   
Download: [zipped raw stdout](plumed_REWE.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_REWE.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : cannot understand the following words from the input line : REWEIGHTING_NGRID=200, REWEIGHTING_NHILLS=10
[pkrvmpptgkbjq6m:10795] *** Process received signal ***
[pkrvmpptgkbjq6m:10795] Signal: Aborted (6)
[pkrvmpptgkbjq6m:10795] Signal code:  (-6)
[pkrvmpptgkbjq6m:10795] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9b1c445330]
[pkrvmpptgkbjq6m:10795] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9b1c49eb2c]
[pkrvmpptgkbjq6m:10795] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9b1c44527e]
[pkrvmpptgkbjq6m:10795] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9b1c4288ff]
[pkrvmpptgkbjq6m:10795] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9b1c8a5ff5]
[pkrvmpptgkbjq6m:10795] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9b1c8bb0da]
[pkrvmpptgkbjq6m:10795] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9b1c8a5a55]
[pkrvmpptgkbjq6m:10795] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9b1c8a5a6f]
[pkrvmpptgkbjq6m:10795] [ 8] plumed(+0x146dd)[0x55a4434996dd]
[pkrvmpptgkbjq6m:10795] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9b1c42a1ca]
[pkrvmpptgkbjq6m:10795] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9b1c42a28b]
[pkrvmpptgkbjq6m:10795] [11] plumed(+0x15365)[0x55a44349a365]
[pkrvmpptgkbjq6m:10795] *** End of error message ***
</pre>
{% endraw %}
