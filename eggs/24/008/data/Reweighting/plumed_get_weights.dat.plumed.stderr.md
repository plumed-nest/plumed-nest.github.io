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
[pkrvmxyh4eaekms:07684] *** Process received signal ***
[pkrvmxyh4eaekms:07684] Signal: Aborted (6)
[pkrvmxyh4eaekms:07684] Signal code:  (-6)
[pkrvmxyh4eaekms:07684] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f07d7845330]
[pkrvmxyh4eaekms:07684] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f07d789eb2c]
[pkrvmxyh4eaekms:07684] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f07d784527e]
[pkrvmxyh4eaekms:07684] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f07d78288ff]
[pkrvmxyh4eaekms:07684] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f07d7ca5ff5]
[pkrvmxyh4eaekms:07684] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f07d7cbb0da]
[pkrvmxyh4eaekms:07684] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f07d7ca5a55]
[pkrvmxyh4eaekms:07684] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f07d7ca5a6f]
[pkrvmxyh4eaekms:07684] [ 8] plumed(+0x146dd)[0x55c0b0dc26dd]
[pkrvmxyh4eaekms:07684] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f07d782a1ca]
[pkrvmxyh4eaekms:07684] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f07d782a28b]
[pkrvmxyh4eaekms:07684] [11] plumed(+0x15365)[0x55c0b0dc3365]
[pkrvmxyh4eaekms:07684] *** End of error message ***
</pre>
{% endraw %}
