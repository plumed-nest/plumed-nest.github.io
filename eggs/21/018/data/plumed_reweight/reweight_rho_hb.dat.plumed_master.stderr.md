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
[runnervmkj6or:07845] *** Process received signal ***
[runnervmkj6or:07845] Signal: Aborted (6)
[runnervmkj6or:07845] Signal code:  (-6)
[runnervmkj6or:07845] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9e84445330]
[runnervmkj6or:07845] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9e8449eb2c]
[runnervmkj6or:07845] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9e8444527e]
[runnervmkj6or:07845] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9e844288ff]
[runnervmkj6or:07845] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9e848a5ff5]
[runnervmkj6or:07845] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9e848bb0da]
[runnervmkj6or:07845] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9e848a5a55]
[runnervmkj6or:07845] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9e848a5a6f]
[runnervmkj6or:07845] [ 8] plumed_master(+0x146dd)[0x55cba23146dd]
[runnervmkj6or:07845] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9e8442a1ca]
[runnervmkj6or:07845] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9e8442a28b]
[runnervmkj6or:07845] [11] plumed_master(+0x15365)[0x55cba2315365]
[runnervmkj6or:07845] *** End of error message ***
</pre>
{% endraw %}
