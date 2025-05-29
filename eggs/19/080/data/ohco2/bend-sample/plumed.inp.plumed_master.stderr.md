**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  ohco2/bend-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @32 : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:68812] *** Process received signal ***
[pkrvmf6wy0o8zjz:68812] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:68812] Signal code:  (-6)
[pkrvmf6wy0o8zjz:68812] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc4a7445330]
[pkrvmf6wy0o8zjz:68812] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc4a749eb2c]
[pkrvmf6wy0o8zjz:68812] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc4a744527e]
[pkrvmf6wy0o8zjz:68812] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc4a74288ff]
[pkrvmf6wy0o8zjz:68812] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc4a78a5ff5]
[pkrvmf6wy0o8zjz:68812] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc4a78bb0da]
[pkrvmf6wy0o8zjz:68812] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc4a78a5a55]
[pkrvmf6wy0o8zjz:68812] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc4a78a5a6f]
[pkrvmf6wy0o8zjz:68812] [ 8] plumed_master(+0x146dd)[0x5564f889e6dd]
[pkrvmf6wy0o8zjz:68812] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc4a742a1ca]
[pkrvmf6wy0o8zjz:68812] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc4a742a28b]
[pkrvmf6wy0o8zjz:68812] [11] plumed_master(+0x15365)[0x5564f889f365]
[pkrvmf6wy0o8zjz:68812] *** End of error message ***
</pre>
{% endraw %}
