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
[pkrvmq0rgcvqdmg:06317] *** Process received signal ***
[pkrvmq0rgcvqdmg:06317] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:06317] Signal code:  (-6)
[pkrvmq0rgcvqdmg:06317] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7962645330]
[pkrvmq0rgcvqdmg:06317] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f796269eb2c]
[pkrvmq0rgcvqdmg:06317] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f796264527e]
[pkrvmq0rgcvqdmg:06317] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f79626288ff]
[pkrvmq0rgcvqdmg:06317] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7962aa5ff5]
[pkrvmq0rgcvqdmg:06317] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7962abb0da]
[pkrvmq0rgcvqdmg:06317] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7962aa5a55]
[pkrvmq0rgcvqdmg:06317] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7962aa5a6f]
[pkrvmq0rgcvqdmg:06317] [ 8] plumed(+0x146dd)[0x55bdb15956dd]
[pkrvmq0rgcvqdmg:06317] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f796262a1ca]
[pkrvmq0rgcvqdmg:06317] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f796262a28b]
[pkrvmq0rgcvqdmg:06317] [11] plumed(+0x15365)[0x55bdb1596365]
[pkrvmq0rgcvqdmg:06317] *** End of error message ***
</pre>
{% endraw %}
