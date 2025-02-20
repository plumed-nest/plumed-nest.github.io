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
[fv-az1374-933:06351] *** Process received signal ***
[fv-az1374-933:06351] Signal: Aborted (6)
[fv-az1374-933:06351] Signal code:  (-6)
[fv-az1374-933:06351] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4857645330]
[fv-az1374-933:06351] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f485769eb2c]
[fv-az1374-933:06351] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f485764527e]
[fv-az1374-933:06351] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f48576288ff]
[fv-az1374-933:06351] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4857aa5ff5]
[fv-az1374-933:06351] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4857abb0da]
[fv-az1374-933:06351] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4857aa5a55]
[fv-az1374-933:06351] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4857aa5a6f]
[fv-az1374-933:06351] [ 8] plumed(+0x146dd)[0x5593ba4916dd]
[fv-az1374-933:06351] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f485762a1ca]
[fv-az1374-933:06351] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f485762a28b]
[fv-az1374-933:06351] [11] plumed(+0x15365)[0x5593ba492365]
[fv-az1374-933:06351] *** End of error message ***
</pre>
{% endraw %}
