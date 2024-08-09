**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  FFH_scripts/plumed_FFH.dat   
Download: [zipped raw stdout](plumed_FFH.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_FFH.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/RegisterBase.h:211) const Content& PLMD::RegisterBase<Content>::get(const std::vector<void*>&, const string&) const [with Content = PLMD::ActionRegisterPointers; std::string = std::__cxx11::basic_string<char>]
+++ assertion failed: m.count(key)>0
[fv-az1446-488:06807] *** Process received signal ***
[fv-az1446-488:06807] Signal: Aborted (6)
[fv-az1446-488:06807] Signal code:  (-6)
[fv-az1446-488:06807] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fbaa1c42520]
[fv-az1446-488:06807] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fbaa1c969fc]
[fv-az1446-488:06807] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fbaa1c42476]
[fv-az1446-488:06807] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fbaa1c287f3]
[fv-az1446-488:06807] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fbaa20a2b9e]
[fv-az1446-488:06807] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fbaa20ae20c]
[fv-az1446-488:06807] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fbaa20ae277]
[fv-az1446-488:06807] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fbaa20ae52b]
[fv-az1446-488:06807] [ 8] plumed_master(+0x14274)[0x561f98c56274]
[fv-az1446-488:06807] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fbaa1c29d90]
[fv-az1446-488:06807] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fbaa1c29e40]
[fv-az1446-488:06807] [11] plumed_master(+0x14ed5)[0x561f98c56ed5]
[fv-az1446-488:06807] *** End of error message ***
</pre>
{% endraw %}
