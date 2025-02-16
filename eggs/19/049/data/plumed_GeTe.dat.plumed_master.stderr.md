**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_GeTe.dat   
Download: [zipped raw stdout](plumed_GeTe.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_GeTe.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label cc_cmat : it was not possible to interpret atom name flq6
[fv-az787-589:67774] *** Process received signal ***
[fv-az787-589:67774] Signal: Aborted (6)
[fv-az787-589:67774] Signal code:  (-6)
[fv-az787-589:67774] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7dca445330]
[fv-az787-589:67774] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7dca49eb2c]
[fv-az787-589:67774] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7dca44527e]
[fv-az787-589:67774] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7dca4288ff]
[fv-az787-589:67774] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7dca8a5ff5]
[fv-az787-589:67774] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7dca8bb0da]
[fv-az787-589:67774] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7dca8a5a55]
[fv-az787-589:67774] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7dca8a5a6f]
[fv-az787-589:67774] [ 8] plumed_master(+0x146dd)[0x55dbdd7276dd]
[fv-az787-589:67774] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7dca42a1ca]
[fv-az787-589:67774] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7dca42a28b]
[fv-az787-589:67774] [11] plumed_master(+0x15365)[0x55dbdd728365]
[fv-az787-589:67774] *** End of error message ***
</pre>
{% endraw %}
