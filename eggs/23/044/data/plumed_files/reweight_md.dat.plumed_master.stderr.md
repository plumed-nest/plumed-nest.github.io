**Project ID:** [plumID:23.044]({{ '/' | absolute_url }}eggs/23/044/)  
Stderr for source:  plumed_files/reweight_md.dat   
Download: [zipped raw stdout](reweight_md.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweight_md.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @32 : keyword ARG is compulsory for this action
[fv-az1937-158:61654] *** Process received signal ***
[fv-az1937-158:61654] Signal: Aborted (6)
[fv-az1937-158:61654] Signal code:  (-6)
[fv-az1937-158:61654] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4c7de45330]
[fv-az1937-158:61654] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4c7de9eb2c]
[fv-az1937-158:61654] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4c7de4527e]
[fv-az1937-158:61654] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4c7de288ff]
[fv-az1937-158:61654] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4c7e2a5ff5]
[fv-az1937-158:61654] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4c7e2bb0da]
[fv-az1937-158:61654] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4c7e2a5a55]
[fv-az1937-158:61654] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4c7e2a5a6f]
[fv-az1937-158:61654] [ 8] plumed_master(+0x146dd)[0x5589789ba6dd]
[fv-az1937-158:61654] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4c7de2a1ca]
[fv-az1937-158:61654] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4c7de2a28b]
[fv-az1937-158:61654] [11] plumed_master(+0x15365)[0x5589789bb365]
[fv-az1937-158:61654] *** End of error message ***
</pre>
{% endraw %}
