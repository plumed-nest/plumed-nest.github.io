**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT_A399V/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:62007] *** Process received signal ***
[pkrvmf6wy0o8zjz:62007] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:62007] Signal code:  (-6)
[pkrvmf6wy0o8zjz:62007] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1abbe45330]
[pkrvmf6wy0o8zjz:62007] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1abbe9eb2c]
[pkrvmf6wy0o8zjz:62007] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1abbe4527e]
[pkrvmf6wy0o8zjz:62007] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1abbe288ff]
[pkrvmf6wy0o8zjz:62007] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1abc2a5ff5]
[pkrvmf6wy0o8zjz:62007] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1abc2bb0da]
[pkrvmf6wy0o8zjz:62007] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1abc2a5a55]
[pkrvmf6wy0o8zjz:62007] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1abc2a5a6f]
[pkrvmf6wy0o8zjz:62007] [ 8] plumed_master(+0x146dd)[0x56379f4ce6dd]
[pkrvmf6wy0o8zjz:62007] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1abbe2a1ca]
[pkrvmf6wy0o8zjz:62007] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1abbe2a28b]
[pkrvmf6wy0o8zjz:62007] [11] plumed_master(+0x15365)[0x56379f4cf365]
[pkrvmf6wy0o8zjz:62007] *** End of error message ***
</pre>
{% endraw %}
