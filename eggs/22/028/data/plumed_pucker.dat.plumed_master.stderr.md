**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[runnervmgx7h7:07824] *** Process received signal ***
[runnervmgx7h7:07824] Signal: Aborted (6)
[runnervmgx7h7:07824] Signal code:  (-6)
[runnervmgx7h7:07824] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f74a7a45330]
[runnervmgx7h7:07824] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f74a7a9ec0c]
[runnervmgx7h7:07824] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f74a7a4527e]
[runnervmgx7h7:07824] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f74a7a288ff]
[runnervmgx7h7:07824] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f74a7ea5ff5]
[runnervmgx7h7:07824] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f74a7ebb0da]
[runnervmgx7h7:07824] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f74a7ea5a55]
[runnervmgx7h7:07824] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f74a7ea5a6f]
[runnervmgx7h7:07824] [ 8] plumed_master(+0x146dd)[0x555ada2366dd]
[runnervmgx7h7:07824] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f74a7a2a1ca]
[runnervmgx7h7:07824] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f74a7a2a28b]
[runnervmgx7h7:07824] [11] plumed_master(+0x15365)[0x555ada237365]
[runnervmgx7h7:07824] *** End of error message ***
</pre>
{% endraw %}
