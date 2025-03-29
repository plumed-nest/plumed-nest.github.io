**Project ID:** [plumID:24.033]({{ '/' | absolute_url }}eggs/24/033/)  
Stderr for source:  Plumed-nest/7q4b/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action EMMI with label gmm : REWEIGHT can only be used in parallel with 2 or more replicas
[fv-az789-879:60898] *** Process received signal ***
[fv-az789-879:60898] Signal: Aborted (6)
[fv-az789-879:60898] Signal code:  (-6)
[fv-az789-879:60898] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff284445330]
[fv-az789-879:60898] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff28449eb2c]
[fv-az789-879:60898] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff28444527e]
[fv-az789-879:60898] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff2844288ff]
[fv-az789-879:60898] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff2848a5ff5]
[fv-az789-879:60898] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff2848bb0da]
[fv-az789-879:60898] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff2848a5a55]
[fv-az789-879:60898] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff2848a5a6f]
[fv-az789-879:60898] [ 8] plumed(+0x146dd)[0x556990a626dd]
[fv-az789-879:60898] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff28442a1ca]
[fv-az789-879:60898] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff28442a28b]
[fv-az789-879:60898] [11] plumed(+0x15365)[0x556990a63365]
[fv-az789-879:60898] *** End of error message ***
</pre>
{% endraw %}
