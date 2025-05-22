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
[pkrvmf6wy0o8zjz:39321] *** Process received signal ***
[pkrvmf6wy0o8zjz:39321] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:39321] Signal code:  (-6)
[pkrvmf6wy0o8zjz:39321] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fac50845330]
[pkrvmf6wy0o8zjz:39321] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fac5089eb2c]
[pkrvmf6wy0o8zjz:39321] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fac5084527e]
[pkrvmf6wy0o8zjz:39321] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fac508288ff]
[pkrvmf6wy0o8zjz:39321] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fac50ca5ff5]
[pkrvmf6wy0o8zjz:39321] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fac50cbb0da]
[pkrvmf6wy0o8zjz:39321] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fac50ca5a55]
[pkrvmf6wy0o8zjz:39321] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fac50ca5a6f]
[pkrvmf6wy0o8zjz:39321] [ 8] plumed(+0x146dd)[0x560d0850e6dd]
[pkrvmf6wy0o8zjz:39321] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fac5082a1ca]
[pkrvmf6wy0o8zjz:39321] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fac5082a28b]
[pkrvmf6wy0o8zjz:39321] [11] plumed(+0x15365)[0x560d0850f365]
[pkrvmf6wy0o8zjz:39321] *** End of error message ***
</pre>
{% endraw %}
