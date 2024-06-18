**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-3/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/RegisterBase.h:211) const Content& PLMD::RegisterBase<Content>::get(const std::vector<void*>&, const string&) const [with Content = PLMD::ActionRegisterPointers; std::string = std::__cxx11::basic_string<char>]
+++ assertion failed: m.count(key)>0
[fv-az883-206:06361] *** Process received signal ***
[fv-az883-206:06361] Signal: Aborted (6)
[fv-az883-206:06361] Signal code:  (-6)
[fv-az883-206:06361] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f3dae442520]
[fv-az883-206:06361] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f3dae4969fc]
[fv-az883-206:06361] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f3dae442476]
[fv-az883-206:06361] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f3dae4287f3]
[fv-az883-206:06361] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f3dae8a2b9e]
[fv-az883-206:06361] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f3dae8ae20c]
[fv-az883-206:06361] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f3dae8ae277]
[fv-az883-206:06361] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f3dae8ae52b]
[fv-az883-206:06361] [ 8] plumed_master(+0x14274)[0x55c782881274]
[fv-az883-206:06361] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f3dae429d90]
[fv-az883-206:06361] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f3dae429e40]
[fv-az883-206:06361] [11] plumed_master(+0x14ed5)[0x55c782881ed5]
[fv-az883-206:06361] *** End of error message ***
</pre>
{% endraw %}
