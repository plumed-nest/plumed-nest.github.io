**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  h3/sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @32 : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:69167] *** Process received signal ***
[pkrvmf6wy0o8zjz:69167] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:69167] Signal code:  (-6)
[pkrvmf6wy0o8zjz:69167] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f132ba45330]
[pkrvmf6wy0o8zjz:69167] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f132ba9eb2c]
[pkrvmf6wy0o8zjz:69167] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f132ba4527e]
[pkrvmf6wy0o8zjz:69167] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f132ba288ff]
[pkrvmf6wy0o8zjz:69167] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f132bea5ff5]
[pkrvmf6wy0o8zjz:69167] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f132bebb0da]
[pkrvmf6wy0o8zjz:69167] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f132bea5a55]
[pkrvmf6wy0o8zjz:69167] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f132bea5a6f]
[pkrvmf6wy0o8zjz:69167] [ 8] plumed_master(+0x146dd)[0x55657c00d6dd]
[pkrvmf6wy0o8zjz:69167] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f132ba2a1ca]
[pkrvmf6wy0o8zjz:69167] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f132ba2a28b]
[pkrvmf6wy0o8zjz:69167] [11] plumed_master(+0x15365)[0x55657c00e365]
[pkrvmf6wy0o8zjz:69167] *** End of error message ***
</pre>
{% endraw %}
