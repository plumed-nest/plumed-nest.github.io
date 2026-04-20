**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_get_weights.dat   
Download: [zipped raw stdout](plumed_get_weights.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_get_weights.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[runnervmeorf1:05421] *** Process received signal ***
[runnervmeorf1:05421] Signal: Aborted (6)
[runnervmeorf1:05421] Signal code:  (-6)
[runnervmeorf1:05421] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fda0a245330]
[runnervmeorf1:05421] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fda0a29eb2c]
[runnervmeorf1:05421] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fda0a24527e]
[runnervmeorf1:05421] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fda0a2288ff]
[runnervmeorf1:05421] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fda0a6a5ff5]
[runnervmeorf1:05421] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fda0a6bb0da]
[runnervmeorf1:05421] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fda0a6a5a55]
[runnervmeorf1:05421] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fda0a6a5a6f]
[runnervmeorf1:05421] [ 8] plumed(+0x146dd)[0x55b569c226dd]
[runnervmeorf1:05421] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fda0a22a1ca]
[runnervmeorf1:05421] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fda0a22a28b]
[runnervmeorf1:05421] [11] plumed(+0x15365)[0x55b569c23365]
[runnervmeorf1:05421] *** End of error message ***
</pre>
{% endraw %}
