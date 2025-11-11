**Project ID:** [plumID:24.013]({{ '/' | absolute_url }}eggs/24/013/)  
Stderr for source:  plumed_Argon_backward.dat   
Download: [zipped raw stdout](plumed_Argon_backward.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_Argon_backward.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COORDINATIONNUMBER with label @s11 : keyword MORE_THAN could not be read correctly
[runnervmw9dnm:05992] *** Process received signal ***
[runnervmw9dnm:05992] Signal: Aborted (6)
[runnervmw9dnm:05992] Signal code:  (-6)
[runnervmw9dnm:05992] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fec85445330]
[runnervmw9dnm:05992] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fec8549eb2c]
[runnervmw9dnm:05992] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fec8544527e]
[runnervmw9dnm:05992] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fec854288ff]
[runnervmw9dnm:05992] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fec858a5ff5]
[runnervmw9dnm:05992] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fec858bb0da]
[runnervmw9dnm:05992] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fec858a5a55]
[runnervmw9dnm:05992] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fec858a5a6f]
[runnervmw9dnm:05992] [ 8] plumed(+0x146dd)[0x55c1149b76dd]
[runnervmw9dnm:05992] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fec8542a1ca]
[runnervmw9dnm:05992] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fec8542a28b]
[runnervmw9dnm:05992] [11] plumed(+0x15365)[0x55c1149b8365]
[runnervmw9dnm:05992] *** End of error message ***
</pre>
{% endraw %}
