**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @24 : keyword ARG is compulsory for this action
[runnervmw9dnm:06852] *** Process received signal ***
[runnervmw9dnm:06852] Signal: Aborted (6)
[runnervmw9dnm:06852] Signal code:  (-6)
[runnervmw9dnm:06852] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff34f245330]
[runnervmw9dnm:06852] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff34f29eb2c]
[runnervmw9dnm:06852] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff34f24527e]
[runnervmw9dnm:06852] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff34f2288ff]
[runnervmw9dnm:06852] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff34f6a5ff5]
[runnervmw9dnm:06852] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff34f6bb0da]
[runnervmw9dnm:06852] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff34f6a5a55]
[runnervmw9dnm:06852] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff34f6a5a6f]
[runnervmw9dnm:06852] [ 8] plumed_master(+0x146dd)[0x55aaff49c6dd]
[runnervmw9dnm:06852] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff34f22a1ca]
[runnervmw9dnm:06852] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff34f22a28b]
[runnervmw9dnm:06852] [11] plumed_master(+0x15365)[0x55aaff49d365]
[runnervmw9dnm:06852] *** End of error message ***
</pre>
{% endraw %}
