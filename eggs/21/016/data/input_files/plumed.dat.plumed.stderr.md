**Project ID:** [plumID:21.016]({{ '/' | absolute_url }}eggs/21/016/)  
Stderr for source:  input_files/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action SAXS with label saxs : cannot understand the following words from the input line : SCALEINT=1
[pkrvmf6wy0o8zjz:66681] *** Process received signal ***
[pkrvmf6wy0o8zjz:66681] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:66681] Signal code:  (-6)
[pkrvmf6wy0o8zjz:66681] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc754445330]
[pkrvmf6wy0o8zjz:66681] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc75449eb2c]
[pkrvmf6wy0o8zjz:66681] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc75444527e]
[pkrvmf6wy0o8zjz:66681] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc7544288ff]
[pkrvmf6wy0o8zjz:66681] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc7548a5ff5]
[pkrvmf6wy0o8zjz:66681] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc7548bb0da]
[pkrvmf6wy0o8zjz:66681] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc7548a5a55]
[pkrvmf6wy0o8zjz:66681] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc7548a5a6f]
[pkrvmf6wy0o8zjz:66681] [ 8] plumed(+0x146dd)[0x556cf079f6dd]
[pkrvmf6wy0o8zjz:66681] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc75442a1ca]
[pkrvmf6wy0o8zjz:66681] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc75442a28b]
[pkrvmf6wy0o8zjz:66681] [11] plumed(+0x15365)[0x556cf07a0365]
[pkrvmf6wy0o8zjz:66681] *** End of error message ***
</pre>
{% endraw %}
