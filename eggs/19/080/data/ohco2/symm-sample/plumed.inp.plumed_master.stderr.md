**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  ohco2/symm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:68724] *** Process received signal ***
[pkrvmf6wy0o8zjz:68724] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:68724] Signal code:  (-6)
[pkrvmf6wy0o8zjz:68724] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc351e45330]
[pkrvmf6wy0o8zjz:68724] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc351e9eb2c]
[pkrvmf6wy0o8zjz:68724] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc351e4527e]
[pkrvmf6wy0o8zjz:68724] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc351e288ff]
[pkrvmf6wy0o8zjz:68724] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc3522a5ff5]
[pkrvmf6wy0o8zjz:68724] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc3522bb0da]
[pkrvmf6wy0o8zjz:68724] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc3522a5a55]
[pkrvmf6wy0o8zjz:68724] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc3522a5a6f]
[pkrvmf6wy0o8zjz:68724] [ 8] plumed_master(+0x146dd)[0x5628d81986dd]
[pkrvmf6wy0o8zjz:68724] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc351e2a1ca]
[pkrvmf6wy0o8zjz:68724] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc351e2a28b]
[pkrvmf6wy0o8zjz:68724] [11] plumed_master(+0x15365)[0x5628d8199365]
[pkrvmf6wy0o8zjz:68724] *** End of error message ***
</pre>
{% endraw %}
