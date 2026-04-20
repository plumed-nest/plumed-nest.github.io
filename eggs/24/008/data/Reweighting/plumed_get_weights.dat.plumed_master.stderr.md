**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_get_weights.dat   
Download: [zipped raw stdout](plumed_get_weights.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_get_weights.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[runnervmeorf1:05436] *** Process received signal ***
[runnervmeorf1:05436] Signal: Aborted (6)
[runnervmeorf1:05436] Signal code:  (-6)
[runnervmeorf1:05436] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f46bba45330]
[runnervmeorf1:05436] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f46bba9eb2c]
[runnervmeorf1:05436] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f46bba4527e]
[runnervmeorf1:05436] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f46bba288ff]
[runnervmeorf1:05436] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f46bbea5ff5]
[runnervmeorf1:05436] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f46bbebb0da]
[runnervmeorf1:05436] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f46bbea5a55]
[runnervmeorf1:05436] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f46bbea5a6f]
[runnervmeorf1:05436] [ 8] plumed_master(+0x146dd)[0x556fd3f256dd]
[runnervmeorf1:05436] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f46bba2a1ca]
[runnervmeorf1:05436] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f46bba2a28b]
[runnervmeorf1:05436] [11] plumed_master(+0x15365)[0x556fd3f26365]
[runnervmeorf1:05436] *** End of error message ***
</pre>
{% endraw %}
