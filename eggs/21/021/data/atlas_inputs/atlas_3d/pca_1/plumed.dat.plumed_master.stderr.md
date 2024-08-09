**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_3d/pca_1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/RegisterBase.h:211) const Content& PLMD::RegisterBase<Content>::get(const std::vector<void*>&, const string&) const [with Content = PLMD::ActionRegisterPointers; std::string = std::__cxx11::basic_string<char>]
+++ assertion failed: m.count(key)>0
[fv-az1446-488:06935] *** Process received signal ***
[fv-az1446-488:06935] Signal: Aborted (6)
[fv-az1446-488:06935] Signal code:  (-6)
[fv-az1446-488:06935] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f0348a42520]
[fv-az1446-488:06935] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f0348a969fc]
[fv-az1446-488:06935] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f0348a42476]
[fv-az1446-488:06935] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f0348a287f3]
[fv-az1446-488:06935] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f0348ea2b9e]
[fv-az1446-488:06935] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f0348eae20c]
[fv-az1446-488:06935] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f0348eae277]
[fv-az1446-488:06935] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f0348eae52b]
[fv-az1446-488:06935] [ 8] plumed_master(+0x14274)[0x56412e6c3274]
[fv-az1446-488:06935] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f0348a29d90]
[fv-az1446-488:06935] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f0348a29e40]
[fv-az1446-488:06935] [11] plumed_master(+0x14ed5)[0x56412e6c3ed5]
[fv-az1446-488:06935] *** End of error message ***
</pre>
{% endraw %}
