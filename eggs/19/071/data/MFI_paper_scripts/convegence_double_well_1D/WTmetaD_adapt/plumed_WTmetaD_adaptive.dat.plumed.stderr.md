**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/convegence_double_well_1D/WTmetaD_adapt/plumed_WTmetaD_adaptive.dat   
Download: [zipped raw stdout](plumed_WTmetaD_adaptive.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_WTmetaD_adaptive.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[runnervmgx7h7:10737] *** Process received signal ***
[runnervmgx7h7:10737] Signal: Aborted (6)
[runnervmgx7h7:10737] Signal code:  (-6)
[runnervmgx7h7:10737] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb7ff845330]
[runnervmgx7h7:10737] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb7ff89ec0c]
[runnervmgx7h7:10737] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb7ff84527e]
[runnervmgx7h7:10737] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb7ff8288ff]
[runnervmgx7h7:10737] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb7ffca5ff5]
[runnervmgx7h7:10737] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb7ffcbb0da]
[runnervmgx7h7:10737] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb7ffca5a55]
[runnervmgx7h7:10737] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb7ffca5a6f]
[runnervmgx7h7:10737] [ 8] plumed(+0x146dd)[0x55cffa6526dd]
[runnervmgx7h7:10737] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb7ff82a1ca]
[runnervmgx7h7:10737] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb7ff82a28b]
[runnervmgx7h7:10737] [11] plumed(+0x15365)[0x55cffa653365]
[runnervmgx7h7:10737] *** End of error message ***
</pre>
{% endraw %}
