**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/reweighting/plumed_REWE.dat   
Download: [zipped raw stdout](plumed_REWE.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_REWE.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : cannot understand the following words from the input line : REWEIGHTING_NGRID=200, REWEIGHTING_NHILLS=10
[pkrvmf6wy0o8zjz:38209] *** Process received signal ***
[pkrvmf6wy0o8zjz:38209] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:38209] Signal code:  (-6)
[pkrvmf6wy0o8zjz:38209] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f28d9c45330]
[pkrvmf6wy0o8zjz:38209] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f28d9c9eb2c]
[pkrvmf6wy0o8zjz:38209] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f28d9c4527e]
[pkrvmf6wy0o8zjz:38209] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f28d9c288ff]
[pkrvmf6wy0o8zjz:38209] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f28da0a5ff5]
[pkrvmf6wy0o8zjz:38209] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f28da0bb0da]
[pkrvmf6wy0o8zjz:38209] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f28da0a5a55]
[pkrvmf6wy0o8zjz:38209] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f28da0a5a6f]
[pkrvmf6wy0o8zjz:38209] [ 8] plumed_master(+0x146dd)[0x5596ca0c86dd]
[pkrvmf6wy0o8zjz:38209] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f28d9c2a1ca]
[pkrvmf6wy0o8zjz:38209] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f28d9c2a28b]
[pkrvmf6wy0o8zjz:38209] [11] plumed_master(+0x15365)[0x5596ca0c9365]
[pkrvmf6wy0o8zjz:38209] *** End of error message ***
</pre>
{% endraw %}
