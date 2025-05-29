**Project ID:** [plumID:19.027]({{ '/' | absolute_url }}eggs/19/027/)  
Stderr for source:  MulticanonicalSimulations/References/Temp550K/Distribution/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @27 : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:70364] *** Process received signal ***
[pkrvmf6wy0o8zjz:70364] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:70364] Signal code:  (-6)
[pkrvmf6wy0o8zjz:70364] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7facbca45330]
[pkrvmf6wy0o8zjz:70364] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7facbca9eb2c]
[pkrvmf6wy0o8zjz:70364] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7facbca4527e]
[pkrvmf6wy0o8zjz:70364] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7facbca288ff]
[pkrvmf6wy0o8zjz:70364] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7facbcea5ff5]
[pkrvmf6wy0o8zjz:70364] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7facbcebb0da]
[pkrvmf6wy0o8zjz:70364] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7facbcea5a55]
[pkrvmf6wy0o8zjz:70364] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7facbcea5a6f]
[pkrvmf6wy0o8zjz:70364] [ 8] plumed_master(+0x146dd)[0x55a2587d66dd]
[pkrvmf6wy0o8zjz:70364] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7facbca2a1ca]
[pkrvmf6wy0o8zjz:70364] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7facbca2a28b]
[pkrvmf6wy0o8zjz:70364] [11] plumed_master(+0x15365)[0x55a2587d7365]
[pkrvmf6wy0o8zjz:70364] *** End of error message ***
</pre>
{% endraw %}
