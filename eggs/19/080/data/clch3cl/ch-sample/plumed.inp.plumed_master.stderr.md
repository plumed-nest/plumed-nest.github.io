**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  clch3cl/ch-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @36 : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:40289] *** Process received signal ***
[pkrvmf6wy0o8zjz:40289] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:40289] Signal code:  (-6)
[pkrvmf6wy0o8zjz:40289] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1c88845330]
[pkrvmf6wy0o8zjz:40289] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1c8889eb2c]
[pkrvmf6wy0o8zjz:40289] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1c8884527e]
[pkrvmf6wy0o8zjz:40289] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1c888288ff]
[pkrvmf6wy0o8zjz:40289] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1c88ca5ff5]
[pkrvmf6wy0o8zjz:40289] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1c88cbb0da]
[pkrvmf6wy0o8zjz:40289] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1c88ca5a55]
[pkrvmf6wy0o8zjz:40289] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1c88ca5a6f]
[pkrvmf6wy0o8zjz:40289] [ 8] plumed_master(+0x146dd)[0x55737a1d26dd]
[pkrvmf6wy0o8zjz:40289] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1c8882a1ca]
[pkrvmf6wy0o8zjz:40289] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1c8882a28b]
[pkrvmf6wy0o8zjz:40289] [11] plumed_master(+0x15365)[0x55737a1d3365]
[pkrvmf6wy0o8zjz:40289] *** End of error message ***
</pre>
{% endraw %}
