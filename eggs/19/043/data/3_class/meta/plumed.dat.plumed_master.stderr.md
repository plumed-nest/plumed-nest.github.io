**Project ID:** [plumID:19.043]({{ '/' | absolute_url }}eggs/19/043/)  
Stderr for source:  3_class/meta/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[fv-az1360-658:11829] *** Process received signal ***
[fv-az1360-658:11829] Signal: Aborted (6)
[fv-az1360-658:11829] Signal code:  (-6)
[fv-az1360-658:11829] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fedf7645330]
[fv-az1360-658:11829] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fedf769eb2c]
[fv-az1360-658:11829] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fedf764527e]
[fv-az1360-658:11829] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fedf76288ff]
[fv-az1360-658:11829] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fedf7aa5ff5]
[fv-az1360-658:11829] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fedf7abb0da]
[fv-az1360-658:11829] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fedf7aa5a55]
[fv-az1360-658:11829] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fedf7aa5a6f]
[fv-az1360-658:11829] [ 8] plumed_master(+0x146dd)[0x564f8959c6dd]
[fv-az1360-658:11829] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fedf762a1ca]
[fv-az1360-658:11829] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fedf762a28b]
[fv-az1360-658:11829] [11] plumed_master(+0x15365)[0x564f8959d365]
[fv-az1360-658:11829] *** End of error message ***
</pre>
{% endraw %}
