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
[fv-az1950-95:66627] *** Process received signal ***
[fv-az1950-95:66627] Signal: Aborted (6)
[fv-az1950-95:66627] Signal code:  (-6)
[fv-az1950-95:66627] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb06c845330]
[fv-az1950-95:66627] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb06c89eb2c]
[fv-az1950-95:66627] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb06c84527e]
[fv-az1950-95:66627] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb06c8288ff]
[fv-az1950-95:66627] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb06cca5ff5]
[fv-az1950-95:66627] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb06ccbb0da]
[fv-az1950-95:66627] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb06cca5a55]
[fv-az1950-95:66627] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb06cca5a6f]
[fv-az1950-95:66627] [ 8] plumed_master(+0x146dd)[0x556e91afa6dd]
[fv-az1950-95:66627] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb06c82a1ca]
[fv-az1950-95:66627] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb06c82a28b]
[fv-az1950-95:66627] [11] plumed_master(+0x15365)[0x556e91afb365]
[fv-az1950-95:66627] *** End of error message ***
</pre>
{% endraw %}
