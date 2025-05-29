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
[pkrvmf6wy0o8zjz:69927] *** Process received signal ***
[pkrvmf6wy0o8zjz:69927] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:69927] Signal code:  (-6)
[pkrvmf6wy0o8zjz:69927] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcaa5845330]
[pkrvmf6wy0o8zjz:69927] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcaa589eb2c]
[pkrvmf6wy0o8zjz:69927] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcaa584527e]
[pkrvmf6wy0o8zjz:69927] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcaa58288ff]
[pkrvmf6wy0o8zjz:69927] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcaa5ca5ff5]
[pkrvmf6wy0o8zjz:69927] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcaa5cbb0da]
[pkrvmf6wy0o8zjz:69927] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcaa5ca5a55]
[pkrvmf6wy0o8zjz:69927] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcaa5ca5a6f]
[pkrvmf6wy0o8zjz:69927] [ 8] plumed(+0x146dd)[0x55a34e96a6dd]
[pkrvmf6wy0o8zjz:69927] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcaa582a1ca]
[pkrvmf6wy0o8zjz:69927] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcaa582a28b]
[pkrvmf6wy0o8zjz:69927] [11] plumed(+0x15365)[0x55a34e96b365]
[pkrvmf6wy0o8zjz:69927] *** End of error message ***
</pre>
{% endraw %}
