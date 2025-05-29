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
[pkrvmf6wy0o8zjz:69566] *** Process received signal ***
[pkrvmf6wy0o8zjz:69566] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:69566] Signal code:  (-6)
[pkrvmf6wy0o8zjz:69566] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5908045330]
[pkrvmf6wy0o8zjz:69566] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f590809eb2c]
[pkrvmf6wy0o8zjz:69566] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f590804527e]
[pkrvmf6wy0o8zjz:69566] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f59080288ff]
[pkrvmf6wy0o8zjz:69566] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f59084a5ff5]
[pkrvmf6wy0o8zjz:69566] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f59084bb0da]
[pkrvmf6wy0o8zjz:69566] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f59084a5a55]
[pkrvmf6wy0o8zjz:69566] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f59084a5a6f]
[pkrvmf6wy0o8zjz:69566] [ 8] plumed(+0x146dd)[0x56169eacf6dd]
[pkrvmf6wy0o8zjz:69566] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f590802a1ca]
[pkrvmf6wy0o8zjz:69566] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f590802a28b]
[pkrvmf6wy0o8zjz:69566] [11] plumed(+0x15365)[0x56169ead0365]
[pkrvmf6wy0o8zjz:69566] *** End of error message ***
</pre>
{% endraw %}
