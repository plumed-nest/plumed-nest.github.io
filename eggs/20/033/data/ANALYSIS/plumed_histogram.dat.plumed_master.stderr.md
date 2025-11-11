**Project ID:** [plumID:20.033]({{ '/' | absolute_url }}eggs/20/033/)  
Stderr for source:  ANALYSIS/plumed_histogram.dat   
Download: [zipped raw stdout](plumed_histogram.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_histogram.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @20 : keyword ARG is compulsory for this action
[runnervmw9dnm:09926] *** Process received signal ***
[runnervmw9dnm:09926] Signal: Aborted (6)
[runnervmw9dnm:09926] Signal code:  (-6)
[runnervmw9dnm:09926] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa136e45330]
[runnervmw9dnm:09926] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa136e9eb2c]
[runnervmw9dnm:09926] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa136e4527e]
[runnervmw9dnm:09926] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa136e288ff]
[runnervmw9dnm:09926] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa1372a5ff5]
[runnervmw9dnm:09926] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa1372bb0da]
[runnervmw9dnm:09926] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa1372a5a55]
[runnervmw9dnm:09926] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa1372a5a6f]
[runnervmw9dnm:09926] [ 8] plumed_master(+0x146dd)[0x555f1e9f96dd]
[runnervmw9dnm:09926] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa136e2a1ca]
[runnervmw9dnm:09926] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa136e2a28b]
[runnervmw9dnm:09926] [11] plumed_master(+0x15365)[0x555f1e9fa365]
[runnervmw9dnm:09926] *** End of error message ***
</pre>
{% endraw %}
