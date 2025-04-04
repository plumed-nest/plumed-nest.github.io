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
[fv-az1680-626:06718] *** Process received signal ***
[fv-az1680-626:06718] Signal: Aborted (6)
[fv-az1680-626:06718] Signal code:  (-6)
[fv-az1680-626:06718] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcae0645330]
[fv-az1680-626:06718] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcae069eb2c]
[fv-az1680-626:06718] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcae064527e]
[fv-az1680-626:06718] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcae06288ff]
[fv-az1680-626:06718] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcae0aa5ff5]
[fv-az1680-626:06718] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcae0abb0da]
[fv-az1680-626:06718] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcae0aa5a55]
[fv-az1680-626:06718] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcae0aa5a6f]
[fv-az1680-626:06718] [ 8] plumed(+0x146dd)[0x55a9a66956dd]
[fv-az1680-626:06718] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcae062a1ca]
[fv-az1680-626:06718] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcae062a28b]
[fv-az1680-626:06718] [11] plumed(+0x15365)[0x55a9a6696365]
[fv-az1680-626:06718] *** End of error message ***
</pre>
{% endraw %}
