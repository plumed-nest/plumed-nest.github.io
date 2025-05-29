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
[pkrvmf6wy0o8zjz:62892] *** Process received signal ***
[pkrvmf6wy0o8zjz:62892] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:62892] Signal code:  (-6)
[pkrvmf6wy0o8zjz:62892] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8c0a845330]
[pkrvmf6wy0o8zjz:62892] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8c0a89eb2c]
[pkrvmf6wy0o8zjz:62892] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8c0a84527e]
[pkrvmf6wy0o8zjz:62892] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8c0a8288ff]
[pkrvmf6wy0o8zjz:62892] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8c0aca5ff5]
[pkrvmf6wy0o8zjz:62892] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8c0acbb0da]
[pkrvmf6wy0o8zjz:62892] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8c0aca5a55]
[pkrvmf6wy0o8zjz:62892] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8c0aca5a6f]
[pkrvmf6wy0o8zjz:62892] [ 8] plumed(+0x146dd)[0x55e251fe66dd]
[pkrvmf6wy0o8zjz:62892] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8c0a82a1ca]
[pkrvmf6wy0o8zjz:62892] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8c0a82a28b]
[pkrvmf6wy0o8zjz:62892] [11] plumed(+0x15365)[0x55e251fe7365]
[pkrvmf6wy0o8zjz:62892] *** End of error message ***
</pre>
{% endraw %}
