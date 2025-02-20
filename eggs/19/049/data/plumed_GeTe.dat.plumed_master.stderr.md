**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_GeTe.dat   
Download: [zipped raw stdout](plumed_GeTe.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_GeTe.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label cc_cmat : it was not possible to interpret atom name flq6
[fv-az1444-322:12426] *** Process received signal ***
[fv-az1444-322:12426] Signal: Aborted (6)
[fv-az1444-322:12426] Signal code:  (-6)
[fv-az1444-322:12426] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa3bf645330]
[fv-az1444-322:12426] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa3bf69eb2c]
[fv-az1444-322:12426] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa3bf64527e]
[fv-az1444-322:12426] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa3bf6288ff]
[fv-az1444-322:12426] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa3bfaa5ff5]
[fv-az1444-322:12426] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa3bfabb0da]
[fv-az1444-322:12426] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa3bfaa5a55]
[fv-az1444-322:12426] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa3bfaa5a6f]
[fv-az1444-322:12426] [ 8] plumed_master(+0x146dd)[0x55a10987a6dd]
[fv-az1444-322:12426] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa3bf62a1ca]
[fv-az1444-322:12426] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa3bf62a28b]
[fv-az1444-322:12426] [11] plumed_master(+0x15365)[0x55a10987b365]
[fv-az1444-322:12426] *** End of error message ***
</pre>
{% endraw %}
