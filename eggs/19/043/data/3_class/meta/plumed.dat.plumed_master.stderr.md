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
[fv-az1278-681:67739] *** Process received signal ***
[fv-az1278-681:67739] Signal: Aborted (6)
[fv-az1278-681:67739] Signal code:  (-6)
[fv-az1278-681:67739] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f24b5045330]
[fv-az1278-681:67739] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f24b509eb2c]
[fv-az1278-681:67739] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f24b504527e]
[fv-az1278-681:67739] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f24b50288ff]
[fv-az1278-681:67739] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f24b54a5ff5]
[fv-az1278-681:67739] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f24b54bb0da]
[fv-az1278-681:67739] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f24b54a5a55]
[fv-az1278-681:67739] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f24b54a5a6f]
[fv-az1278-681:67739] [ 8] plumed_master(+0x146dd)[0x563454aad6dd]
[fv-az1278-681:67739] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f24b502a1ca]
[fv-az1278-681:67739] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f24b502a28b]
[fv-az1278-681:67739] [11] plumed_master(+0x15365)[0x563454aae365]
[fv-az1278-681:67739] *** End of error message ***
</pre>
{% endraw %}
