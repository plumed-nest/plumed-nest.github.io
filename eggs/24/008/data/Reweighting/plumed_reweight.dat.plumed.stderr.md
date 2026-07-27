**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[runnervmvrwv9:05497] *** Process received signal ***
[runnervmvrwv9:05497] Signal: Aborted (6)
[runnervmvrwv9:05497] Signal code:  (-6)
[runnervmvrwv9:05497] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f23a5245330]
[runnervmvrwv9:05497] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f23a529eb2c]
[runnervmvrwv9:05497] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f23a524527e]
[runnervmvrwv9:05497] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f23a52288ff]
[runnervmvrwv9:05497] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f23a56a5ff5]
[runnervmvrwv9:05497] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f23a56bb0da]
[runnervmvrwv9:05497] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f23a56a5a55]
[runnervmvrwv9:05497] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f23a56a5a6f]
[runnervmvrwv9:05497] [ 8] plumed(+0x146dd)[0x55b94600e6dd]
[runnervmvrwv9:05497] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f23a522a1ca]
[runnervmvrwv9:05497] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f23a522a28b]
[runnervmvrwv9:05497] [11] plumed(+0x15365)[0x55b94600f365]
[runnervmvrwv9:05497] *** End of error message ***
</pre>
{% endraw %}
