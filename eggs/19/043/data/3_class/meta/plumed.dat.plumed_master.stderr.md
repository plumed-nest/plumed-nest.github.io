**Project ID:** [plumID:19.043]({{ '/' | absolute_url }}eggs/19/043/)  
Stderr for source:  3_class/meta/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[fv-az1781-845:66775] *** Process received signal ***
[fv-az1781-845:66775] Signal: Aborted (6)
[fv-az1781-845:66775] Signal code:  (-6)
[fv-az1781-845:66775] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fec33045330]
[fv-az1781-845:66775] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fec3309eb2c]
[fv-az1781-845:66775] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fec3304527e]
[fv-az1781-845:66775] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fec330288ff]
[fv-az1781-845:66775] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fec334a5ff5]
[fv-az1781-845:66775] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fec334bb0da]
[fv-az1781-845:66775] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fec334a5a55]
[fv-az1781-845:66775] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fec334a5a6f]
[fv-az1781-845:66775] [ 8] plumed_master(+0x146dd)[0x55669de1e6dd]
[fv-az1781-845:66775] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fec3302a1ca]
[fv-az1781-845:66775] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fec3302a28b]
[fv-az1781-845:66775] [11] plumed_master(+0x15365)[0x55669de1f365]
[fv-az1781-845:66775] *** End of error message ***
</pre>
{% endraw %}
