**Project ID:** [plumID:19.050]({{ '/' | absolute_url }}eggs/19/050/)  
Stderr for source:  plumed_histogram.dat   
Download: [zipped raw stdout](plumed_histogram.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_histogram.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @32 : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:66166] *** Process received signal ***
[pkrvmf6wy0o8zjz:66166] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:66166] Signal code:  (-6)
[pkrvmf6wy0o8zjz:66166] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0274045330]
[pkrvmf6wy0o8zjz:66166] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f027409eb2c]
[pkrvmf6wy0o8zjz:66166] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f027404527e]
[pkrvmf6wy0o8zjz:66166] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f02740288ff]
[pkrvmf6wy0o8zjz:66166] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f02744a5ff5]
[pkrvmf6wy0o8zjz:66166] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f02744bb0da]
[pkrvmf6wy0o8zjz:66166] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f02744a5a55]
[pkrvmf6wy0o8zjz:66166] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f02744a5a6f]
[pkrvmf6wy0o8zjz:66166] [ 8] plumed_master(+0x146dd)[0x55a48d73d6dd]
[pkrvmf6wy0o8zjz:66166] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f027402a1ca]
[pkrvmf6wy0o8zjz:66166] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f027402a28b]
[pkrvmf6wy0o8zjz:66166] [11] plumed_master(+0x15365)[0x55a48d73e365]
[pkrvmf6wy0o8zjz:66166] *** End of error message ***
</pre>
{% endraw %}
