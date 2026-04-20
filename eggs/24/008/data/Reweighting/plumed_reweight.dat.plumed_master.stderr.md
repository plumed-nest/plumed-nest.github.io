**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[runnervmeorf1:05487] *** Process received signal ***
[runnervmeorf1:05487] Signal: Aborted (6)
[runnervmeorf1:05487] Signal code:  (-6)
[runnervmeorf1:05487] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0236a45330]
[runnervmeorf1:05487] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0236a9eb2c]
[runnervmeorf1:05487] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0236a4527e]
[runnervmeorf1:05487] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0236a288ff]
[runnervmeorf1:05487] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0236ea5ff5]
[runnervmeorf1:05487] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0236ebb0da]
[runnervmeorf1:05487] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0236ea5a55]
[runnervmeorf1:05487] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0236ea5a6f]
[runnervmeorf1:05487] [ 8] plumed_master(+0x146dd)[0x55eed4c3b6dd]
[runnervmeorf1:05487] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0236a2a1ca]
[runnervmeorf1:05487] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0236a2a28b]
[runnervmeorf1:05487] [11] plumed_master(+0x15365)[0x55eed4c3c365]
[runnervmeorf1:05487] *** End of error message ***
</pre>
{% endraw %}
