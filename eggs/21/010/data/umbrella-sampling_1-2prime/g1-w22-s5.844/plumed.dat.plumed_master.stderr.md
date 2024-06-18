**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w22-s5.844/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/RegisterBase.h:211) const Content& PLMD::RegisterBase<Content>::get(const std::vector<void*>&, const string&) const [with Content = PLMD::ActionRegisterPointers; std::string = std::__cxx11::basic_string<char>]
+++ assertion failed: m.count(key)>0
[fv-az1215-453:07070] *** Process received signal ***
[fv-az1215-453:07070] Signal: Aborted (6)
[fv-az1215-453:07070] Signal code:  (-6)
[fv-az1215-453:07070] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f191b442520]
[fv-az1215-453:07070] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f191b4969fc]
[fv-az1215-453:07070] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f191b442476]
[fv-az1215-453:07070] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f191b4287f3]
[fv-az1215-453:07070] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f191b8a2b9e]
[fv-az1215-453:07070] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f191b8ae20c]
[fv-az1215-453:07070] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f191b8ae277]
[fv-az1215-453:07070] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f191b8ae52b]
[fv-az1215-453:07070] [ 8] plumed_master(+0x14274)[0x5649a694d274]
[fv-az1215-453:07070] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f191b429d90]
[fv-az1215-453:07070] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f191b429e40]
[fv-az1215-453:07070] [11] plumed_master(+0x14ed5)[0x5649a694ded5]
[fv-az1215-453:07070] *** End of error message ***
</pre>
{% endraw %}
