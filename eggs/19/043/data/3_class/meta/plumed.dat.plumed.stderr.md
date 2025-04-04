**Project ID:** [plumID:19.043]({{ '/' | absolute_url }}eggs/19/043/)  
Stderr for source:  3_class/meta/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[fv-az1360-658:11813] *** Process received signal ***
[fv-az1360-658:11813] Signal: Aborted (6)
[fv-az1360-658:11813] Signal code:  (-6)
[fv-az1360-658:11813] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f19d4c45330]
[fv-az1360-658:11813] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f19d4c9eb2c]
[fv-az1360-658:11813] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f19d4c4527e]
[fv-az1360-658:11813] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f19d4c288ff]
[fv-az1360-658:11813] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f19d50a5ff5]
[fv-az1360-658:11813] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f19d50bb0da]
[fv-az1360-658:11813] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f19d50a5a55]
[fv-az1360-658:11813] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f19d50a5a6f]
[fv-az1360-658:11813] [ 8] plumed(+0x146dd)[0x55df031856dd]
[fv-az1360-658:11813] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f19d4c2a1ca]
[fv-az1360-658:11813] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f19d4c2a28b]
[fv-az1360-658:11813] [11] plumed(+0x15365)[0x55df03186365]
[fv-az1360-658:11813] *** End of error message ***
</pre>
{% endraw %}
