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
[fv-az1909-454:66005] *** Process received signal ***
[fv-az1909-454:66005] Signal: Aborted (6)
[fv-az1909-454:66005] Signal code:  (-6)
[fv-az1909-454:66005] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa4e5e45330]
[fv-az1909-454:66005] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa4e5e9eb2c]
[fv-az1909-454:66005] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa4e5e4527e]
[fv-az1909-454:66005] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa4e5e288ff]
[fv-az1909-454:66005] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa4e62a5ff5]
[fv-az1909-454:66005] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa4e62bb0da]
[fv-az1909-454:66005] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa4e62a5a55]
[fv-az1909-454:66005] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa4e62a5a6f]
[fv-az1909-454:66005] [ 8] plumed(+0x146dd)[0x55bc8d4fb6dd]
[fv-az1909-454:66005] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa4e5e2a1ca]
[fv-az1909-454:66005] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa4e5e2a28b]
[fv-az1909-454:66005] [11] plumed(+0x15365)[0x55bc8d4fc365]
[fv-az1909-454:66005] *** End of error message ***
</pre>
{% endraw %}
