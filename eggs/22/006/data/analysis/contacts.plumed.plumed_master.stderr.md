**Project ID:** [plumID:22.006]({{ '/' | absolute_url }}eggs/22/006/)  
Stderr for source:  analysis/contacts.plumed   
Download: [zipped raw stdout](contacts.plumed.plumed_master.stdout.txt.zip) - [zipped raw stderr](contacts.plumed.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @92 : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:37494] *** Process received signal ***
[pkrvmf6wy0o8zjz:37494] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:37494] Signal code:  (-6)
[pkrvmf6wy0o8zjz:37494] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f81e9245330]
[pkrvmf6wy0o8zjz:37494] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f81e929eb2c]
[pkrvmf6wy0o8zjz:37494] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f81e924527e]
[pkrvmf6wy0o8zjz:37494] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f81e92288ff]
[pkrvmf6wy0o8zjz:37494] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f81e96a5ff5]
[pkrvmf6wy0o8zjz:37494] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f81e96bb0da]
[pkrvmf6wy0o8zjz:37494] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f81e96a5a55]
[pkrvmf6wy0o8zjz:37494] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f81e96a5a6f]
[pkrvmf6wy0o8zjz:37494] [ 8] plumed_master(+0x146dd)[0x5569df89d6dd]
[pkrvmf6wy0o8zjz:37494] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f81e922a1ca]
[pkrvmf6wy0o8zjz:37494] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f81e922a28b]
[pkrvmf6wy0o8zjz:37494] [11] plumed_master(+0x15365)[0x5569df89e365]
[pkrvmf6wy0o8zjz:37494] *** End of error message ***
</pre>
{% endraw %}
