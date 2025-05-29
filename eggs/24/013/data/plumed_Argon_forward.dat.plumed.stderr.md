**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_forward.dat   
Download: [zipped raw stdout](plumed_Argon_forward.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_forward.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[pkrvmf6wy0o8zjz:62947] *** Process received signal ***
[pkrvmf6wy0o8zjz:62947] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:62947] Signal code:  (-6)
[pkrvmf6wy0o8zjz:62947] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f317c645330]
[pkrvmf6wy0o8zjz:62947] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f317c69eb2c]
[pkrvmf6wy0o8zjz:62947] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f317c64527e]
[pkrvmf6wy0o8zjz:62947] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f317c6288ff]
[pkrvmf6wy0o8zjz:62947] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f317caa5ff5]
[pkrvmf6wy0o8zjz:62947] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f317cabb0da]
[pkrvmf6wy0o8zjz:62947] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f317caa5a55]
[pkrvmf6wy0o8zjz:62947] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f317caa5a6f]
[pkrvmf6wy0o8zjz:62947] [ 8] plumed(+0x146dd)[0x563504a3d6dd]
[pkrvmf6wy0o8zjz:62947] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f317c62a1ca]
[pkrvmf6wy0o8zjz:62947] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f317c62a28b]
[pkrvmf6wy0o8zjz:62947] [11] plumed(+0x15365)[0x563504a3e365]
[pkrvmf6wy0o8zjz:62947] *** End of error message ***
</pre>
{% endraw %}
