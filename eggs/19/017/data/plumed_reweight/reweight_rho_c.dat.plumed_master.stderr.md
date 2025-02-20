**Project ID:** [plumID:19.017]({{ '/' | absolute_url }}eggs/19/017/)  
Stderr for source:  plumed_reweight/reweight_rho_c.dat   
Download: [zipped raw stdout](reweight_rho_c.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweight_rho_c.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
WARNING: IFile closed in the middle of reading. seems strange!
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @17 : keyword ARG is compulsory for this action
[fv-az1372-996:13397] *** Process received signal ***
[fv-az1372-996:13397] Signal: Aborted (6)
[fv-az1372-996:13397] Signal code:  (-6)
[fv-az1372-996:13397] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff0a0e45330]
[fv-az1372-996:13397] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff0a0e9eb2c]
[fv-az1372-996:13397] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff0a0e4527e]
[fv-az1372-996:13397] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff0a0e288ff]
[fv-az1372-996:13397] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff0a12a5ff5]
[fv-az1372-996:13397] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff0a12bb0da]
[fv-az1372-996:13397] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff0a12a5a55]
[fv-az1372-996:13397] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff0a12a5a6f]
[fv-az1372-996:13397] [ 8] plumed_master(+0x146dd)[0x5638c34fb6dd]
[fv-az1372-996:13397] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff0a0e2a1ca]
[fv-az1372-996:13397] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff0a0e2a28b]
[fv-az1372-996:13397] [11] plumed_master(+0x15365)[0x5638c34fc365]
[fv-az1372-996:13397] *** End of error message ***
</pre>
{% endraw %}
