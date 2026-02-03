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
[runnervmkj6or:04882] *** Process received signal ***
[runnervmkj6or:04882] Signal: Aborted (6)
[runnervmkj6or:04882] Signal code:  (-6)
[runnervmkj6or:04882] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f98fca45330]
[runnervmkj6or:04882] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f98fca9eb2c]
[runnervmkj6or:04882] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f98fca4527e]
[runnervmkj6or:04882] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f98fca288ff]
[runnervmkj6or:04882] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f98fcea5ff5]
[runnervmkj6or:04882] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f98fcebb0da]
[runnervmkj6or:04882] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f98fcea5a55]
[runnervmkj6or:04882] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f98fcea5a6f]
[runnervmkj6or:04882] [ 8] plumed_master(+0x146dd)[0x55aba36ee6dd]
[runnervmkj6or:04882] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f98fca2a1ca]
[runnervmkj6or:04882] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f98fca2a28b]
[runnervmkj6or:04882] [11] plumed_master(+0x15365)[0x55aba36ef365]
[runnervmkj6or:04882] *** End of error message ***
</pre>
{% endraw %}
