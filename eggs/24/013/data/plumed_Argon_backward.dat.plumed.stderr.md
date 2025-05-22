**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_backward.dat   
Download: [zipped raw stdout](plumed_Argon_backward.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_backward.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[pkrvmf6wy0o8zjz:34848] *** Process received signal ***
[pkrvmf6wy0o8zjz:34848] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:34848] Signal code:  (-6)
[pkrvmf6wy0o8zjz:34848] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fceea645330]
[pkrvmf6wy0o8zjz:34848] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fceea69eb2c]
[pkrvmf6wy0o8zjz:34848] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fceea64527e]
[pkrvmf6wy0o8zjz:34848] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fceea6288ff]
[pkrvmf6wy0o8zjz:34848] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fceeaaa5ff5]
[pkrvmf6wy0o8zjz:34848] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fceeaabb0da]
[pkrvmf6wy0o8zjz:34848] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fceeaaa5a55]
[pkrvmf6wy0o8zjz:34848] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fceeaaa5a6f]
[pkrvmf6wy0o8zjz:34848] [ 8] plumed(+0x146dd)[0x55754e3e96dd]
[pkrvmf6wy0o8zjz:34848] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fceea62a1ca]
[pkrvmf6wy0o8zjz:34848] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fceea62a28b]
[pkrvmf6wy0o8zjz:34848] [11] plumed(+0x15365)[0x55754e3ea365]
[pkrvmf6wy0o8zjz:34848] *** End of error message ***
</pre>
{% endraw %}
