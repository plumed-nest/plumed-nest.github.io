**Project ID:** [plumID:19.027]({{ '/' | absolute_url }}eggs/19/027/)  
Stderr for source:  MulticanonicalSimulations/Multicanonical/Analysis/SampledDistribution/plumed.dat   
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
[pkrvmf6wy0o8zjz:70083] *** Process received signal ***
[pkrvmf6wy0o8zjz:70083] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:70083] Signal code:  (-6)
[pkrvmf6wy0o8zjz:70083] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc203645330]
[pkrvmf6wy0o8zjz:70083] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc20369eb2c]
[pkrvmf6wy0o8zjz:70083] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc20364527e]
[pkrvmf6wy0o8zjz:70083] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc2036288ff]
[pkrvmf6wy0o8zjz:70083] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc203aa5ff5]
[pkrvmf6wy0o8zjz:70083] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc203abb0da]
[pkrvmf6wy0o8zjz:70083] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc203aa5a55]
[pkrvmf6wy0o8zjz:70083] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc203aa5a6f]
[pkrvmf6wy0o8zjz:70083] [ 8] plumed_master(+0x146dd)[0x55c45efff6dd]
[pkrvmf6wy0o8zjz:70083] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc20362a1ca]
[pkrvmf6wy0o8zjz:70083] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc20362a28b]
[pkrvmf6wy0o8zjz:70083] [11] plumed_master(+0x15365)[0x55c45f000365]
[pkrvmf6wy0o8zjz:70083] *** End of error message ***
</pre>
{% endraw %}
