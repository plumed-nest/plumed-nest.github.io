**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w1-s1.308/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/RegisterBase.h:211) const Content& PLMD::RegisterBase<Content>::get(const std::vector<void*>&, const string&) const [with Content = PLMD::ActionRegisterPointers; std::string = std::__cxx11::basic_string<char>]
+++ assertion failed: m.count(key)>0
[fv-az1215-453:06629] *** Process received signal ***
[fv-az1215-453:06629] Signal: Aborted (6)
[fv-az1215-453:06629] Signal code:  (-6)
[fv-az1215-453:06629] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f9f10842520]
[fv-az1215-453:06629] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f9f108969fc]
[fv-az1215-453:06629] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f9f10842476]
[fv-az1215-453:06629] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f9f108287f3]
[fv-az1215-453:06629] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f9f10ca2b9e]
[fv-az1215-453:06629] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f9f10cae20c]
[fv-az1215-453:06629] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f9f10cae277]
[fv-az1215-453:06629] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f9f10cae52b]
[fv-az1215-453:06629] [ 8] plumed_master(+0x14274)[0x55a3eaa68274]
[fv-az1215-453:06629] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f9f10829d90]
[fv-az1215-453:06629] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f9f10829e40]
[fv-az1215-453:06629] [11] plumed_master(+0x14ed5)[0x55a3eaa68ed5]
[fv-az1215-453:06629] *** End of error message ***
</pre>
{% endraw %}
