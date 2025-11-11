**Project ID:** [plumID:22.016]({{ '/' | absolute_url }}eggs/22/016/)  
Stderr for source:  SurfaceFreeEnergy/FindOptimalParameters/FindOptimalOrderParameter-SmallEnv/Liquid/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @45 : keyword ARG is compulsory for this action
[runnervmw9dnm:09612] *** Process received signal ***
[runnervmw9dnm:09612] Signal: Aborted (6)
[runnervmw9dnm:09612] Signal code:  (-6)
[runnervmw9dnm:09612] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f07cfa45330]
[runnervmw9dnm:09612] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f07cfa9eb2c]
[runnervmw9dnm:09612] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f07cfa4527e]
[runnervmw9dnm:09612] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f07cfa288ff]
[runnervmw9dnm:09612] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f07cfea5ff5]
[runnervmw9dnm:09612] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f07cfebb0da]
[runnervmw9dnm:09612] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f07cfea5a55]
[runnervmw9dnm:09612] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f07cfea5a6f]
[runnervmw9dnm:09612] [ 8] plumed_master(+0x146dd)[0x55f6ac5af6dd]
[runnervmw9dnm:09612] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f07cfa2a1ca]
[runnervmw9dnm:09612] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f07cfa2a28b]
[runnervmw9dnm:09612] [11] plumed_master(+0x15365)[0x55f6ac5b0365]
[runnervmw9dnm:09612] *** End of error message ***
</pre>
{% endraw %}
