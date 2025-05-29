**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX with label @s41 : missing SWITCH11 keyword
[pkrvmf6wy0o8zjz:70016] *** Process received signal ***
[pkrvmf6wy0o8zjz:70016] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:70016] Signal code:  (-6)
[pkrvmf6wy0o8zjz:70016] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff1ce045330]
[pkrvmf6wy0o8zjz:70016] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff1ce09eb2c]
[pkrvmf6wy0o8zjz:70016] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff1ce04527e]
[pkrvmf6wy0o8zjz:70016] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff1ce0288ff]
[pkrvmf6wy0o8zjz:70016] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff1ce4a5ff5]
[pkrvmf6wy0o8zjz:70016] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff1ce4bb0da]
[pkrvmf6wy0o8zjz:70016] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff1ce4a5a55]
[pkrvmf6wy0o8zjz:70016] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff1ce4a5a6f]
[pkrvmf6wy0o8zjz:70016] [ 8] plumed(+0x146dd)[0x561ba6ebc6dd]
[pkrvmf6wy0o8zjz:70016] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff1ce02a1ca]
[pkrvmf6wy0o8zjz:70016] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff1ce02a28b]
[pkrvmf6wy0o8zjz:70016] [11] plumed(+0x15365)[0x561ba6ebd365]
[pkrvmf6wy0o8zjz:70016] *** End of error message ***
</pre>
{% endraw %}
