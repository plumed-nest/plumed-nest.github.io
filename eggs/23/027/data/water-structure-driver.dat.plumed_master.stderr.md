**Project ID:** [plumID:23.027]({{ '/' | absolute_url }}eggs/23/027/)  
Stderr for source:  water-structure-driver.dat   
Download: [zipped raw stdout](water-structure-driver.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](water-structure-driver.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @179 : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:62349] *** Process received signal ***
[pkrvmf6wy0o8zjz:62349] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:62349] Signal code:  (-6)
[pkrvmf6wy0o8zjz:62349] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7494645330]
[pkrvmf6wy0o8zjz:62349] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f749469eb2c]
[pkrvmf6wy0o8zjz:62349] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f749464527e]
[pkrvmf6wy0o8zjz:62349] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f74946288ff]
[pkrvmf6wy0o8zjz:62349] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7494aa5ff5]
[pkrvmf6wy0o8zjz:62349] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7494abb0da]
[pkrvmf6wy0o8zjz:62349] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7494aa5a55]
[pkrvmf6wy0o8zjz:62349] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7494aa5a6f]
[pkrvmf6wy0o8zjz:62349] [ 8] plumed_master(+0x146dd)[0x5635516986dd]
[pkrvmf6wy0o8zjz:62349] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f749462a1ca]
[pkrvmf6wy0o8zjz:62349] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f749462a28b]
[pkrvmf6wy0o8zjz:62349] [11] plumed_master(+0x15365)[0x563551699365]
[pkrvmf6wy0o8zjz:62349] *** End of error message ***
</pre>
{% endraw %}
