**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w18-s4.980/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/RegisterBase.h:211) const Content& PLMD::RegisterBase<Content>::get(const std::vector<void*>&, const string&) const [with Content = PLMD::ActionRegisterPointers; std::string = std::__cxx11::basic_string<char>]
+++ assertion failed: m.count(key)>0
[fv-az1215-453:06912] *** Process received signal ***
[fv-az1215-453:06912] Signal: Aborted (6)
[fv-az1215-453:06912] Signal code:  (-6)
[fv-az1215-453:06912] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f1a5ee42520]
[fv-az1215-453:06912] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f1a5ee969fc]
[fv-az1215-453:06912] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f1a5ee42476]
[fv-az1215-453:06912] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f1a5ee287f3]
[fv-az1215-453:06912] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f1a5f2a2b9e]
[fv-az1215-453:06912] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f1a5f2ae20c]
[fv-az1215-453:06912] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f1a5f2ae277]
[fv-az1215-453:06912] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f1a5f2ae52b]
[fv-az1215-453:06912] [ 8] plumed_master(+0x14274)[0x5632c84e6274]
[fv-az1215-453:06912] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f1a5ee29d90]
[fv-az1215-453:06912] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f1a5ee29e40]
[fv-az1215-453:06912] [11] plumed_master(+0x14ed5)[0x5632c84e6ed5]
[fv-az1215-453:06912] *** End of error message ***
</pre>
{% endraw %}
