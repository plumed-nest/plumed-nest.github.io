**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT/plumed_h1h2.dat   
Download: [zipped raw stdout](plumed_h1h2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_h1h2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @38 : keyword ARG is compulsory for this action
[runnervmw9dnm:06891] *** Process received signal ***
[runnervmw9dnm:06891] Signal: Aborted (6)
[runnervmw9dnm:06891] Signal code:  (-6)
[runnervmw9dnm:06891] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe186045330]
[runnervmw9dnm:06891] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe18609eb2c]
[runnervmw9dnm:06891] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe18604527e]
[runnervmw9dnm:06891] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe1860288ff]
[runnervmw9dnm:06891] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe1864a5ff5]
[runnervmw9dnm:06891] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe1864bb0da]
[runnervmw9dnm:06891] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe1864a5a55]
[runnervmw9dnm:06891] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe1864a5a6f]
[runnervmw9dnm:06891] [ 8] plumed_master(+0x146dd)[0x56390d9e06dd]
[runnervmw9dnm:06891] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe18602a1ca]
[runnervmw9dnm:06891] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe18602a28b]
[runnervmw9dnm:06891] [11] plumed_master(+0x15365)[0x56390d9e1365]
[runnervmw9dnm:06891] *** End of error message ***
</pre>
{% endraw %}
