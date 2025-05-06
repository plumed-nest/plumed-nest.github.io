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
[fv-az2209-645:61095] *** Process received signal ***
[fv-az2209-645:61095] Signal: Aborted (6)
[fv-az2209-645:61095] Signal code:  (-6)
[fv-az2209-645:61095] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8f5ea45330]
[fv-az2209-645:61095] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8f5ea9eb2c]
[fv-az2209-645:61095] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8f5ea4527e]
[fv-az2209-645:61095] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8f5ea288ff]
[fv-az2209-645:61095] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8f5eea5ff5]
[fv-az2209-645:61095] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8f5eebb0da]
[fv-az2209-645:61095] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8f5eea5a55]
[fv-az2209-645:61095] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8f5eea5a6f]
[fv-az2209-645:61095] [ 8] plumed(+0x146dd)[0x5595505dd6dd]
[fv-az2209-645:61095] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8f5ea2a1ca]
[fv-az2209-645:61095] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8f5ea2a28b]
[fv-az2209-645:61095] [11] plumed(+0x15365)[0x5595505de365]
[fv-az2209-645:61095] *** End of error message ***
</pre>
{% endraw %}
