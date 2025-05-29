**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/symm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @44 : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:66196] *** Process received signal ***
[pkrvmf6wy0o8zjz:66196] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:66196] Signal code:  (-6)
[pkrvmf6wy0o8zjz:66196] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9422845330]
[pkrvmf6wy0o8zjz:66196] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f942289eb2c]
[pkrvmf6wy0o8zjz:66196] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f942284527e]
[pkrvmf6wy0o8zjz:66196] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f94228288ff]
[pkrvmf6wy0o8zjz:66196] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9422ca5ff5]
[pkrvmf6wy0o8zjz:66196] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9422cbb0da]
[pkrvmf6wy0o8zjz:66196] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9422ca5a55]
[pkrvmf6wy0o8zjz:66196] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9422ca5a6f]
[pkrvmf6wy0o8zjz:66196] [ 8] plumed_master(+0x146dd)[0x55cb569cb6dd]
[pkrvmf6wy0o8zjz:66196] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f942282a1ca]
[pkrvmf6wy0o8zjz:66196] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f942282a28b]
[pkrvmf6wy0o8zjz:66196] [11] plumed_master(+0x15365)[0x55cb569cc365]
[pkrvmf6wy0o8zjz:66196] *** End of error message ***
</pre>
{% endraw %}
