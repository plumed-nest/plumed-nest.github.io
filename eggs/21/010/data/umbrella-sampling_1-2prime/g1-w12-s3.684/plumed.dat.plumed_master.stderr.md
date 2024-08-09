**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w12-s3.684/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/RegisterBase.h:211) const Content& PLMD::RegisterBase<Content>::get(const std::vector<void*>&, const string&) const [with Content = PLMD::ActionRegisterPointers; std::string = std::__cxx11::basic_string<char>]
+++ assertion failed: m.count(key)>0
[fv-az1019-654:06781] *** Process received signal ***
[fv-az1019-654:06781] Signal: Aborted (6)
[fv-az1019-654:06781] Signal code:  (-6)
[fv-az1019-654:06781] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7effe7242520]
[fv-az1019-654:06781] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7effe72969fc]
[fv-az1019-654:06781] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7effe7242476]
[fv-az1019-654:06781] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7effe72287f3]
[fv-az1019-654:06781] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7effe76a2b9e]
[fv-az1019-654:06781] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7effe76ae20c]
[fv-az1019-654:06781] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7effe76ae277]
[fv-az1019-654:06781] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7effe76ae52b]
[fv-az1019-654:06781] [ 8] plumed_master(+0x14274)[0x5588fd933274]
[fv-az1019-654:06781] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7effe7229d90]
[fv-az1019-654:06781] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7effe7229e40]
[fv-az1019-654:06781] [11] plumed_master(+0x14ed5)[0x5588fd933ed5]
[fv-az1019-654:06781] *** End of error message ***
</pre>
{% endraw %}
