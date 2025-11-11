**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @41 : keyword ARG is compulsory for this action
[runnervmw9dnm:09099] *** Process received signal ***
[runnervmw9dnm:09099] Signal: Aborted (6)
[runnervmw9dnm:09099] Signal code:  (-6)
[runnervmw9dnm:09099] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9a9b845330]
[runnervmw9dnm:09099] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9a9b89eb2c]
[runnervmw9dnm:09099] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9a9b84527e]
[runnervmw9dnm:09099] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9a9b8288ff]
[runnervmw9dnm:09099] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9a9bca5ff5]
[runnervmw9dnm:09099] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9a9bcbb0da]
[runnervmw9dnm:09099] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9a9bca5a55]
[runnervmw9dnm:09099] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9a9bca5a6f]
[runnervmw9dnm:09099] [ 8] plumed_master(+0x146dd)[0x562d94d846dd]
[runnervmw9dnm:09099] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9a9b82a1ca]
[runnervmw9dnm:09099] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9a9b82a28b]
[runnervmw9dnm:09099] [11] plumed_master(+0x15365)[0x562d94d85365]
[runnervmw9dnm:09099] *** End of error message ***
</pre>
{% endraw %}
