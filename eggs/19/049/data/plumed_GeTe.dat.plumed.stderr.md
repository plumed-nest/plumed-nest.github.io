**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_GeTe.dat   
Download: [zipped raw stdout](plumed_GeTe.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_GeTe.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label cc_cmat : it was not possible to interpret atom name flq6
[pkrvmf6wy0o8zjz:39229] *** Process received signal ***
[pkrvmf6wy0o8zjz:39229] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:39229] Signal code:  (-6)
[pkrvmf6wy0o8zjz:39229] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcd69e45330]
[pkrvmf6wy0o8zjz:39229] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcd69e9eb2c]
[pkrvmf6wy0o8zjz:39229] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcd69e4527e]
[pkrvmf6wy0o8zjz:39229] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcd69e288ff]
[pkrvmf6wy0o8zjz:39229] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcd6a2a5ff5]
[pkrvmf6wy0o8zjz:39229] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcd6a2bb0da]
[pkrvmf6wy0o8zjz:39229] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcd6a2a5a55]
[pkrvmf6wy0o8zjz:39229] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcd6a2a5a6f]
[pkrvmf6wy0o8zjz:39229] [ 8] plumed(+0x146dd)[0x5573cdd536dd]
[pkrvmf6wy0o8zjz:39229] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcd69e2a1ca]
[pkrvmf6wy0o8zjz:39229] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcd69e2a28b]
[pkrvmf6wy0o8zjz:39229] [11] plumed(+0x15365)[0x5573cdd54365]
[pkrvmf6wy0o8zjz:39229] *** End of error message ***
</pre>
{% endraw %}
