**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_GeTe.dat   
Download: [zipped raw stdout](plumed_GeTe.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_GeTe.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label cc_cmat : it was not possible to interpret atom name flq6
[fv-az1391-351:65893] *** Process received signal ***
[fv-az1391-351:65893] Signal: Aborted (6)
[fv-az1391-351:65893] Signal code:  (-6)
[fv-az1391-351:65893] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa63f845330]
[fv-az1391-351:65893] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa63f89eb2c]
[fv-az1391-351:65893] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa63f84527e]
[fv-az1391-351:65893] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa63f8288ff]
[fv-az1391-351:65893] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa63fca5ff5]
[fv-az1391-351:65893] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa63fcbb0da]
[fv-az1391-351:65893] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa63fca5a55]
[fv-az1391-351:65893] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa63fca5a6f]
[fv-az1391-351:65893] [ 8] plumed(+0x146dd)[0x55a2e21e06dd]
[fv-az1391-351:65893] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa63f82a1ca]
[fv-az1391-351:65893] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa63f82a28b]
[fv-az1391-351:65893] [11] plumed(+0x15365)[0x55a2e21e1365]
[fv-az1391-351:65893] *** End of error message ***
</pre>
{% endraw %}
