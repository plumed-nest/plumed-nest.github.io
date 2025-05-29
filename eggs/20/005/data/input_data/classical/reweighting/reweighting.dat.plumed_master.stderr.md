**Project ID:** [plumID:20.005]({{ '/' | absolute_url }}eggs/20/005/)  
Stderr for source:  input_data/classical/reweighting/reweighting.dat   
Download: [zipped raw stdout](reweighting.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweighting.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @16 : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:65707] *** Process received signal ***
[pkrvmf6wy0o8zjz:65707] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:65707] Signal code:  (-6)
[pkrvmf6wy0o8zjz:65707] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff4e9645330]
[pkrvmf6wy0o8zjz:65707] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff4e969eb2c]
[pkrvmf6wy0o8zjz:65707] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff4e964527e]
[pkrvmf6wy0o8zjz:65707] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff4e96288ff]
[pkrvmf6wy0o8zjz:65707] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff4e9aa5ff5]
[pkrvmf6wy0o8zjz:65707] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff4e9abb0da]
[pkrvmf6wy0o8zjz:65707] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff4e9aa5a55]
[pkrvmf6wy0o8zjz:65707] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff4e9aa5a6f]
[pkrvmf6wy0o8zjz:65707] [ 8] plumed_master(+0x146dd)[0x560c5baf96dd]
[pkrvmf6wy0o8zjz:65707] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff4e962a1ca]
[pkrvmf6wy0o8zjz:65707] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff4e962a28b]
[pkrvmf6wy0o8zjz:65707] [11] plumed_master(+0x15365)[0x560c5bafa365]
[pkrvmf6wy0o8zjz:65707] *** End of error message ***
</pre>
{% endraw %}
