**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[runnervmeorf1:05472] *** Process received signal ***
[runnervmeorf1:05472] Signal: Aborted (6)
[runnervmeorf1:05472] Signal code:  (-6)
[runnervmeorf1:05472] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa85fc45330]
[runnervmeorf1:05472] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa85fc9eb2c]
[runnervmeorf1:05472] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa85fc4527e]
[runnervmeorf1:05472] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa85fc288ff]
[runnervmeorf1:05472] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa8600a5ff5]
[runnervmeorf1:05472] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa8600bb0da]
[runnervmeorf1:05472] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa8600a5a55]
[runnervmeorf1:05472] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa8600a5a6f]
[runnervmeorf1:05472] [ 8] plumed(+0x146dd)[0x562dd9d4e6dd]
[runnervmeorf1:05472] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa85fc2a1ca]
[runnervmeorf1:05472] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa85fc2a28b]
[runnervmeorf1:05472] [11] plumed(+0x15365)[0x562dd9d4f365]
[runnervmeorf1:05472] *** End of error message ***
</pre>
{% endraw %}
