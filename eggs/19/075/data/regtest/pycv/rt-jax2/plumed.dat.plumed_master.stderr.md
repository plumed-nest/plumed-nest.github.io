**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-jax2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/RegisterBase.h:211) const Content& PLMD::RegisterBase<Content>::get(const std::vector<void*>&, const string&) const [with Content = PLMD::ActionRegisterPointers; std::string = std::__cxx11::basic_string<char>]
+++ assertion failed: m.count(key)>0
[fv-az1269-668:06441] *** Process received signal ***
[fv-az1269-668:06441] Signal: Aborted (6)
[fv-az1269-668:06441] Signal code:  (-6)
[fv-az1269-668:06441] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f721f042520]
[fv-az1269-668:06441] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f721f0969fc]
[fv-az1269-668:06441] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f721f042476]
[fv-az1269-668:06441] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f721f0287f3]
[fv-az1269-668:06441] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f721f4a2b9e]
[fv-az1269-668:06441] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f721f4ae20c]
[fv-az1269-668:06441] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f721f4ae277]
[fv-az1269-668:06441] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f721f4ae52b]
[fv-az1269-668:06441] [ 8] plumed_master(+0x14274)[0x5636e7a55274]
[fv-az1269-668:06441] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f721f029d90]
[fv-az1269-668:06441] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f721f029e40]
[fv-az1269-668:06441] [11] plumed_master(+0x14ed5)[0x5636e7a55ed5]
[fv-az1269-668:06441] *** End of error message ***
</pre>
{% endraw %}
