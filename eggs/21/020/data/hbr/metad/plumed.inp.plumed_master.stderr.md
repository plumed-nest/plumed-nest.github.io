**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/metad/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @41 : keyword ARG is compulsory for this action
[runnervmw9dnm:09188] *** Process received signal ***
[runnervmw9dnm:09188] Signal: Aborted (6)
[runnervmw9dnm:09188] Signal code:  (-6)
[runnervmw9dnm:09188] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc131445330]
[runnervmw9dnm:09188] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc13149eb2c]
[runnervmw9dnm:09188] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc13144527e]
[runnervmw9dnm:09188] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc1314288ff]
[runnervmw9dnm:09188] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc1318a5ff5]
[runnervmw9dnm:09188] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc1318bb0da]
[runnervmw9dnm:09188] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc1318a5a55]
[runnervmw9dnm:09188] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc1318a5a6f]
[runnervmw9dnm:09188] [ 8] plumed_master(+0x146dd)[0x563cdd2686dd]
[runnervmw9dnm:09188] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc13142a1ca]
[runnervmw9dnm:09188] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc13142a28b]
[runnervmw9dnm:09188] [11] plumed_master(+0x15365)[0x563cdd269365]
[runnervmw9dnm:09188] *** End of error message ***
</pre>
{% endraw %}
