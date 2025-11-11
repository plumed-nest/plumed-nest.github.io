**Project ID:** [plumID:21.018]({{ '/' | absolute_url }}eggs/21/018/)  
Stderr for source:  plumed_reweight/reweight_rho_hb.dat   
Download: [zipped raw stdout](reweight_rho_hb.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweight_rho_hb.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
WARNING: IFile closed in the middle of reading. seems strange!
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @24 : keyword ARG is compulsory for this action
[runnervmw9dnm:09883] *** Process received signal ***
[runnervmw9dnm:09883] Signal: Aborted (6)
[runnervmw9dnm:09883] Signal code:  (-6)
[runnervmw9dnm:09883] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb5acc45330]
[runnervmw9dnm:09883] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb5acc9eb2c]
[runnervmw9dnm:09883] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb5acc4527e]
[runnervmw9dnm:09883] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb5acc288ff]
[runnervmw9dnm:09883] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb5ad0a5ff5]
[runnervmw9dnm:09883] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb5ad0bb0da]
[runnervmw9dnm:09883] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb5ad0a5a55]
[runnervmw9dnm:09883] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb5ad0a5a6f]
[runnervmw9dnm:09883] [ 8] plumed_master(+0x146dd)[0x55e40fc326dd]
[runnervmw9dnm:09883] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb5acc2a1ca]
[runnervmw9dnm:09883] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb5acc2a28b]
[runnervmw9dnm:09883] [11] plumed_master(+0x15365)[0x55e40fc33365]
[runnervmw9dnm:09883] *** End of error message ***
</pre>
{% endraw %}
