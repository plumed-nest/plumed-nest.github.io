**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT-CH3Cl/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @44 : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:61930] *** Process received signal ***
[pkrvmf6wy0o8zjz:61930] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:61930] Signal code:  (-6)
[pkrvmf6wy0o8zjz:61930] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f94ae245330]
[pkrvmf6wy0o8zjz:61930] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f94ae29eb2c]
[pkrvmf6wy0o8zjz:61930] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f94ae24527e]
[pkrvmf6wy0o8zjz:61930] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f94ae2288ff]
[pkrvmf6wy0o8zjz:61930] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f94ae6a5ff5]
[pkrvmf6wy0o8zjz:61930] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f94ae6bb0da]
[pkrvmf6wy0o8zjz:61930] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f94ae6a5a55]
[pkrvmf6wy0o8zjz:61930] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f94ae6a5a6f]
[pkrvmf6wy0o8zjz:61930] [ 8] plumed_master(+0x146dd)[0x55be82f9e6dd]
[pkrvmf6wy0o8zjz:61930] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f94ae22a1ca]
[pkrvmf6wy0o8zjz:61930] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f94ae22a28b]
[pkrvmf6wy0o8zjz:61930] [11] plumed_master(+0x15365)[0x55be82f9f365]
[pkrvmf6wy0o8zjz:61930] *** End of error message ***
</pre>
{% endraw %}
