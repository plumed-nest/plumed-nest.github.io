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
[fv-az1950-95:66611] *** Process received signal ***
[fv-az1950-95:66611] Signal: Aborted (6)
[fv-az1950-95:66611] Signal code:  (-6)
[fv-az1950-95:66611] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2664a45330]
[fv-az1950-95:66611] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2664a9eb2c]
[fv-az1950-95:66611] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2664a4527e]
[fv-az1950-95:66611] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2664a288ff]
[fv-az1950-95:66611] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2664ea5ff5]
[fv-az1950-95:66611] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2664ebb0da]
[fv-az1950-95:66611] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2664ea5a55]
[fv-az1950-95:66611] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2664ea5a6f]
[fv-az1950-95:66611] [ 8] plumed(+0x146dd)[0x56332b23c6dd]
[fv-az1950-95:66611] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2664a2a1ca]
[fv-az1950-95:66611] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2664a2a28b]
[fv-az1950-95:66611] [11] plumed(+0x15365)[0x56332b23d365]
[fv-az1950-95:66611] *** End of error message ***
</pre>
{% endraw %}
