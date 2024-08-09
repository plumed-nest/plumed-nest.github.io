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
[fv-az1019-654:06971] *** Process received signal ***
[fv-az1019-654:06971] Signal: Aborted (6)
[fv-az1019-654:06971] Signal code:  (-6)
[fv-az1019-654:06971] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f48bde42520]
[fv-az1019-654:06971] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f48bde969fc]
[fv-az1019-654:06971] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f48bde42476]
[fv-az1019-654:06971] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f48bde287f3]
[fv-az1019-654:06971] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f48be2a2b9e]
[fv-az1019-654:06971] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f48be2ae20c]
[fv-az1019-654:06971] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f48be2ae277]
[fv-az1019-654:06971] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f48be2ae52b]
[fv-az1019-654:06971] [ 8] plumed_master(+0x14274)[0x55a483026274]
[fv-az1019-654:06971] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f48bde29d90]
[fv-az1019-654:06971] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f48bde29e40]
[fv-az1019-654:06971] [11] plumed_master(+0x14ed5)[0x55a483026ed5]
[fv-az1019-654:06971] *** End of error message ***
</pre>
{% endraw %}
