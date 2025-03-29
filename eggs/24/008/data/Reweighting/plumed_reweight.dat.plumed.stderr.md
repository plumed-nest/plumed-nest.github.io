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
[fv-az789-879:62158] *** Process received signal ***
[fv-az789-879:62158] Signal: Aborted (6)
[fv-az789-879:62158] Signal code:  (-6)
[fv-az789-879:62158] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efee0c45330]
[fv-az789-879:62158] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efee0c9eb2c]
[fv-az789-879:62158] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efee0c4527e]
[fv-az789-879:62158] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efee0c288ff]
[fv-az789-879:62158] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efee10a5ff5]
[fv-az789-879:62158] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efee10bb0da]
[fv-az789-879:62158] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efee10a5a55]
[fv-az789-879:62158] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efee10a5a6f]
[fv-az789-879:62158] [ 8] plumed(+0x146dd)[0x5645fd8566dd]
[fv-az789-879:62158] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efee0c2a1ca]
[fv-az789-879:62158] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efee0c2a28b]
[fv-az789-879:62158] [11] plumed(+0x15365)[0x5645fd857365]
[fv-az789-879:62158] *** End of error message ***
</pre>
{% endraw %}
