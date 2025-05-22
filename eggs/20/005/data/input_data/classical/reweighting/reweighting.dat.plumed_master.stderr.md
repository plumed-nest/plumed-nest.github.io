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
[pkrvmf6wy0o8zjz:39781] *** Process received signal ***
[pkrvmf6wy0o8zjz:39781] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:39781] Signal code:  (-6)
[pkrvmf6wy0o8zjz:39781] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f02eb845330]
[pkrvmf6wy0o8zjz:39781] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f02eb89eb2c]
[pkrvmf6wy0o8zjz:39781] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f02eb84527e]
[pkrvmf6wy0o8zjz:39781] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f02eb8288ff]
[pkrvmf6wy0o8zjz:39781] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f02ebca5ff5]
[pkrvmf6wy0o8zjz:39781] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f02ebcbb0da]
[pkrvmf6wy0o8zjz:39781] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f02ebca5a55]
[pkrvmf6wy0o8zjz:39781] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f02ebca5a6f]
[pkrvmf6wy0o8zjz:39781] [ 8] plumed_master(+0x146dd)[0x55799f69a6dd]
[pkrvmf6wy0o8zjz:39781] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f02eb82a1ca]
[pkrvmf6wy0o8zjz:39781] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f02eb82a28b]
[pkrvmf6wy0o8zjz:39781] [11] plumed_master(+0x15365)[0x55799f69b365]
[pkrvmf6wy0o8zjz:39781] *** End of error message ***
</pre>
{% endraw %}
