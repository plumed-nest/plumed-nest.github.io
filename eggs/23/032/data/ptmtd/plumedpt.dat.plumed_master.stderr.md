**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  ptmtd/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/RegisterBase.h:211) const Content& PLMD::RegisterBase<Content>::get(const std::vector<void*>&, const string&) const [with Content = PLMD::ActionRegisterPointers; std::string = std::__cxx11::basic_string<char>]
+++ assertion failed: m.count(key)>0
[fv-az1019-654:04268] *** Process received signal ***
[fv-az1019-654:04268] Signal: Aborted (6)
[fv-az1019-654:04268] Signal code:  (-6)
[fv-az1019-654:04268] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fac07042520]
[fv-az1019-654:04268] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fac070969fc]
[fv-az1019-654:04268] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fac07042476]
[fv-az1019-654:04268] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fac070287f3]
[fv-az1019-654:04268] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fac074a2b9e]
[fv-az1019-654:04268] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fac074ae20c]
[fv-az1019-654:04268] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fac074ae277]
[fv-az1019-654:04268] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fac074ae52b]
[fv-az1019-654:04268] [ 8] plumed_master(+0x14274)[0x5581f908e274]
[fv-az1019-654:04268] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fac07029d90]
[fv-az1019-654:04268] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fac07029e40]
[fv-az1019-654:04268] [11] plumed_master(+0x14ed5)[0x5581f908eed5]
[fv-az1019-654:04268] *** End of error message ***
</pre>
{% endraw %}
