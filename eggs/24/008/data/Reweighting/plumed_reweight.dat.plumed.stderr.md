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
[fv-az1374-933:06403] *** Process received signal ***
[fv-az1374-933:06403] Signal: Aborted (6)
[fv-az1374-933:06403] Signal code:  (-6)
[fv-az1374-933:06403] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbf38a45330]
[fv-az1374-933:06403] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbf38a9eb2c]
[fv-az1374-933:06403] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbf38a4527e]
[fv-az1374-933:06403] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbf38a288ff]
[fv-az1374-933:06403] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbf38ea5ff5]
[fv-az1374-933:06403] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbf38ebb0da]
[fv-az1374-933:06403] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbf38ea5a55]
[fv-az1374-933:06403] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbf38ea5a6f]
[fv-az1374-933:06403] [ 8] plumed(+0x146dd)[0x5599237a56dd]
[fv-az1374-933:06403] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbf38a2a1ca]
[fv-az1374-933:06403] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbf38a2a28b]
[fv-az1374-933:06403] [11] plumed(+0x15365)[0x5599237a6365]
[fv-az1374-933:06403] *** End of error message ***
</pre>
{% endraw %}
