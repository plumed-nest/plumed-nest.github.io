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
[pkrvmq0rgcvqdmg:06265] *** Process received signal ***
[pkrvmq0rgcvqdmg:06265] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:06265] Signal code:  (-6)
[pkrvmq0rgcvqdmg:06265] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8751e45330]
[pkrvmq0rgcvqdmg:06265] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8751e9eb2c]
[pkrvmq0rgcvqdmg:06265] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8751e4527e]
[pkrvmq0rgcvqdmg:06265] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8751e288ff]
[pkrvmq0rgcvqdmg:06265] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f87522a5ff5]
[pkrvmq0rgcvqdmg:06265] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f87522bb0da]
[pkrvmq0rgcvqdmg:06265] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f87522a5a55]
[pkrvmq0rgcvqdmg:06265] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f87522a5a6f]
[pkrvmq0rgcvqdmg:06265] [ 8] plumed(+0x146dd)[0x55df16d3b6dd]
[pkrvmq0rgcvqdmg:06265] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8751e2a1ca]
[pkrvmq0rgcvqdmg:06265] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8751e2a28b]
[pkrvmq0rgcvqdmg:06265] [11] plumed(+0x15365)[0x55df16d3c365]
[pkrvmq0rgcvqdmg:06265] *** End of error message ***
</pre>
{% endraw %}
