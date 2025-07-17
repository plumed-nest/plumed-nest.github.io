**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[pkrvmq0rgcvqdmg:06333] *** Process received signal ***
[pkrvmq0rgcvqdmg:06333] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:06333] Signal code:  (-6)
[pkrvmq0rgcvqdmg:06333] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdc54445330]
[pkrvmq0rgcvqdmg:06333] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdc5449eb2c]
[pkrvmq0rgcvqdmg:06333] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdc5444527e]
[pkrvmq0rgcvqdmg:06333] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdc544288ff]
[pkrvmq0rgcvqdmg:06333] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdc548a5ff5]
[pkrvmq0rgcvqdmg:06333] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdc548bb0da]
[pkrvmq0rgcvqdmg:06333] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdc548a5a55]
[pkrvmq0rgcvqdmg:06333] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdc548a5a6f]
[pkrvmq0rgcvqdmg:06333] [ 8] plumed_master(+0x146dd)[0x559d12f246dd]
[pkrvmq0rgcvqdmg:06333] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdc5442a1ca]
[pkrvmq0rgcvqdmg:06333] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdc5442a28b]
[pkrvmq0rgcvqdmg:06333] [11] plumed_master(+0x15365)[0x559d12f25365]
[pkrvmq0rgcvqdmg:06333] *** End of error message ***
</pre>
{% endraw %}
