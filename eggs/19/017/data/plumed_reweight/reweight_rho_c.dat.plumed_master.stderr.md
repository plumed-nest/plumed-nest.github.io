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
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @17 : keyword ARG is compulsory for this action
[fv-az1781-845:66986] *** Process received signal ***
[fv-az1781-845:66986] Signal: Aborted (6)
[fv-az1781-845:66986] Signal code:  (-6)
[fv-az1781-845:66986] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcb2c445330]
[fv-az1781-845:66986] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcb2c49eb2c]
[fv-az1781-845:66986] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcb2c44527e]
[fv-az1781-845:66986] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcb2c4288ff]
[fv-az1781-845:66986] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcb2c8a5ff5]
[fv-az1781-845:66986] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcb2c8bb0da]
[fv-az1781-845:66986] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcb2c8a5a55]
[fv-az1781-845:66986] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcb2c8a5a6f]
[fv-az1781-845:66986] [ 8] plumed_master(+0x146dd)[0x55d03ad226dd]
[fv-az1781-845:66986] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcb2c42a1ca]
[fv-az1781-845:66986] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcb2c42a28b]
[fv-az1781-845:66986] [11] plumed_master(+0x15365)[0x55d03ad23365]
[fv-az1781-845:66986] *** End of error message ***
</pre>
{% endraw %}
