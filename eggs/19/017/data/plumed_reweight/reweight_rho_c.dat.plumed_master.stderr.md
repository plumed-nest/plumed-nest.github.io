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
[fv-az1391-351:67031] *** Process received signal ***
[fv-az1391-351:67031] Signal: Aborted (6)
[fv-az1391-351:67031] Signal code:  (-6)
[fv-az1391-351:67031] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f55bc245330]
[fv-az1391-351:67031] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f55bc29eb2c]
[fv-az1391-351:67031] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f55bc24527e]
[fv-az1391-351:67031] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f55bc2288ff]
[fv-az1391-351:67031] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f55bc6a5ff5]
[fv-az1391-351:67031] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f55bc6bb0da]
[fv-az1391-351:67031] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f55bc6a5a55]
[fv-az1391-351:67031] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f55bc6a5a6f]
[fv-az1391-351:67031] [ 8] plumed_master(+0x146dd)[0x558a09a9d6dd]
[fv-az1391-351:67031] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f55bc22a1ca]
[fv-az1391-351:67031] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f55bc22a28b]
[fv-az1391-351:67031] [11] plumed_master(+0x15365)[0x558a09a9e365]
[fv-az1391-351:67031] *** End of error message ***
</pre>
{% endraw %}
