**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  sn2/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @33 : keyword ARG is compulsory for this action
[runnervmw9dnm:09035] *** Process received signal ***
[runnervmw9dnm:09035] Signal: Aborted (6)
[runnervmw9dnm:09035] Signal code:  (-6)
[runnervmw9dnm:09035] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8b15e45330]
[runnervmw9dnm:09035] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8b15e9eb2c]
[runnervmw9dnm:09035] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8b15e4527e]
[runnervmw9dnm:09035] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8b15e288ff]
[runnervmw9dnm:09035] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8b162a5ff5]
[runnervmw9dnm:09035] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8b162bb0da]
[runnervmw9dnm:09035] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8b162a5a55]
[runnervmw9dnm:09035] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8b162a5a6f]
[runnervmw9dnm:09035] [ 8] plumed_master(+0x146dd)[0x55d463a5f6dd]
[runnervmw9dnm:09035] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8b15e2a1ca]
[runnervmw9dnm:09035] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8b15e2a28b]
[runnervmw9dnm:09035] [11] plumed_master(+0x15365)[0x55d463a60365]
[runnervmw9dnm:09035] *** End of error message ***
</pre>
{% endraw %}
