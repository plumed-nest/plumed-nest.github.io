**Project ID:** [plumID:25.029]({{ '/' | absolute_url }}eggs/25/029/)  
Stderr for source:  ./amor/4-reweight_amor.dat   
Download: [zipped raw stdout](4-reweight_amor.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](4-reweight_amor.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @46 : keyword ARG is compulsory for this action
[runnervmw9dnm:05632] *** Process received signal ***
[runnervmw9dnm:05632] Signal: Aborted (6)
[runnervmw9dnm:05632] Signal code:  (-6)
[runnervmw9dnm:05632] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4b8d445330]
[runnervmw9dnm:05632] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4b8d49eb2c]
[runnervmw9dnm:05632] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4b8d44527e]
[runnervmw9dnm:05632] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4b8d4288ff]
[runnervmw9dnm:05632] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4b8d8a5ff5]
[runnervmw9dnm:05632] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4b8d8bb0da]
[runnervmw9dnm:05632] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4b8d8a5a55]
[runnervmw9dnm:05632] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4b8d8a5a6f]
[runnervmw9dnm:05632] [ 8] plumed_master(+0x146dd)[0x559ae18746dd]
[runnervmw9dnm:05632] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4b8d42a1ca]
[runnervmw9dnm:05632] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4b8d42a28b]
[runnervmw9dnm:05632] [11] plumed_master(+0x15365)[0x559ae1875365]
[runnervmw9dnm:05632] *** End of error message ***
</pre>
{% endraw %}
