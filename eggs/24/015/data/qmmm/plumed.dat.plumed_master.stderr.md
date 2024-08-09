**Project ID:** [plumID:24.015]({{ '/' | absolute_url }}eggs/24/015/)  
Stderr for source:  qmmm/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/RegisterBase.h:211) const Content& PLMD::RegisterBase<Content>::get(const std::vector<void*>&, const string&) const [with Content = PLMD::ActionRegisterPointers; std::string = std::__cxx11::basic_string<char>]
+++ assertion failed: m.count(key)>0
[fv-az530-623:03949] *** Process received signal ***
[fv-az530-623:03949] Signal: Aborted (6)
[fv-az530-623:03949] Signal code:  (-6)
[fv-az530-623:03949] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f7c7a642520]
[fv-az530-623:03949] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f7c7a6969fc]
[fv-az530-623:03949] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f7c7a642476]
[fv-az530-623:03949] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f7c7a6287f3]
[fv-az530-623:03949] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f7c7aaa2b9e]
[fv-az530-623:03949] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f7c7aaae20c]
[fv-az530-623:03949] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f7c7aaae277]
[fv-az530-623:03949] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f7c7aaae52b]
[fv-az530-623:03949] [ 8] plumed_master(+0x14274)[0x560b02a54274]
[fv-az530-623:03949] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f7c7a629d90]
[fv-az530-623:03949] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f7c7a629e40]
[fv-az530-623:03949] [11] plumed_master(+0x14ed5)[0x560b02a54ed5]
[fv-az530-623:03949] *** End of error message ***
</pre>
{% endraw %}
