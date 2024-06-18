**Project ID:** [plumID:21.034]({{ '/' | absolute_url }}eggs/21/034/)  
Stderr for source:  RiD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/RegisterBase.h:211) const Content& PLMD::RegisterBase<Content>::get(const std::vector<void*>&, const string&) const [with Content = PLMD::ActionRegisterPointers; std::string = std::__cxx11::basic_string<char>]
+++ assertion failed: m.count(key)>0
[fv-az695-955:06695] *** Process received signal ***
[fv-az695-955:06695] Signal: Aborted (6)
[fv-az695-955:06695] Signal code:  (-6)
[fv-az695-955:06695] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fca18042520]
[fv-az695-955:06695] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fca180969fc]
[fv-az695-955:06695] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fca18042476]
[fv-az695-955:06695] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fca180287f3]
[fv-az695-955:06695] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fca184a2b9e]
[fv-az695-955:06695] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fca184ae20c]
[fv-az695-955:06695] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fca184ae277]
[fv-az695-955:06695] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fca184ae52b]
[fv-az695-955:06695] [ 8] plumed_master(+0x14274)[0x55ed4f2b0274]
[fv-az695-955:06695] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fca18029d90]
[fv-az695-955:06695] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fca18029e40]
[fv-az695-955:06695] [11] plumed_master(+0x14ed5)[0x55ed4f2b0ed5]
[fv-az695-955:06695] *** End of error message ***
</pre>
{% endraw %}
