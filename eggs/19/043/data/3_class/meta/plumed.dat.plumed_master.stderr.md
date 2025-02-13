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
[fv-az1665-105:15434] *** Process received signal ***
[fv-az1665-105:15434] Signal: Aborted (6)
[fv-az1665-105:15434] Signal code:  (-6)
[fv-az1665-105:15434] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efe93045330]
[fv-az1665-105:15434] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efe9309eb2c]
[fv-az1665-105:15434] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efe9304527e]
[fv-az1665-105:15434] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efe930288ff]
[fv-az1665-105:15434] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efe934a5ff5]
[fv-az1665-105:15434] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efe934bb0da]
[fv-az1665-105:15434] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efe934a5a55]
[fv-az1665-105:15434] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efe934a5a6f]
[fv-az1665-105:15434] [ 8] plumed_master(+0x146dd)[0x564f1c4126dd]
[fv-az1665-105:15434] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efe9302a1ca]
[fv-az1665-105:15434] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efe9302a28b]
[fv-az1665-105:15434] [11] plumed_master(+0x15365)[0x564f1c413365]
[fv-az1665-105:15434] *** End of error message ***
</pre>
{% endraw %}
