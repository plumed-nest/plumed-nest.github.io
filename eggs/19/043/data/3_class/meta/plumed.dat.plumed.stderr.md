**Project ID:** [plumID:19.043]({{ '/' | absolute_url }}eggs/19/043/)  
Stderr for source:  3_class/meta/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[fv-az1665-105:15418] *** Process received signal ***
[fv-az1665-105:15418] Signal: Aborted (6)
[fv-az1665-105:15418] Signal code:  (-6)
[fv-az1665-105:15418] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fad39445330]
[fv-az1665-105:15418] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fad3949eb2c]
[fv-az1665-105:15418] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fad3944527e]
[fv-az1665-105:15418] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fad394288ff]
[fv-az1665-105:15418] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fad398a5ff5]
[fv-az1665-105:15418] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fad398bb0da]
[fv-az1665-105:15418] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fad398a5a55]
[fv-az1665-105:15418] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fad398a5a6f]
[fv-az1665-105:15418] [ 8] plumed(+0x146dd)[0x558901e826dd]
[fv-az1665-105:15418] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fad3942a1ca]
[fv-az1665-105:15418] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fad3942a28b]
[fv-az1665-105:15418] [11] plumed(+0x15365)[0x558901e83365]
[fv-az1665-105:15418] *** End of error message ***
</pre>
{% endraw %}
