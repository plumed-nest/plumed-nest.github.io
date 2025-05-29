**Project ID:** [plumID:20.033]({{ '/' | absolute_url }}eggs/20/033/)  
Stderr for source:  ANALYSIS/plumed_histogram.dat   
Download: [zipped raw stdout](plumed_histogram.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_histogram.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @29 : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:68449] *** Process received signal ***
[pkrvmf6wy0o8zjz:68449] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:68449] Signal code:  (-6)
[pkrvmf6wy0o8zjz:68449] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4342645330]
[pkrvmf6wy0o8zjz:68449] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f434269eb2c]
[pkrvmf6wy0o8zjz:68449] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f434264527e]
[pkrvmf6wy0o8zjz:68449] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f43426288ff]
[pkrvmf6wy0o8zjz:68449] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4342aa5ff5]
[pkrvmf6wy0o8zjz:68449] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4342abb0da]
[pkrvmf6wy0o8zjz:68449] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4342aa5a55]
[pkrvmf6wy0o8zjz:68449] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4342aa5a6f]
[pkrvmf6wy0o8zjz:68449] [ 8] plumed_master(+0x146dd)[0x55e5210e96dd]
[pkrvmf6wy0o8zjz:68449] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f434262a1ca]
[pkrvmf6wy0o8zjz:68449] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f434262a28b]
[pkrvmf6wy0o8zjz:68449] [11] plumed_master(+0x15365)[0x55e5210ea365]
[pkrvmf6wy0o8zjz:68449] *** End of error message ***
</pre>
{% endraw %}
