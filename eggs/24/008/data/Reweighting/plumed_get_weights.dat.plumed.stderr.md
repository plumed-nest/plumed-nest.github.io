**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_get_weights.dat   
Download: [zipped raw stdout](plumed_get_weights.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_get_weights.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[runnervmvrwv9:05446] *** Process received signal ***
[runnervmvrwv9:05446] Signal: Aborted (6)
[runnervmvrwv9:05446] Signal code:  (-6)
[runnervmvrwv9:05446] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5829c45330]
[runnervmvrwv9:05446] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5829c9eb2c]
[runnervmvrwv9:05446] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5829c4527e]
[runnervmvrwv9:05446] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5829c288ff]
[runnervmvrwv9:05446] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f582a0a5ff5]
[runnervmvrwv9:05446] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f582a0bb0da]
[runnervmvrwv9:05446] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f582a0a5a55]
[runnervmvrwv9:05446] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f582a0a5a6f]
[runnervmvrwv9:05446] [ 8] plumed(+0x146dd)[0x5651b18cd6dd]
[runnervmvrwv9:05446] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5829c2a1ca]
[runnervmvrwv9:05446] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5829c2a28b]
[runnervmvrwv9:05446] [11] plumed(+0x15365)[0x5651b18ce365]
[runnervmvrwv9:05446] *** End of error message ***
</pre>
{% endraw %}
