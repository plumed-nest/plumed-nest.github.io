**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  ch4-base/asymm-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @32 : keyword ARG is compulsory for this action
[runnervmw9dnm:10335] *** Process received signal ***
[runnervmw9dnm:10335] Signal: Aborted (6)
[runnervmw9dnm:10335] Signal code:  (-6)
[runnervmw9dnm:10335] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5710045330]
[runnervmw9dnm:10335] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f571009eb2c]
[runnervmw9dnm:10335] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f571004527e]
[runnervmw9dnm:10335] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f57100288ff]
[runnervmw9dnm:10335] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f57104a5ff5]
[runnervmw9dnm:10335] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f57104bb0da]
[runnervmw9dnm:10335] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f57104a5a55]
[runnervmw9dnm:10335] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f57104a5a6f]
[runnervmw9dnm:10335] [ 8] plumed_master(+0x146dd)[0x55674aa6e6dd]
[runnervmw9dnm:10335] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f571002a1ca]
[runnervmw9dnm:10335] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f571002a28b]
[runnervmw9dnm:10335] [11] plumed_master(+0x15365)[0x55674aa6f365]
[runnervmw9dnm:10335] *** End of error message ***
</pre>
{% endraw %}
