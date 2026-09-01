**Project ID:** [plumID:19.017]({{ '/' | absolute_url }}eggs/19/017/)  
Stderr for source:  plumed_reweight/reweight_rho_c.dat   
Download: [zipped raw stdout](reweight_rho_c.dat.plumed.stdout.txt.zip) - [zipped raw stderr](reweight_rho_c.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
WARNING: IFile closed in the middle of reading. seems strange!
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action HISTOGRAM with label @s13 : set NORMALIZATION=true/false when using LOGWEIGHTS as otherwise the weights are ignored. Alternatively, learn to use the new syntax for histograms with KDE/ACCUMULATE to have more control over what PLUMED is calculating
[runnervmgx7h7:12705] *** Process received signal ***
[runnervmgx7h7:12705] Signal: Aborted (6)
[runnervmgx7h7:12705] Signal code:  (-6)
[runnervmgx7h7:12705] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f552b045330]
[runnervmgx7h7:12705] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f552b09ec0c]
[runnervmgx7h7:12705] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f552b04527e]
[runnervmgx7h7:12705] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f552b0288ff]
[runnervmgx7h7:12705] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f552b4a5ff5]
[runnervmgx7h7:12705] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f552b4bb0da]
[runnervmgx7h7:12705] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f552b4a5a55]
[runnervmgx7h7:12705] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f552b4a5a6f]
[runnervmgx7h7:12705] [ 8] plumed(+0x146dd)[0x5628bc6d56dd]
[runnervmgx7h7:12705] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f552b02a1ca]
[runnervmgx7h7:12705] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f552b02a28b]
[runnervmgx7h7:12705] [11] plumed(+0x15365)[0x5628bc6d6365]
[runnervmgx7h7:12705] *** End of error message ***
</pre>
{% endraw %}
