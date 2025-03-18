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
[fv-az1983-395:61093] *** Process received signal ***
[fv-az1983-395:61093] Signal: Aborted (6)
[fv-az1983-395:61093] Signal code:  (-6)
[fv-az1983-395:61093] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd519045330]
[fv-az1983-395:61093] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd51909eb2c]
[fv-az1983-395:61093] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd51904527e]
[fv-az1983-395:61093] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd5190288ff]
[fv-az1983-395:61093] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd5194a5ff5]
[fv-az1983-395:61093] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd5194bb0da]
[fv-az1983-395:61093] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd5194a5a55]
[fv-az1983-395:61093] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd5194a5a6f]
[fv-az1983-395:61093] [ 8] plumed(+0x146dd)[0x5636f84396dd]
[fv-az1983-395:61093] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd51902a1ca]
[fv-az1983-395:61093] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd51902a28b]
[fv-az1983-395:61093] [11] plumed(+0x15365)[0x5636f843a365]
[fv-az1983-395:61093] *** End of error message ***
</pre>
{% endraw %}
