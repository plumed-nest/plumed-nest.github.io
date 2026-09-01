**Project ID:** [plumID:25.015]({{ '/' | absolute_url }}eggs/25/015/)  
Stderr for source:  PLUMED_Inputs/plumed_torsion.dat   
Download: [zipped raw stdout](plumed_torsion.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_torsion.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPATOMS with label @6 : it was not possible to interpret atom name t1_grp
[runnervmgx7h7:05421] *** Process received signal ***
[runnervmgx7h7:05421] Signal: Aborted (6)
[runnervmgx7h7:05421] Signal code:  (-6)
[runnervmgx7h7:05421] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5b93a45330]
[runnervmgx7h7:05421] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5b93a9ec0c]
[runnervmgx7h7:05421] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5b93a4527e]
[runnervmgx7h7:05421] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5b93a288ff]
[runnervmgx7h7:05421] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5b93ea5ff5]
[runnervmgx7h7:05421] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5b93ebb0da]
[runnervmgx7h7:05421] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5b93ea5a55]
[runnervmgx7h7:05421] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5b93ea5a6f]
[runnervmgx7h7:05421] [ 8] plumed(+0x146dd)[0x55f5ed5c26dd]
[runnervmgx7h7:05421] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5b93a2a1ca]
[runnervmgx7h7:05421] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5b93a2a28b]
[runnervmgx7h7:05421] [11] plumed(+0x15365)[0x55f5ed5c3365]
[runnervmgx7h7:05421] *** End of error message ***
</pre>
{% endraw %}
