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
[pkrvmf6wy0o8zjz:38192] *** Process received signal ***
[pkrvmf6wy0o8zjz:38192] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:38192] Signal code:  (-6)
[pkrvmf6wy0o8zjz:38192] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f22fb245330]
[pkrvmf6wy0o8zjz:38192] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f22fb29eb2c]
[pkrvmf6wy0o8zjz:38192] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f22fb24527e]
[pkrvmf6wy0o8zjz:38192] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f22fb2288ff]
[pkrvmf6wy0o8zjz:38192] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f22fb6a5ff5]
[pkrvmf6wy0o8zjz:38192] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f22fb6bb0da]
[pkrvmf6wy0o8zjz:38192] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f22fb6a5a55]
[pkrvmf6wy0o8zjz:38192] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f22fb6a5a6f]
[pkrvmf6wy0o8zjz:38192] [ 8] plumed(+0x146dd)[0x55b8573d76dd]
[pkrvmf6wy0o8zjz:38192] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f22fb22a1ca]
[pkrvmf6wy0o8zjz:38192] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f22fb22a28b]
[pkrvmf6wy0o8zjz:38192] [11] plumed(+0x15365)[0x55b8573d8365]
[pkrvmf6wy0o8zjz:38192] *** End of error message ***
</pre>
{% endraw %}
