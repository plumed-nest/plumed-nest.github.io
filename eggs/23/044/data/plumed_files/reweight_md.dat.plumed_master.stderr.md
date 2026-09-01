**Project ID:** [plumID:23.044]({{ '/' | absolute_url }}eggs/23/044/)  
Stderr for source:  plumed_files/reweight_md.dat   
Download: [zipped raw stdout](reweight_md.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweight_md.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @22 : keyword ARG is compulsory for this action
[runnervmgx7h7:06964] *** Process received signal ***
[runnervmgx7h7:06964] Signal: Aborted (6)
[runnervmgx7h7:06964] Signal code:  (-6)
[runnervmgx7h7:06964] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f066b245330]
[runnervmgx7h7:06964] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f066b29ec0c]
[runnervmgx7h7:06964] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f066b24527e]
[runnervmgx7h7:06964] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f066b2288ff]
[runnervmgx7h7:06964] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f066b6a5ff5]
[runnervmgx7h7:06964] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f066b6bb0da]
[runnervmgx7h7:06964] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f066b6a5a55]
[runnervmgx7h7:06964] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f066b6a5a6f]
[runnervmgx7h7:06964] [ 8] plumed_master(+0x146dd)[0x5639642916dd]
[runnervmgx7h7:06964] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f066b22a1ca]
[runnervmgx7h7:06964] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f066b22a28b]
[runnervmgx7h7:06964] [11] plumed_master(+0x15365)[0x563964292365]
[runnervmgx7h7:06964] *** End of error message ***
</pre>
{% endraw %}
