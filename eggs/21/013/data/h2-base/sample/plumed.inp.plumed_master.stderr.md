**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-base/sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @29 : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:40434] *** Process received signal ***
[pkrvmf6wy0o8zjz:40434] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:40434] Signal code:  (-6)
[pkrvmf6wy0o8zjz:40434] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe2ee245330]
[pkrvmf6wy0o8zjz:40434] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe2ee29eb2c]
[pkrvmf6wy0o8zjz:40434] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe2ee24527e]
[pkrvmf6wy0o8zjz:40434] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe2ee2288ff]
[pkrvmf6wy0o8zjz:40434] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe2ee6a5ff5]
[pkrvmf6wy0o8zjz:40434] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe2ee6bb0da]
[pkrvmf6wy0o8zjz:40434] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe2ee6a5a55]
[pkrvmf6wy0o8zjz:40434] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe2ee6a5a6f]
[pkrvmf6wy0o8zjz:40434] [ 8] plumed_master(+0x146dd)[0x5640054636dd]
[pkrvmf6wy0o8zjz:40434] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe2ee22a1ca]
[pkrvmf6wy0o8zjz:40434] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe2ee22a28b]
[pkrvmf6wy0o8zjz:40434] [11] plumed_master(+0x15365)[0x564005464365]
[pkrvmf6wy0o8zjz:40434] *** End of error message ***
</pre>
{% endraw %}
