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
[fv-az1680-626:06770] *** Process received signal ***
[fv-az1680-626:06770] Signal: Aborted (6)
[fv-az1680-626:06770] Signal code:  (-6)
[fv-az1680-626:06770] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1617a45330]
[fv-az1680-626:06770] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1617a9eb2c]
[fv-az1680-626:06770] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1617a4527e]
[fv-az1680-626:06770] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1617a288ff]
[fv-az1680-626:06770] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1617ea5ff5]
[fv-az1680-626:06770] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1617ebb0da]
[fv-az1680-626:06770] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1617ea5a55]
[fv-az1680-626:06770] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1617ea5a6f]
[fv-az1680-626:06770] [ 8] plumed(+0x146dd)[0x562b8387e6dd]
[fv-az1680-626:06770] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1617a2a1ca]
[fv-az1680-626:06770] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1617a2a28b]
[fv-az1680-626:06770] [11] plumed(+0x15365)[0x562b8387f365]
[fv-az1680-626:06770] *** End of error message ***
</pre>
{% endraw %}
